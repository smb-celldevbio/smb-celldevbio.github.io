---
layout: post
title: Junior Researcher Feature with Dr. Jay Stotsky
subtitle: Postdoctoral Researcher in Mathematics, University of Minnesota
gh-repo: daattali/beautiful-jekyll
tags: [junior feature]
comments: true
---

Since the beginning of 2021, we've been posting interviews with tenured/tenure-track level researchers, but starting this month, we're also going to post interviews with students and postdocs in our Junior Researcher Features!

In September's Junior Researcher Feature, we have an interview with [Dr. Jay Stotsky](https://cse.umn.edu/math/jay-stotsky), Postdoctoral Researcher in Mathematics, University of Minnesota.

<img src="https://smb-celldevbio.github.io/uploads/blog_images/stotsky/Jay_Stotsky.jpg" width="150" alt="Jay Stotsky" style="display: block; margin-left: auto; margin-right: auto; width: 50%;" />

**When did you first become interested in mathematics and biology?**

I have been interested in math and biology (along with chemistry and physics) as long as I can remember.
As a child, I read pretty much any book I got my hands on including some of my parents' old math textbooks
from when they were in school, and I think this helped spark my interest in math and science. In math, I
also just liked the way the different symbols looked and kept trying to learn more because I wanted to know
what symbols such as the calculus operators "d/dx" and "&#8747;", or even the square-root symbol really meant.

In college, I was not sure whether I wanted to go into a science or math, so I ended up studying chemical
& biological engineering because the required courses included a number of math and science courses that sounded interesting to me. I think this ended up being a great choice for an applied mathematician as the core courses required scientific knowledge as well as mathematical skill and taught me a lot about working on problems at the forefront of both math and science.

**Was the decision to do a Ph.D. an obvious and easy choice?**

For me, this was an easy choice. I knew early on that I wanted to pursue a career in math or science. My parents, seeing my academic interests, also encouraged me to pursue a Ph.D. as the most likely way to turn my mathematical interest into a career.

However, what field to pursue in graduate school was a difficult choice since I was interested in both applied math and chemical engineering. In particular, I wanted to learn more about how the partial differential equations that I studied in class could be solved using computational methods. I eventually had an opportunity to spend a summer working on an undergraduate research project with a math professor to develop a finite element method based multigrid solver for the diffusion equation on a sphere. I enjoyed the research a lot and this made up my mind to study applied math.

**What are the main biological research questions that you are interested in?**

My interests are generally quite wide-ranging, but lately I have become very interested in understanding how cells, tissues, and organisms are able to integrate the outputs from multitudes of biochemical pathways to make more abstract, higher level choices. For instance, growing cells must integrate many types of signals (which might include various growth factor concentrations, mechanical forces, nutritional levels, etc.) in order to eventually grow or not. I think mathematics will play an important role in understanding these types of problems for several reasons. The biological systems are typically too complicated to meaningfully understand without some sort of idealization such as can be provided by a mathematical model. Additionally, mathematical analysis might uncover principles that apply not just to one organism or cell type, but are more broadly applicable as a kind of biological strategy. I think working in this area is quite exciting and that there is starting to be a lot of close collaboration between experimental research and theory.

A somewhat related topic that I also am very interested in is the development of realistic models of the mechanical behavior of biological systems. Even at the level of a single cell, this is highly non-trivial. Cells are able to modulate their mechanical properties via complex networks of proteins that make up what is known as the cytoskeleton. Many cells continually modify the strength and alter the composition of their cytoskeleton in response to various biological signals. Thus, in response to a force, a cell does not simply respond as a passive, non-living material would, but instead, it actively changes its own mechanical properties in response to the force.

Beyond studying single cell mechanical behavior, in a multi-cellular system, adjacent cells exert forces on each other that are important to maintaining mechanical properties of the tissue, and there are even biochemical pathways that respond to mechanical force via changes in the conformation of many proteins in response to mechanical stress. This type of mechanical feedback has long been postulated to play an important role in biology, but it is only recently that the tools needed to study this phenomenon have been developed.

**What types of questions do you think will be important to answer in the future in your field?**

Over the past fifty or more years a great deal has been done to understand how biochemical processes govern cell and organism behavior. More recent results suggest that mechanical forces also play an important role. In a few cases, mechanisms have been discovered that indicate close interactions between biochemical and biomechanical processes, but a more comprehensive model of how they combine to govern growth, and morphogenesis (or how animals get to be the correct size and shape) is certainly a long-term goal.

Incorporating mechanical aspects of growth and forces generated by the cell cytoskeleton into a comprehensive theory of the mechanical behavior of biological materials also presents a fundamental challenge. There currently exist several distinct approaches of how to incorporate such phenomena (e.g. growth and intrinsic force generation) into "classical" theories of mechanics. The development of a more concrete understanding of what the various assumptions in these theories imply and whether they are equivalent or not under certain conditions seems important to establishing the validity of any mechanical model that incorporates these features. Further developments along these lines will also have to address how the biochemistry and biomechanics are coupled, for instance, to determine how the biochemical state of a cell eventually figures into constitutive equations for the mechanical properties, or to address the effects of changes in the enzymatic activity of stress-sensitive proteins in response to forces.

Another important question regards how small-scale structure - such as the properties of the cytoskeleton at each point in a cell - ultimately leads to observed cell behaviors such as cell blebbing, and directed motion. In many (perhaps most, or even all) cases, biological systems exhibit non-linear properties. However, understanding how small-scale details (e.g. properties of each particular cell) interact to yield global (e.g. tissue or system-wide) behavior in nonlinear systems has long been a difficult question to answer. It will be interesting to see how mathematical theory and the development of new computational techniques can address these types of problems.

**What mathematical and computational tools do you find useful in your work?**

I use a range of tools depending on the problem at hand. Probably I most commonly use a software suite and associated programming language called MATLAB. One particular feature I like is that it is easy to pause MATLAB in the middle of a simulation and assess how things are progressing, or even debug if need be. This is useful because in complicated models, it is difficult to guess beforehand how things will evolve during a simulation. Going through a few example simulations and pausing to check on things from time to time can greatly help to build intuition about how the model behaves and what the next steps should be.

I also use Mathematica. Mathematica can directly evaluate and work with complicated algebraic expressions. I find it very useful for simplifying complicated formulas (to the extent they can be simplified) and also for computing difficult integrals and derivatives.

Recently I have been using a program called Fenics to solve various partial differential equations. Fenics is based on the finite element method, and I like that it offers a range of different types of elements that can be easily implemented for different equations. This is useful as some of the (non-linear) equations in a model of cell motility that I am currently working on are difficult to solve and it is helpful to rapidly be able to test out various approaches to find what works.

Last but not least, familiarity with some basic principles of high-performance computation, and with procedures for running programs and transferring data on supercomputers and cluster computing systems is important.

**How would you describe the results of a recent paper you contributed to?**

A few months ago, the paper [A Random Walk Approach to Transport in Tissues and Complex Media: From Microscale Descriptions to Macroscale Models](https://doi.org/10.1007/s11538-021-00917-0) was published in the Bulletin of Mathematical Biology with co-authors Hans Othmer (Univ. of Minnesota) and Jia Gou (UC Riverside). This paper describes how a type of mathematical construct, known as a Continuous-Time-Random-Walk (CTRW) can be used to connect experimental observations with biological theories about how individual cells in a tissue behave. CTRWs have been used as models of transport phenomena for over 50 years, however, this work expands upon previous work by introducing a framework that can be applied to complicated problems that involve multiple types of transport and (linear) reactions. For instance, complex lattices such as hexagonal lattices which are often used to approximate tissue geometry, can be handled in our framework. We also discuss how the CTRWs that contain all of the cell-level processes can be simplified through the use of first-passage-times and asymptotic theory to obtain mascro-scale equations, similar to those obtained via homogenization theory. We then apply our new framework suggest how transport of a protein important in the development of a proto-organ, called the wing-disc, present in fruit fly (Drosophila melanogaster) larvae can be understood in terms of processes that occur in the cells that make up the wing-disc. Because the underlying structure of the models is quite general, I think the presented ideas could end up being quite useful to a range of scientists and mathematicians in many applications beyond what we presented in the paper.

**What makes you passionate about your work?**

I always have been interested in how things work, and the sense of discovery I get when all of the pieces fall into place and I understand something new is one motivation. In the broader picture, I find inspiration in the potential that I could (with some luck and a lot of work) contribute to important scientific advancements.

Lastly, though I am still starting out in my career, I find that reflecting on my work gives me a sense of pride. I think one benefit of working in a field where results are written down and published, is that there is a tangible record to reflect on.

**What do you like to do in your spare time outside of work?**

I have played piano for almost 25 years. I enjoy many classical works, especially those of Bach, Beethoven, Schubert, and Chopin. As a graduate student, I started playing tango music (which was originally a form of Argentian popular music) as well. One peculiarity of tango music that I enjoy is that it ranges from written-out scores all the way to jazz-like improvisation. Aside from music, I enjoy playing tennis, kayaking, hiking, and swing-dancing. Being at home more during the pandemic, I also have enjoyed trying to identify all of the bird species that live in the area - I would guess that there are several hundred species that come through during their migrations.
