---
layout: post
title: Interview with Dr. Bernie Daigle
subtitle: Associate Professor of Biological Sciences and Computer Science, University of Memphis
gh-repo: daattali/beautiful-jekyll
tags: [interview]
comments: true
---

In this blog post, we feature an Interview with <a href="https://daiglelab.org"> Dr. Bernie Daigle, Jr.</a>, Associate Professor of Biological Sciences and Computer Science, University of Memphis (UofM)

**When did you first become interested in mathematics and biology?**

I discovered my love of biology in high school. The movie Jurassic Park had released a couple years earlier, and when my biology class began a unit on genetics, I couldn’t help but be excited that the premise of the movie (genetically re-creating dinosaurs based on fossilized DNA) might one day be possible. I majored in biology as an undergraduate at Cornell University, and while there I worked on experimental research projects in yeast genetics and biochemistry. After deciding to continue my education in graduate school, I chose the Ph.D. program in genetics at Stanford University and assumed I would continue my research as an experimental biologist.

However, during my second quarter as a Ph.D. student, I enrolled in a graduate course that involved programming in Perl to answer genome-scale questions based on DNA sequence and other “omics” datasets. This was a pivotal experience for me, as it rekindled my love for programming (I had taken two years of programming in high school) and allowed me to use those skills to answer cool biological questions. From that point onward, I realized that I was meant to be a computational researcher. I redesigned my graduate curriculum to include an additional half dozen math, statistics, and computer science classes, and I joined a research lab focused on computational biology and bioinformatics (led by Dr. Russ Altman). It was here that I discovered my passion for computational biology research.

**Was the decision to do a Ph.D. an obvious and easy choice?**

For me it definitely was. As an undergraduate, I really enjoyed solving scientific problems and working on longer-term research projects. Most of these had been selected and designed for me, however, so I wanted to take the next step and begin exploring my own ideas and projects. A Ph.D. program seemed like the natural place to do this, and I was fortunate to join one of the last cohorts of students to earn a Howard Hughes Medical Institute (HHMI) Predoctoral Fellowship as a first-year graduate student. This provided 5 years of funding independent from any specific lab or project, so it allowed me to take my time and design a dissertation project from the ground up. I ultimately mapped out a bioinformatics study involving the integration of high-throughput transcriptomics datasets (back in the mid-2000s, DNA microarrays were all the rage) to identify robust gene co-expression modules that were active across a range of biological conditions. We were able to show that knowledge of these modules could be wielded to increase the experimental power of any one transcriptomics experiment: for example, a researcher could benefit from the power of a 10-sample experiment for the price of a 5-sample experiment.

<p align="center"><img src="/uploads/blog_images/daigle/Stanford.jpg" alt="" style="display: block; margin-left: auto; margin-right: auto; width: 60%;" /></p>
<p align="center"><i>Stanford’s James H. Clark Center, where I worked for six years as a Ph.D. student</i></p>

The other huge benefit of doing a Ph.D. for me was that it gave me the flexibility to broaden my educational and research trajectory to include mathematical and computational biology, which would have been much more difficult to do had I pursued a Master’s degree or entered the workforce directly.

**How did you come to run your own group?**

During graduate school, my Ph.D. advisor served as the chair of the Stanford Bioengineering department for several years, so I was exposed to multiple research projects involving the modeling and simulation of biological systems. This exposure piqued my interest, so upon graduation with my Ph.D., I joined Dr. Linda Petzold’s lab at the University of California, Santa Barbara, as a postdoctoral researcher. There, I started on a series of new projects involving stochastic modeling and simulation of single-cell systems. Within these systems, I helped develop computationally efficient techniques for rare event simulation as well as parameter estimation from time-lapse microscopy data. A specific application of the latter technique led to the precise characterization of promoter architecture (i.e., number of distinct transcriptional states occupied over time) for the mouse glutaminase gene, suggesting a much more complex architecture than had been previously predicted. In addition to these projects, I also continued working in bioinformatics in the form of mining multi-omics data for biomarkers of cancer and psychological disorders, among other conditions.

<p align="center"><img src="/uploads/blog_images/daigle/UCSB.png" alt="" style="display: block; margin-left: auto; margin-right: auto; width: 60%;" /></p>
<p align="center"><i>Eastern entrance to UCSB, with my postdoctoral home (Harold Frank Hall) in the background</i></p>

After spending two years as a postdoc and an additional three as an Assistant Researcher (Research Assistant Professor equivalent), I was ready to start my own group. In 2015, I began my position at the UofM as an Assistant Professor in Biological Sciences and Computer Science, an affiliation which seemed to fit my background and interests perfectly.

**What are your main research questions and why are they interesting?**

My current research follows naturally from my work as a Ph.D. student and postdoc and is split somewhat evenly between single-cell modeling/simulation and big data/bioinformatics. In the first area, I am currently adapting some of my stochastic parameter estimation techniques to infer gene regulatory interactions from single-cell transcriptomics data (e.g., scRNA-seq). The advantage of working with genome-scale data is that it enables inference of large-scale transcriptional regulatory networks, particularly in the case of population snapshot measurements collected as a time course. We are currently applying our regulatory network inference techniques to scRNA-seq datasets investigating the immune response to Salmonella infection.

In the second area of research, I have continued developing omics data integration and biomarker identification techniques with a specific focus on post-traumatic stress disorder (PTSD). PTSD, which can occur in response to exposure to traumatic events, is accompanied by debilitating symptoms and comorbidities such as depression, cardiovascular disease, and diabetes. PTSD is surprisingly prevalent, with a 6-7% lifetime prevalence among American adults and up to 31% prevalence in U.S. military veterans. Traditionally, PTSD is diagnosed via time-consuming, expensive, and sometimes subjective psychological assessments given by trained clinicians. One of our main research questions is whether we can replicate such diagnoses based solely on blood-based biomarkers and other non-invasive measurements taken from individuals. To answer this question, we are applying machine learning techniques to integrate and reduce the dimensionality of multiple genome-scale datasets to identify the most predictive biomarkers. Thus far, we have shown that it is indeed possible to accurately predict PTSD status based on a surprisingly small number of blood-based and non-invasive measurements (< 30). Our ongoing work in this area has focused on identifying subtypes of PTSD and using this information to further improve the accuracy of biomarker-based classification of the disorder.

<p align="center"><img src="/uploads/blog_images/daigle/UofM.jpg" alt="" style="display: block; margin-left: auto; margin-right: auto; width: 60%;" /></p>
<p align="center"><i>UofM’s University Center and J.M. Smith Hall (right foreground), home to the Daigle Lab</i></p>

**What makes you passionate about your work?**

As a computational researcher, I still get a thrill out of thinking through a methodological solution to solve an outstanding problem, implementing that solution, and seeing that solution be successful. The fact that there are always new biological and computational problems to solve keeps things interesting, and I’ve often found that even if a particular problem cannot be solved today, it is usually only a matter of time before new experimental and/or computational techniques are developed which make it possible. I also derive a lot of satisfaction from working with students and watching them develop and become independent researchers. As a bonus, my students often teach me about new techniques and ways of thinking that I would not have known otherwise.

**Do you have any advice for someone considering a career in mathematical biology?**

One thing I would suggest is to always keep an open mind, in both the research questions you choose as well as the techniques you use to answer them. It can be tempting to continue focusing on the same questions using the same techniques year after year, but some of the coolest projects I have worked on initially developed as spinoffs from main research thrusts or off-the-wall ideas from a colleague or collaborator. Diversifying your interests can also make acquiring research funding less difficult, particularly if you are able to join collaborative projects where your own expertise complements that of your collaborators.

**What do you like to do in your spare time outside of work?**

My wife and I have two kids at home under the age of six, so we spend most of our spare time hanging out with them—visiting the zoo, going on walks and bike rides, and playing at local parks. In what time is left, I try to keep up with a regular exercise routine to stay in shape and maximize energy levels. I’ve also recently taken an interest in VR (virtual reality) gaming, which provides a nice escape from the day-to-day routine.
