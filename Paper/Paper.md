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
To be rewritten
<!--

If 10 years ago it seemed largely irrelevant and out of scope to adopt FOSS (Free Open-Source Software), the setting dramatically changed. Nowadays to address methodological and theoretical issues in archaeology, FOSS are attractive and promise access to powerful toolboxes accompanied with lifelong sustainability. 
An unexpected or unintended outgrowth of the adoption of FOSS is the interaction with FOSS Communities and the philosophy of software development. Such communities "are a global melting pot of diverse professions and skills that contribute to the progression of the goals represented by the software" (Wikipedia: The Free Encyclopaedia, s.v. "Humanitarian-FOSS"). Thus, archaeologist adopting FOSS deals with free, informal and wider communities, so-called FOSS communities. Each software or a specific package develops a community maintaining the software, providing advice, case examples, advertising and developing new tools. Looking for help, new ideas, possibilities of new tasks, reading or collaborate in the development of FOSS give access for archaeologist to others, less formal, but scientific communities. Platforms like Wikipedia or Stack Overflow challenge scientific communication and the reward principle driven by the traditional academic. This paper addresses how FOSS and FOSS-communities provide a common language and goal through which foreign disciplines are revisited. It also takes this different perspectives to look how this framework could enrich and challenge science and more specifically archaeological research.

-->

# Things to be done
- Footnote/explanation on "computational Archaeology"
- Research Pipeline Figure derived from Peng and Kieran

# INTRODUCTION[^PaperOrigin]
The Open Access movement rises a lot of sympathy among archaeologists. Academia.edu has grown to one of the biggest repository for archaeological paper « freely » available, cross cutting boundaries of traditional reading circle[^Academia]. Anyone understand some of the benefits of this availability. On the other side, the Free Software movement, where the origins of the Open Access movement is to be situated, is not considered as relevant. However, on going and growing debates about benefits of dynamism in publication available through new information technologies challenge this position. Why should archaeologist consider the philosophy of Free Software with more awareness?

Even if Free Software is well established inside and outside academia, the advantages of Free software (that is "the 'free' as in 'free speech', and not the 'free' as in 'free beer' ") are not acknowledged[^FreeBeer]. Free software is in many cases (in the imaginary) understood as complicated, untrustable or non as effective as proprietary software. Generally software is considered as a tool to answer questions and the emphasis is put on the results and not on the reuse neither of work-flows nor of the collected data.

The aim of this paper is to give a brief overview of the crossing of Free Software with computational Archaeology. This closer look draws the attention on changes in information technologies that question knowledge dissemination. Not only Open Access is important to sustain for large access to research outcome but the access to the data and the analysis should be done in transparent and reproducible ways, that are closer to the ethic of scientific research. This will sustain a stronger research environment. 

Firstly, I will introduce the notion of Scientific Community and then I will concentrate on the similarities between Scientific Community and Free Software Community. In a third point, I will examine the concepts of reuse, modulation and reproducibility in archaeology, which I will illustrate with two examples.


[^PaperOrigin]: This paper is the output of a talk given during the session 10A "ArcheoFOSS: free/open source software and archaeological research, ten years later" of the [CAA 2015 "KEEP THE REVOLUTION GOING"](http://caaconference.org/). I am grateful to the organisers and to the participants for the comments in a nice and motivating atmosphere. The original paper, the slide-show and extra material are freely accessible. DOI: [10.5281/zenodo.16596](http://dx.doi.org/10.5281/zenodo.16596). A video was recorded by Doug Rocks-Macqueen and published under his project Recording Archaeology.
[^Academia]: [academia.edu](http://academia.edu) is « free to use » but it is not free. There is no API, which would have made possible a query of the growth of papers tagged with #Archaeology during the last years and assert the quoted sentence from the main text. Until now, it's just a guess ...
[^FreeBeer]: See the definition of the [Free Sofware Foundation](https://fsf.org)




# Precedent Work
The paper of Benjamin Ducke is, to my knowledge, the only article about the relation of Free (and Open Source) Software and Archaeology (@Ducke2012). He focuses the attention on the problem of 'black boxes' (@Morin2012) and of sustainability for the development of archaeological software. Proprietary software restrict the assessment and control of the processes and hinder the dissemination of the analysis. All non-owner of the specific proprietary software are de facto excluded of the reproduction of the analysis. However as he states, his article does not focus on philosophical or social aspect of Free Software. In my take up, I would like to focus narrower on these problems and how access to data questions methods established in archaeological research. 




# Scientific community

Science is cumulative even if is not clear how exactly scientific knowledge accumulates. In any case it is a community endeavour. In this process, the scientific community brings different points of views, different questions and different ways to resolve same problems. The community is a pool of inspiration: interactions encourage innovation and spark ideas about new lines of evidence, new applications, new questions, and alternate explanations. Lively interactions of the scientific community make the scientific knowledge accumulating and becoming "stable" faster[^stable knowledge].  

The scientific community is a motivating force for recognition and respect from peers and it control the quality of scientific research by scrutinising the work of other. It's a system of checks and balances that assures that claims are not fraudulent. The communication and the open process inside the community makes claim robust. It's not the claim of a unique researcher that make science strong and reliable but true scrutiny and critics of peers(@Fanelli2013). 


[^stable knowledge]: "Stable knowledge" refers to the process of establishing a fact. (see among others @Latour1979)






# Free Software and Science

Free Software shares a lot of characteristics with science. Both have scrutiny and cumulative knowledge that can be seen in process like peer reviewing, open data subject to validation and replication. There is a strong culture of credit, civility, reputation and communication

The motivations to do Science or Free Software is in many aspects similar: it's a based on the reputation you earn with your work and there is in both cases an ethic to attribute the work (@Kelty2001). In this process of credit and reputation, researcher makes their work available to others and researcher becomes identified with their work. Citations accredit reuse of ideas, concepts or code. In Free Software or  in Science differences are made according to the status of the contribution (author, contributor, maintainer). Contributions are based on same principles of cumulative knowledge, its reuse, mixing and modulation.

But similarities between Free Software and Science should not hide the differences. Dissimilarities, specifically Free Software's assets challenge in return, what is taken for granted in Science.




# Modifiability

The concept of modifiability is without any doubt the most fascinating concept among the dissimilarities between Science and Free Software (@Kelty2008: 12). Books and articles have acclimatised science making with stable knowledge. The impression given by books or articles is that of a definitive version, tangible under the fingers. But Free Software with practices like forking, new versioning, cloning, constant evolution of source code questions this concept. Every "newly available" operating system, even proprietary, contains older pieces of software.

On top of the drawing (), a representation of the current way of doing research with stable knowledge: results are only used, when they are stable. At the bottom a prospect on how software development looks like and how science could be made. The process of sharing and reusing  knowledge is becoming more dynamic. However this poses a question. If the content does not need any more to be stable and it is uses like Free Software, "how should the authority, stability and reliability of knowledge be assessed" (@Kelty2008:300)?  In this sense FS challenges the "Power of Knowledge"[^PowerOfKnowledge].

[^PowerOfKnowledge]: I refer to the expression of C. Kelty is his book, Two Bits [@Kelty2008]

![Modifiability of knowledge](Images/ResearchCulture-Inv.png)
<footer class="source">Image: [Bartling et al. 2014, Opening Science (fig. 3, 10)](http://dx.doi.org/10.1007/978-3-319-00026-8_1)  |  CC BY-NC 3.0 </footer>  





# Free Software challenges the Power of Knowledge 

New practices of publication with the appearance of new information technologies render the knowledge more dynamic (@Vinck2014). Wikipedia is the most famous example with content that can be updated, changed, deleted, copied, forked at any time by anyone. The last 10 years have seen a complete revaluation of Wikipedia at the University. 10 years ago, as I saw it in France, it was mostly rejected as "untrustable source". Now academics explain how to use it scientifically.

Even if there is a growing discussion on dynamic publication there are still few examples of work-flows in academia.  The model proposed by Kansa and others -- "Push and Publish"-- will certainly have a bright future (@Kansa2014). In this model, data are published on-line and may be updated, completed, corrected, cloned after the first online release. Repositories and digital archiving enable new dissemination methods.

By looking at the practice of Free Software, it is easier to ask how authority is established and question the finality of publication. Free Software focus not only on the results (the Software) but focus on how it works, on the possibility to be controlled, improved and reused. Free Software allows to computational archaeology not only to focus on the results but broaden the attention consequently on how evidence are reached. This is the only way to reconcile  the ethic of computational science and the establishing of facts. It's with this sense in mind, that I will turn to the problem of reproducibility for computational archaeology.

![Dynamic Publication](Images/DynamicPublicationFormats6-Inv.png)
<footer class="source">Image: [Heller et al. 2014, Opening Science (fig. 5, 200)](http://dx.doi.org/10.1007/978-3-319-00026-8_13)  |  CC BY-NC 3.0 </footer>

# Reproducibility

Reproducibility allows anyone to start from the same data, check all the process in order to verify the results. The complete process, from the ideas and data to the publication as been quoted as research Pipeline (Peng). In Archaeology there is no culture of exchanging code for reproducibility until now, even if it is changing[^SAA2015]. If we turn back to the definition of science, however, reproducibility and sharing of code is even the sine qua non for science, to permit the community to scrutinise the work. It's the only way to stick with a robust exposition of facts. "We often forget that scientific knowledge is reliable not because scientists are more clever, objective or honest than other people, but because their claims are exposed to criticism and replication." [@Fanelli 2013] 

For computational research, best practices permit to knit together data, code, and results trough scripting[@Marwick2015]. Reproducibility must be attain to stick to the ethic of science. Moreover reproducibility has a huge potential for empirical research, like archaeology. Reproducibility is important in order to reuse and maintain data up to date. If, as shown in the **Published and Push** model, data are updated, then the analysis can be quickly updated, and therefore results, do not need to stay in the state as published.

Reproducibility helps to cast the research in modules. Bits of research based on code can be transformed and reuse for similar project or build upon for new project. The modularity of code impacts on two levels. Firstly, open and reproducible archaeology makes resources easy available as paradigmatic pedagogical object. Hands-on workshops, modulations of research, testing of new hypothesis can be done in teaching environments with a direct, DIY approach. Secondly, the modularity of Free Software ease the blurring of academic borders in unpredictable ways. By providing a common language, Free Software creates new transversal communities that makes science stronger. 

[^SAA2015]: For example, see the meeting during the SAA 2015 in San Francisco, "Electronic Symposium Open Methods in Archaeology : How to Encourage Reproducible Research as the Default Practice?" organised by Ben Marwick, Mark Lake and Andrew Bevan. 


# Conclusion

Free Software challenges the authority of science and provides a mean to transform computational archaeology by questioning transmission and reuse of research. Free Software coupled with reproducibility by means of scripting make all the research pipeline available to the scrutiny of the community and reconciles together data, process and results. Making the complete research pipeline available, will change archaeology to a more open and robust computational research environment.


# References
