---
title: "Archaeology as Community Enterprise"
output:
  html_document:
    toc: yes
bibliography: bibliography.bib
csl: harvard-european-archaeology.csl
---
<style>

body {  background-color: black;
}

h1 {  color: #3399ff;    }
h2 {  color: #3399ff;    }
h3 {  color: #3399ff;    }
slide { background-color: #000000;}

ul{ color: #FFF;}
p{ color: #FFF;  font-size: 1.5em;}
.title-slide hgroup h1 {color: #FFF;}




</style>

# Abstract
To address methodological and theoretical issues in archaeology computational (and quantitative) archaeology is commonly used. However few debates occur on the software that perpetrate the analysis, manipulate data or how this should be available. This paper addresses the need to use Free Software at a moment, where data is becoming easy available online, and tools to make reproducible research become widespread. This configuration challenges current ways of publishing quantitative research.


# INTRODUCTION[^PaperOrigin]
The Open Access movement rises a lot of sympathy among archaeologists. Academia.edu has grown to one of the biggest repositories for archaeological papers « freely » available, cross cutting boundaries of traditional reading circles[^Academia]. Everyone understands some of the benefits of this availability. On the other side, the Free Software movement, where the origins of the Open Access movement is to be situated, is not considered as relevant. However, on going and growing debates about benefits of dynamism in publication available through new information technologies challenge this position. Why should archaeologists consider the philosophy of Free Software with more awareness?

Even if Free Software is well established inside and outside academia, the advantages of Free software (that is "the 'free' as in 'free speech', and not the 'free' as in 'free beer' ") are not acknowledged[^FreeBeer]. Free software is in many cases (in the imaginary) understood as complicated, untrustable or no as effective as proprietary software. Generally software is considered as a tool to answer questions and the emphasis is put on the results and not on the reuse neither of work-flows nor of the collected data.

The aim of this paper is to give a brief overview of the intersection of Free Software with computational Archaeology. This closer look draws the attention on changes in information technologies that question knowledge dissemination. Not only Open Access is important to sustain for large access to research outcome but the access to the data and the analysis should be done in transparent and reproducible ways, that are closer to the ethic of scientific research. This will sustain a stronger research environment. 




[^PaperOrigin]: This paper is the output of a talk given during the session 10A "ArcheoFOSS: free/open source software and archaeological research, ten years later" at the [CAA 2015 conference "KEEP THE REVOLUTION GOING"](http://caaconference.org/). I am grateful to the organisers and to the participants for the comments in a nice and motivating atmosphere. The original paper, the slide-show and extra material are accessible online. DOI: [10.5281/zenodo.16596](http://dx.doi.org/10.5281/zenodo.16596). A video of the lecture was recorded by Doug Rocks-Macqueen and has been published under his project *Recording Archaeology*.
[^Academia]: [academia.edu](http://academia.edu) is « free to use » but it is not free. There is no API, which would have enable a query of the growth of papers tagged with #Archaeology during the last years and consequently asserts the affirmation from the main text. Until now, it's just a guess ...
[^FreeBeer]: See the definition of the [Free Sofware Foundation](https://fsf.org)




# Precedent Work
The paper of Benjamin Ducke is, to my knowledge, the only article about the relation of Free (and Open Source) Software and Archaeology [@Ducke2012]. He focuses the attention on the problem of 'black boxes' [@Morin2012] and of sustainability for the development of archaeological software. Proprietary software restricts the assessment, the control of the processes and hinders the dissemination of the analysis. All non-owner of the specific proprietary software are *de facto* excluded of the reproduction of the analysis. However as he states, his article does not focus on philosophical or social aspects of Free Software. In my take up, I would like to focus narrower on these problems and how access to data questions methods established in archaeological research. 




# Scientific community

Science is cumulative even if it is not clear how exactly scientific knowledge accumulates. In any case it is a community endeavour. In this process, the scientific community brings different points of views, different questions and different ways to resolve same problems. The community is a pool of inspiration: interactions encourage innovation and spark ideas about new lines of evidence, new applications, new questions, and alternate explanations. Lively interactions of the scientific community make the scientific knowledge accumulating and becoming "stable" faster[^StableKnowledge].  

The scientific community is a motivating force for recognition and respect from peers and it controls the quality of scientific research by scrutinising the work of others. It's a system of checks and balances that assures that claims are not fraudulent. The communication and the open process inside the community make claim robust. It's not the claim of a unique researcher that makes science strong and reliable but true scrutiny and critics of peers [@Fanelli2013].


[^StableKnowledge]: "Stable knowledge" refers to the process of establishing a fact, among others @Latour1979.






# Free Software and Science

Free Software shares a lot of characteristics with science. Both have scrutiny and cumulative knowledge, which can be seen in process like peer reviewing, open data subject to validation and replication. There is a strong culture of credit, civility, reputation and communication

The motivations to do Science or Free Software is in many aspects similar: it's based on the reputation earned with published work and there is in both cases an ethic to attribute the work [@Kelty2001]. Researcher make their work available to others and citations accredit reuse of ideas, concepts or code. In Free Software or  in Science differences are made according to the status of the contribution (author, contributor, maintainer, etc.). Contributions are based on same principles of cumulative knowledge, its reuse, mixing and modulation.

But similarities between Free Software and Science should not hide differences. Dissimilarities, specifically Free Software's assets challenge in return, what is taken for granted in Science.




# Modifiability

The concept of modifiability is without any doubt the most fascinating concept among the dissimilarities between Science and Free Software [@Kelty2008: 12]. Books and articles have acclimatised science making with stable knowledge. The impression given by books or articles is that of a definitive version, tangible under the fingers. But Free Software with practices like forking, new versioning, cloning, constant evolution of source code questions this concept. Every "newly available" operating system, even proprietary, contains older pieces of software.

![Modifiability of knowledge](Images/ResearchCulture-Inv.png)
<footer class="source">[Figure1] [Bartling et al. 2014, Opening Science (fig. 3, 10)](http://dx.doi.org/10.1007/978-3-319-00026-8_1)  |  CC BY-NC 3.0 </footer>  

On top of the drawing [Figure1], a representation of the current way of doing research with stable knowledge: results are only used, when they are stable. At the bottom a prospect on how software development looks like and how science could be made. The process of sharing and reusing  knowledge is becoming more dynamic. However this poses a question. If the content does not need any more to be stable and it is used like Free Software, "how should the authority, stability and reliability of knowledge be assessed" [@Kelty2008: 300]?  In this sense Free Software challenges the "Power of Knowledge"[^PowerOfKnowledge].

[^PowerOfKnowledge]: I refer to the expression of C. Kelty in his book, Two Bits [-@Kelty2008]







# Free Software challenges the Power of Knowledge 

New practices of publication with the appearance of new information technologies render the knowledge more dynamic [@Vinck2014]. Wikipedia is the most famous example with content that can be updated, changed, deleted, copied or forked at any time by anyone. The last 10 years have seen a complete revaluation of Wikipedia at the University. 10 years ago, as I saw it in France, it was mostly rejected as "untrustable source". Now academics explain how to use it scientifically.

Even if there is a growing discussion on publication of dynamic content there are still few examples of work-flows in academia.  The model proposed by Kansa and others -- *Push and Publish* -- will certainly have a bright future [@Kansa2014]. In this model, data are published on-line and may be updated, completed, corrected, cloned after the first online release. Repositories and digital archiving enable new dissemination methods.

By looking at the practice of Free Software, it is easier to ask how authority is established and question the finality of publications. Free Software focuses not only on the results (the software) but unifies operations and the possibility of control, improvement and reuse. Free Software allows computational archaeology not only to concentrate on the results but broaden the attention consequently on how evidences are reached. This is the only way to reconcile  the ethic of science and the establishing of (computational) facts. It's with this sense in mind, that I will turn to the problem of reproducibility for computational archaeology.


# Reproducibility

Reproducibility allows anyone to start from the same data, check all the processes in order to verify the results. The complete process, from ideas and data to the publication as been termed as research pipeline [figure 2]. In Archaeology there is no culture of exchanging code for reproducibility until now, even if it is changing[^SAA2015]. If we turn back to the definition of science, however, reproducibility and sharing of code is even *sine qua non* for science, to permit the community to scrutinise the work. It's the only way to stick with a robust exposition of facts. "We often forget that scientific knowledge is reliable not because scientists are more clever, objective or honest than other people, but because their claims are exposed to criticism and replication." [@Fanelli2013] 

![Research Pipeline](Images/ResearchPipeline-Inv.png)
<footer class="source">[Figure2] Research Pipline (after ideas from Roger Peng and Kieran Healy)  | N. Strupler  CC BY-NC 4.0 </footer>  

For computational research, best practices permit to knit together data, code, and results trough scripting [@Marwick2015]. Reproducibility must be attained to adhere to the ethic of science. Moreover reproducibility has a huge potential for empirical research, like archaeology. Reproducibility is important in order to reuse and maintain data up to date. If, as shown in the *Published and Push* model, data are updated, then the analysis can be quickly updated, and therefore results, do not need to stay in the (outdated) state as published.

Reproducibility helps to cast the research in modules. Bits of research based on code can be transformed and reused for similar projects or build upon for new projects. The modularity of code impacts on two levels. Firstly, open and reproducible archaeology makes resources easy available as paradigmatic pedagogical object. Hands-on workshops, modulations of research, testing of new hypothesis can be done in teaching environments with a direct, **do it yourself** approach. Secondly, the modularity of Free Software eases the blurring of academic borders in unpredictable ways. By providing a common language, Free Software creates new transversal communities that make science stronger. 

[^SAA2015]: For example, see the meeting during the SAA 2015 in San Francisco, "Electronic Symposium Open Methods in Archaeology : How to Encourage Reproducible Research as the Default Practice?" organised by Ben Marwick, Mark Lake and Andrew Bevan. 


# Conclusion

Free Software challenges the authority of science and provides a mean to transform computational archaeology by questioning transmission and reuse of research. Free Software coupled with reproducibility by means of scripting makes all the research pipeline available to the scrutiny of the community and reconciles together data, processes and results. Making the complete research  available, has the potential to change computational archaeology into a more open and robust research environment.

---
nocite: | 
  @Heller2014
...


# References
