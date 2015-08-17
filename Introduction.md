# Introducing the Problem

## Learning objectives
* Understand the current issues and barriers to reproducibility
* Understand why the whole workflow is important
* Understand documentation/organizational issues underpinning reproducibility 

## What is the problem?

Researchers often have three broad goals for their work. The first is that they are interested in studying innovative ideas and want to discover new things about how the world works. Second, they are interested in producing reproducible results; they want to be able to find their results again, and they want others to be able to find them as well. Finally, researchers want to build off both their own and the work of others in order to accumulate knowledge over time; they want research to move our understanding of the work forward. 

All three of these ideals are supposed to be embodied in the published, peer-reviewed scientific literature – the place where scientific knowledge is accumulated and built upon. We want to believe that the published literature embraces these three ideals of novel discoveries, reproducibility, and tracking the accumulation of knowledge. However, over the past few years there has been increasing concern that many research findings across fields (e.g. cancer biology, psychology, and political science) in the published literature may not be as reliable as we would hope. Though there have been several high profile fraud cases the last several years, this is typically not a widespread problem. What we will talk about today are standard research practices that lead scientists to produce research that is more difficult to reproduce and replicate, thus leading to generally low levels of replicability. 


## What is Reproducibility?

Before we go any further, I want to define what I mean when I say reproducibility. This is a broad term which has been used by many different people to mean different things, so I want to make sure we’re all on the same page. 

One way in which a study can be reproducible is that if you took someones data and their code/analysis scripts and reran exactly what they did, you would be able to reproduce the numbers that are reported in their paper. This is sometimes called `computational reproducibility`. This one might sound rather simple, but it can be surprisingly tricky. For example, the Quarterly Journal of Political Science requires that all submitted articles also submit a ‘replication package’ which includes all the data and code required to replicate the numbers in the articles. These are then subjected to internal review. Over the last two years, 14 of the 24 empirical papers, 58 percent, subjected to this review showed differences between the results reported in the paper and the results obtained from the internal review.

Another type of reproducibility is the question of whether we can reproduce what was done. So, do we have enough information to rerun the experiment or survey the way it was originally conducted? This is sometimes referred to as `empirical reproducibility`.

Finally, there is the question of, if we have enough information to reproduce the studies protocol completely, and reproduce the analyses completely, and run them on independent data set, would we reproduce the results? Would we come to the same statistical conclusions as the original study? This is often referred to as the `replicability` of the study.

Now, all three of these are important, and if you’ll notice we can’t even attempt the third type without the first two types, but often in science we want the results of studies to be reproducible, so we want our scientific findings to replicate. For this workshop, we’ll be talking about issues that should increase all three type of reproducibility, towards the goal of making scientific studies more reproducible and findings more replicable.


## What is leading to low levels of reproducibility?

I mentioned earlier that when we talk about issues of reproducibility, we aren’t talking about fraud. So if most of this is now caused by fraud, what is leading to the problem? There are a number of contributing factors, but one of the big issues is a lack of documentation and transparency. Here is an abstract representation of the research lifecycle. 

![research lifecycle](intro_figs/research_lifecycle.png)


How it generally works now, if I’m not in your lab the only part of this process that I can see is the final step; all I see is what is in the published report. And even if I am in your lab, after about 6 months, I probably won’t remember what happened at these different steps, so all I’ll be left with is the published report. Even if it’s our own research, as some point we will forget what happened in these earlier steps and have to resort to using the publish report as a guide. This creates problems for a couple of reasons. Firstly, published reports are often lacking in details, and so it can be very difficult to determine exactly what was done based only on the information in the published report. Second, the published report often doesn’t give us an indication of how the research question, methodology, or analysis strategies may have changed over time. The evolution of these protocols can give us important information for evaluating the conclusions of the research, and so not documenting and being transparent about the process, rather than just the final versions, is problematic. Finally, at the moment there is a large bias against publishing non statistically significant findings. This leads to a large ‘file drawer’ problem, in which many studies don’t get published, making it difficult to accumulate certain types of knowledge. If we better document the process of all studies, not just published ones, this will help us get more accurate information about all the full population of research studies being conducted. 

## Why should you care about increasing reproducibility?

Now, why in particular should we care about low levels of reproducibility? Low levels of reproducibility and replicability are a problem for a number of reasons. One of the ones you’ve probably heard before is that it’s a problem because if findings don’t replicate, that means we may not know as much as we think we know, and if we can’t reproduce the experiments, we can’t even check if the results will replicate, so it makes it difficult to attempt to validate scientific knowledge, slows down the progress of science, and potentially leads to wasted resources and poor decision making based on following up potentially non-replicable lines of research.

However, low levels of reproducibility also have an impact closer to home, specifically, it can make work in your own lab less efficient. If you think how transient labs are, often one graduate student starts something, leaves, and then another graduate student is trying to pick up their project or build an extend a project done by someone else. Or perhaps you submit a paper, and 6 months later an editor asks you for new analyses and you have to go and find your data and analysis again. Both of these scenarios are contingent on knowing where all your stuff is, and a large amount of either transfer of knowledge or remembering of knowledge, which in general we as people don’t do well right now. This means that the current practices also make it hard for us to replicate and build off our own work, which can often lead to wastes of time and lab resources.  

So, learning about and implementing more reproducible practices will help both science as a whole, as well as your own work.

## What will happen in this workshop?

In this workshop, we’ll be talking about ways to increase the documentation and transparency of your workflow, and learning tools that will help you to implement these changes. To do this, we’re all going to be working through an example study in simulated research groups of a PI, graduate student, and research assistant. Collectively, you’ll work on building an open, transparent research project from start to finish in order to learn good project management practices and use of the OSF. At the end of the workshop we’ll also be sharing the projects we’ve built with each other so we can see how well others can understand what we’ve done. 

## Group set-up
So, to start off, lets count off in 3s. If you don’t have a computer with you, say ’skip’ and look on with one of the groups on either side of you. These will be your groups. All the 1s will be the PIs, all the 2s with be graduate student collaborators, and all the 3s will be research assistants. Don’t worry too much about your role, it’s not going to have a huge impact on what you do today, but if you feel uncomfortable in your role and you want to switch with someone else in your group that is fine.

> Activity: Count off in 3s for group creation

Also, as I mentioned we’ll be working with the OSF during this workshop. So, if you don’t already have an OSF account, please go ahead and set-up one. If you go to [visit OSF](https://osf.io) you can either create an account, or sign-in if you already have one. If you are creating an account, an email will be sent to your email to verify your account.

> Activity: Sign-up or login to [visit OSF](https://osf.io)



