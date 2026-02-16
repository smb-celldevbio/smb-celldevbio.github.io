---
layout: post
title: Interview with Dr Samantha Linn
subtitle: SF Postdoctoral Fellow in the Department of Mathematics at Imperial College London
gh-repo: daattali/beautiful-jekyll
tags: [interview]
comments: false
---

In this blog post, we feature <a href="https://sites.google.com/view/samanthalinn/">Dr. Samantha Linn</a>. Samantha is an NSF Postdoctoral Fellow in the Department of Mathematics at Imperial College London, mentored by Paul Bressloff. She received her PhD in mathematics in 2025 at the University of Utah where she was advised by Sean Lawley. Her research concerns stochastic processes inspired by biology.

<p align="center"><img src="/uploads/blog_images/Linn/SL_headshot.png" alt="" style="display: block; margin-left: auto; margin-right: auto; width: 50%;" /></p>

**When did you first become interested in mathematics and biology?**

I'm not sure there was a 'first' time; as long as I can remember I have gravitated towards science in general. My experience with mathematics as a young student definitely centered around problem solving, which came naturally to me and which I also thoroughly enjoyed. (People close to me are all terribly aware of my life-long sudoku obsession!) An interest in biology, specifically, came later. Perhaps I was overwhelmed by its complexity but now my perception is one of admiration. Biological systems are an incredible example of world-building and this phenomenon has become the main inspiration behind the world-building I try to do with mathematics.


**Was the decision to do a Ph.D. an obvious and easy choice?**

Going to graduate school truthfully had not crossed my mind until I essentially found myself in it. I got my Bachelor's degree in biomedical engineering with my sights set on medical school, but something about that path did not feel genuine. Thankfully I had mentors who must have seen a sparkle in my eye when I did math and who encouraged me to give it a try. It is retrospectively comedic that my interpretation of 'give it a try' was to enroll in a PhD program, but becoming a mathematician has been an incredible blessing and I am very grateful to those mentors.

**What are the main biological research questions that you are interested in?**

There is something remarkable and beautiful to me about how robustly biological systems behave in the face of overwhelming randomness. Broadly speaking, any given biological system is composed of many noisy individual actors making simple and perhaps uninteresting decisions, yet the system-wide dynamics that emerge are often highly structured and somehow not so noisy. Almost without choice I find myself spending heaps of time trying to understand how this can possibly be true. Sometimes this exercise brings me closer to specific biological questions and sometimes it sends me into an abstract abyss!

**What mathematical and computational tools do you find useful in your work?**

Oftentimes my projects start with a stochastic differential equation that defines the dynamics of some stochastic process. This form does not necessarily lend itself well to computing quantities of interest such as first-passage time statistics and splitting probabilities. Instead, we can formulate the corresponding **Fokker-Planck equation** (FPE), which is a partial differential equation that describes the dynamics of the probability distribution of the original stochastic process. FPEs are much more conducive to analysis; for instance setting the time derivative to zero allows us to solve for the steady-state distribution of the process (if this exists). But let's suppose it doesn't exist; suppose we have a stochastic searcher in a confined domain and it can permanently 'escape' through a semi-permeable boundary but only by interacting with the boundary in a specific way (<em>e.g.,</em> the searcher needs to exhibit a specific spatial conformation to be recognized by the binding element of the boundary). In this case, the toolbox of <a href="https://en.wikipedia.org/wiki/Renewal_theory">**renewal theory**</a> lets us construct the searcher's full trajectory (until escape) in terms of excursions in the bulk domain partitioned by unsuccessful escape attempts. Each excursion between unsuccessful attempts can then be understood as if the boundary were perfectly impermeable. With this construction we can once again make use of the corresponding FPE to determine, for instance, the searcher distribution prior to escaping and the statistics of the time taken for the searcher to escape.

**What makes you passionate about your work?**

As it turns out, doing mathematics research is a highly creative process and I really enjoy the feeling of discovery that it comes with. To prove things that are eternally true...and to go through this process with other passionate mathematicians...what a delight.

<div style="display: flex; align-items: center; gap: 40px;">
  
  <img src="/uploads/blog_images/Linn/SL_picture.png" alt="" style="width: 35%" />

  <p style="flex: 1;">
    
<b>What do you like to do in your spare time outside of work?</b>
<br>
<br>
Anything on a mountain! My time in Utah shaped me into an avid cyclist,  climber, and skier.

  </p>

</div>

**Any advice for someone considering a career in mathematical biology?**

Have courage in shaping your own identity within the vast sea that is mathematical biology. Being a mathematical biologist can look many different ways: we can be in the field collecting data, simulating complex dynamics, constructing and analyzing theoretical models. There is space for all of us to venture these uncharted seas and learn from each other along the way.

<p><em>If you are interested in learning more about Samantha work, you can find her at <a href="https://ecmtb2026.org/">joint ECMTB and SMB meeting</a> in Gratz </em></p>
