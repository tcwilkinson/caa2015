discussing the merits, challenges and drawbacks that the FOSS movement in archaeology has brought to the wider discipline
 ->  the actual impact of FOSS on archaeological practice


If 10 years ago it seemed largely irrelevant and out of scope to adopt FOSS (Free Open-Source Software), the setting dramatically changed. Nowadays to address methodological and theoretical issues in archaeology, FOSS are attractive and promise access to powerful toolboxes accompanied with lifelong sustainability. 
* An unexpected or unintended outgrowth of the adoption of FOSS is the interaction with FOSS Communities and the philosophy of software development. Such communities "are a global melting pot of diverse professions and skills that contribute to the progression of the goals represented by the software" (Wikipedia: The Free Encyclopedia, s.v. "Humanitarian-FOSS"). Thus, archaeologist adopting FOSS deals with free, informal and wider communities, so-called FOSS communities. Each software or a specific package develops a community maintaining the software, providing advices, case examples, advertising and developing new tools. Looking for help, new ideas, possibilities of new tasks, reading or collaborate in the development of FOSS give access for archaeologist to others, less formal, but scientific communities.*
Platforms like Wikipedia or Stack Overflow challenge scientific communication and the reward principle driven by the traditional academic. This paper addresses how FOSS and FOSS-communities provide a common language and goal through which foreign disciplines are revisited. It also takes this different perspectives to look how this framework could enrich and challenge science and more specifically archaeological research.




Intro:
1-2: Science Community ->  Diversity, innovation are needed for science
3-4: FOSS and Free Science  -> Community play a role
What happend when you mix the communities of FOSS and Archaeology?
-> Change the norm: reproducibiltiy

5-6: From REUSE  (FOSS Broadly) to Reproducibility
    -> Release of Data and more and more Raw data
    with an appropriate Licences
The existence of Free Software relies on intellectual property and licensing law.


7: Publication

6-7: reuse of Code as a tool. Mandatory (GNU Licence)
    -> R: CA, PCA, LDA, 
    Calcolatory R

8-9: Quick adaptation of Ideas from other discipline
    -> Diversity make strength
    -> Innovation for new problems




Archaelogical Science as Community Enterprise
 
Good morning, my name is Néhémie, I am a PhD student in Near Eastern Archaeology working on the Bronze Age Capital of the Hittite, Hattusa, in Central Anatolia Turkey - So far for the self-promotion. I am going to explore the ways FOSS impact on the concept of reuse and mixing of Knowledge in archaeology and the challenges for scholars, especialy the young one.  This will provide us with a background to look closer at the impact of Reproducibility in Archaeology, for wich I will show some example mainly with R.

MOTIVATION:  Some words on my motivations: I am always diaspointed  when I speak of FS, people  still don't understand why FS are important. In this talk, I won't give revolutionary facts but I wanted to make clear how FS already influenced scientific research in general AND in archeology. As a young scientist, I need to be prepared to make a strong statement to defende the way I use it in my PhD.


SUMMARY
Let me briefly outline my talk. We will progress as follow: 
    First I will introduce the notion of Scientific Community 
    Then I will concentrate on the similarties between Scientific Community and FS Community ...
    In a Third point i will examine the concept of Reuse, Modulation and Reproducibtily in Archaeology
    Finaly I will show 3 examples to illustrate impact of the FOSS movement on Archaeology ...
    and conlcude



I will begin my Talk by briefly outlining what is The Scientific community to make the similarities and the differences with FS more apparent. 

1)Why is the community so important?
Sience is cumulative even if how exactly sienctific knowledge accumulate is not clear. In any case it is a community endeavour, you can't do science alone. Community make the scientific knowledge accumulating and becoming "stable" faster. (I choosed the word "stable knowledge" to avoid "truth knowledge" and in reference to the process of establishing a fact (Latour and others) 
-> Diversity makes the difference

Point of views
"Scientists from diverse backgrounds bring many points of view to bear on scientific problems.  Scientists have different strengths and different interests. Not only do people from different backgrounds choose to investigate different questions, but they may approach the same question in different ways. "

Diversity invigorates problem solving. 
"A diverse community is better able to generate new research methods, explanations, and ideas, which can help science over challenging hurdles and shed new light on problems. Science benefits from practitioners with diverse beliefs, backgrounds, and values to balance out the biases that might occur if science were practiced by a narrow subset of humanity. Scientists strive to be impartial and objective in their assessments of scientific issues, but in those occasional cases in which personal biases sneak in, they are kept in check by a diverse scientific community."





2) Which are the functions served by the community

Inspiration. 
"Community-level interactions encourage innovation and spark ideas about new lines of evidence, new applications, new questions, and alternate explanations. "

Motivation.
"Community offers scientists the prospect of recognition from their peers. In science, achievement is usually measured, not in terms of money or titles, but in terms of respect and esteem from colleagues."
			
A cumulative knowledge base. 
"Science builds on itself. We wouldn't have general relativity if we didn't have classical mechanics. And we wouldn't have classical mechanics if we didn't have Galileo’s studies of motion and revolutionary ideas about astronomy. A similar deep history spanning hundreds of years could be given for almost any scientific idea. The scientific community provides the cumulative knowledge base on which science is built."

Scrutiny. 
"Participating in the scientific community involves scrutinizing the work of others and allowing your own work to be similarly evaluated by your peers. This system of checks and balances verifies the quality of scientific research and assures that evidence is "

=I’d like to recap on the Scientific Community: it's the communication and the open process that make it stronger. It's not the claim of a unique researcher that make science strong and reliable but tue scrutinity and critics of the peers. Now I would like to move on to FOSS





3) FS and Free Science

Free Software share a lot of characteristic of the science: they have
 - peer review, open data subject to validation and replication (Scrutinity, Cumulative Knowledge)
 - culture of credit, civility and reputation (Points of views, motivation, inspiration)

<!--
In Science
"the circumstance that the more widely scientists make their intellectual property available to others, the more securely it becomes identified as their property. For science is public not private knowledge. Only by publishing their work can scientists make their contribution (as the telling word has it) and only when it thus becomes part of the public domain of science can they truly lay claim to it as theirs. For the claim resides only in the recognition of the source of the contribution by peers" [@Garfield1979]  (after Kelty 2001).
-->

->  The motivations to do Science or FS is often seen to been in many aspects similar: it's a based on the reputation you earn with your work and there is in both case an ethic to attribuate the work (Kelty 2001) In this process of credit and reputation, researcher make their work available to others and resaercher becomes indentified with their work. Citation then aknowledge/acredit reuse of ideas / concepts /code... In the FS movement you publish the code and if you're accredited as author / contributor if it's used / reused / modified ....  Free Software and Science are based on the same principle of cumulative knowledge, reuse, remixing and modulation. 

BUT similarities beetwen structures of the FS and Science should not hide the differences. Because FS and Science have a lot of similarities it is easier to better understand them, to see how they work and how they are structured. Then it's important to focus on the dissimilarities. FS impress most scientist due to the size of projects, indirect cooperation with people all around the world, the way project are developped, maintained, contested, and how ideas are exchanged. These dissimlarities challenge in return what is taken for granted in science . 



4) Modifiability

The concept of modifiability is without any doubt the most fascinating concept among the dissimilarities between Science and Free Software (Kelty 2008: 12). Books and articles have aclimatized us with stabile knowledge. The impression given by a book or an article is that you have a definitiv version  in your hand (Archaeologist speak mostly of "end publication" to contrast with "on going report"). Books or articles are authoritative and even more authoritative if they are quantified with a number of citations and downloads. If you publish the same content online and in a book, the book is percieved as more authoritative. 
But FS with practices like forking, new versioning, constant evolution of the source code interroge this concept. "How should the authority, stability, and reliability of knowledge be assessed when work can be rendered permanently modifiable? (Kelty 2008:300) "



5) FS Chalenge the Power of Knowledge

New practices of publication with the appearance of new information technologies render the knowledge more dynamic (@Vinck2014). Wikipedia is the most famous example with a content that can be updated, changed, deleted, copied, forked at any time by anyone. The last 10 years have seen a complet reevaluation of Wikipedia at the University. 10 years ago it was mostly rejected as "untrustable source". For example as I started as undergraduate, Professor were more or less forbiding the usage of Wikipedia but some years after same professor explain how to use scientificaly Wikipedia, and some yeras after they started to actively contribute to it. 

Wikipedia reveals how complex the system of evaluation of the knowledge is and how it's now challenged. There is still few example form the academia but  workflow are to be created. As en example for archaeology Eric Kansa advocates for "Push and Publish" workflow (@Kansa2014).

FS interroge how authority is establish and question the finality of publication. This dissimilarity, playing with content in constant dynamic, give the oppurtunity to better focus on the workflow and not only the results.



6) Reproducibility

An aspect now highly debated in Science and rapidly and steadly growing in Archaeology is reproducibility.  Reproducibility allow anyone to start from the same data to arrive at the same conclusion. In Archaeology there is no culture of exchanging code for reproducibility until now but it is changing. If we turn back to the definition of science, reproducibility and sharing of code is even the sine qua non for the science, to permit the community to scrutinise the work: 

« We often forget that scientific knowledge is reliable not because scientists are more clever, objective or honest than other people, but because their claims are exposed to criticism and replication.» [@Fanelli 2013] 

If you don't have the code or the possibility to critic and explore the work, is that reliable? But moreover are scientist not blocking Science if it is not reproducible? (some would like to go to say that is missconduct).

Now I will expose the benefits of reproducibility for Archaeology as community enterprise:  Besides a trustful and better practice of science reproducibility is important for:
 - First Pedagogy  
 - Second Blurring the community borders 

<!--
The changing meaning of the *finality* of a scholarly or creative work (Kelty 2008: 270)
Free Software is no longer only about software—it exemplifies a more general reorientation of power and knowledge. (Kelty 2008: 2)
-->



7) Pedagogy. 

First of all FS have a pedagogical aspect that you can't find with others software. 

To read the code, and more precisely to read commented code permit to learn quickly. Some said for FS "In pedagogical terms, Windows is to fish as UNIX is to fishing lessons. (Kelty 2008: 132)". One of the most classical book in FS is the Lions' Commentary on UNIX 6th Edition. This a commentary of the V6 of UNIX that has been used by a lot of student to understand how UNIX works. Making Litterate Programming , that is " concentrate [...] on explaining  to *human beeings" what we want a computer to do" [@Knuth1984: 97] give the opportunity to concentrate on the process.

There is of course  example for Archaeology - Note: I will mostly speak of R beceause It's one of the software I used the most and I know the best - 
    David L. Carlson: An R Companion to Quantifying Archaeology by Stephen Shennan. 
    It's a comment of the work of Shennan that make easier to access the knowledhg of Shennan. Most importantly it allow then to hack (modulate) the code to use it quicly for your own quesiton
    Quantitative Archaeology Wiki  from isoa.it too. Exactly the same with possibility of reuse.

In Pedagogical term Reproducibility are a big help to approach different knowledges, and is perfect for a DIY practice. In this case, code makes learning of statistic for archaeologist more enjoyable. Even if the learning curve is steep it's not a wall! FS in archaeology must be more stressed as a paradigmatic pedagogical object. I think there is a lot of work to do in this direction.

Now I will move to my second point on the challenge apported by FS: blurring the border.



8) Blurring the border

As I show at the begining of my talk, community is important for mixing ideas. The modularity of FS ease the blurring of academic border in imprivisible ways. As an example, I will present my work on hittite seals. I started a project with R on seals and created a data base with some code as I was looking into multivariate analysis. I presented my work during an R Conference in Lyon and I had a lot of feedback. Eventually my dataset, code and my questions served as a Bachelor thesis in statistical modeling. Then I came back with the results and we are now contribuating to transform the work in an article.  This example shows that the borders are not just blurred in one way (that is archaeologist need statistic) but in the other way arround too (What are archaeologist looking for and awaiting from statistician?)

Reproducibilty make the modulation of knowledge easier and quicker and challeng how the knowledge is transmitted.


10) The Conclusion
    In this presentation I wanted to explore the relation of FS with archaeology. It's a personnal statement but I wanted to explain how FS is influencing my practice of archaeology. I hope to have been able to show that the effect of FS in Science and the perspective it oppens. Even if - I hope - a lot of what I have say is not revolutionary,  this does of course highlight the need for further advocaca for FS in archaeology and I would like to see more debates on how FS challenge Knowledge transmission. I would now like to give you the opportunity to ask questions. Thank you very much for listening.

    


<!--


A Generic Conference Talk Outline

This conference talk outline is a starting point, not a rigid template. Most good speakers average two minutes per slide (not counting title and outline slides), and thus use about a dozen slides for a twenty minute presentation.

    Title/author/affiliation (1 slide)
    Forecast (1 slide)
    Give gist of problem attacked and insight found (What is the one idea you want people to leave with? This is the "abstract" of an oral presentation.)
    Outline (1 slide)
    Give talk structure. Some speakers prefer to put this at the bottom of their title slide. (Audiences like predictability.)
    Background
        Motivation and Problem Statement (1-2 slides)
        (Why should anyone care? Most researchers overestimate how much the audience knows about the problem they are attacking.)
        Related Work (0-1 slides)
        Cover superficially or omit; refer people to your paper.
        Methods (1 slide)
        Cover quickly in short talks; refer people to your paper. 
    Results (4-6 slides)
    Present key results and key insights. This is main body of the talk. Its internal structure varies greatly as a function of the researcher's contribution. (Do not superficially cover all results; cover key result well. Do not just present numbers; interpret them to give insights. Do not put up large tables of numbers.)
    Summary (1 slide)
    Future Work (0-1 slides)
    Optionally give problems this research opens up.
    Backup Slides (0-3 slides)
    Optionally have a few slides ready (not counted in your talk total) to answer expected questions. (Likely question areas: ideas glossed over, shortcomings of methods or results, and future work.




Philosophy of FOSS and philosophy of Science (Free Science, C. Kelty)
Use extended definition of Free Software. Introdcution of Recursive Public
 - Development of FOSS
 -  Is there really no Influence in Archaology? Whole concept of sharing in there: yeah may be not only specific on archaeology
 - Copyright and copyleft are challenging

2) Role of community 
 - Exchange, new ideas -> line of codes // articles | blogpost How To Do | Tutorials ...
 - Where we are lookgin for ideas to cope with big data
 - Not easy to find friend to play with ...

3) Examples
   - R 
Calcolatory: R 
  - Wikipedia 
  -QGIS will be one of this example
(Graham and Mirko Novàk)
LA communanauté qui définit et détermine la qualité
Today we are faced with a situation where publication has become trivial, but verification and the management"

4) What can Archaeology do for FOSS
Philo of FOSS is to give back: aknowledge, promote and engage wit FOSS. Use Archaeology for FOSS.

Price of FOSS conference: is that real ??? 450 Euros ???
-> would have  liked to see "Our sessino is open to everyone with our without monetary retribution"



-->