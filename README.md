# Causal Inference Reading Group (Spring 2020)

## Purpose

There is a lot going on in the causal inference literature! The goal of the reading group is to help each other keep up with the literature and best practices. It will be practitioner-oriented. Ideally, each session will end with people learning something that they can realistically apply to a project.

I am totally open to this becoming more of a "methods" workshop that encompasses more topics as time goes on. For now, I hope grounding it in causal inference to start with will help us figure out the nitty-gritty (e.g. how to structure discussions). 

## Structure

[I have no idea what I'm doing](https://i.imgur.com/m0w03xj.jpg) so happy for suggestions and to adapt as we go along. 

- Once a month
- 1 person leads discussion
- Focus on one paper (or one set of papers around a topic)
- Guide for discussion: 
    1. What is the core methodological issue?
    1. 1-2 examples to illustrate
    1. What are possible solutions?
    1. How to implement solutions **in code**?
    1. Brainstorm ideas for how we can use this in our own research

About the "code" bulletpoint, the goal is NOT that people should be coding up fancy estimators on their own. Rather, the hope is that the rest of the reading group will have an answer to the question of "How can I implement this in Stata/R/Python/~~Gretl~~ and how painful will it be?". In an ideal world, the discussant would have attempted to implement the method and can talk about that process (e.g. unexpected problems that came up). At a minimum, they should discuss the steps needed to go from concept to actual usage in a project.  

## Spring Schedule

[DAG Chapter in *Causal Inference: The Mixtape by Scott Cunningham*](http://scunning.com/cunningham_mixtape.pdf) - Discussant: Wei Yang, 29 Jan 2020

[Consistency without Inference: Instrumental Variables in Practical Application](http://personal.lse.ac.uk/YoungA/ConsistencyWithoutInference.pdf) - Discussant: **TBD**

[Sampling-based vs. Design-based Uncertainty in Regression Analysis](https://arxiv.org/abs/1706.01778) - Discussant: **TBD**

[How Much Can We Generalize from Impact Evaluations? (Eva Vivalt)](http://evavivalt.com/wp-content/uploads/How-Much-Can-We-Generalize.pdf) - Discussant: **TBD**

[Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects](http://economics.mit.edu/files/17847) - Discussant: **TBD**

[Difference-in-differences with variation in treatment timing (Andrew Goodman-Bacon)](https://cdn.vanderbilt.edu/vu-my/wp-content/uploads/sites/2318/2019/07/29170757/ddtiming_7_29_2019.pdf) + [SO YOU’VE BEEN TOLD TO DO MY DIFFERENCE-IN-DIFFERENCES THING: A GUIDE (Andrew Goodman-Bacon)](https://cdn.vanderbilt.edu/vu-my/wp-content/uploads/sites/2318/2019/10/09023516/so_youve_been_told_dd_10_9_2019.pdf) - Discussant: **TBD** 

[Adaptive Experimental Design: Prospects and Applications in Political Science](https://alexandercoppock.com/papers/OCG_adaptive.pdf) - Discussant: **TBD**

## Topics

## Difference-in-differences

[Difference-in-differences with variation in treatment timing (Andrew Goodman-Bacon)](https://cdn.vanderbilt.edu/vu-my/wp-content/uploads/sites/2318/2019/07/29170757/ddtiming_7_29_2019.pdf)

[SO YOU’VE BEEN TOLD TO DO MY DIFFERENCE-IN-DIFFERENCES THING: A GUIDE (Andrew Goodman-Bacon)](https://cdn.vanderbilt.edu/vu-my/wp-content/uploads/sites/2318/2019/10/09023516/so_youve_been_told_dd_10_9_2019.pdf)

[Pre-test with Caution: Event-study Estimates After Testing for Parallel Trends](https://scholar.harvard.edu/files/jroth/files/roth_pretrends_20190730.pdf)

[Difference-in-Differences with Multiple Time Periods and an Application on the Minimum Wage and Employment (Callaway and Sant'Anna)](https://arxiv.org/abs/1803.09015)

[Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects (Abraham and Sun)](http://economics.mit.edu/files/14964)

[Online Appendix C discussing event-by-event analysis (which appendix may differ by which version of paper you find) of *The Effect of Minimum Wages on Low-Wage Jobs* (Cengiz, Dube, Lindner, and Zipperer)](https://www.nber.org/papers/w25434)

[Pre-test with Caution: Event-study Estimates After Testing for Parallel Trends](https://scholar.harvard.edu/files/jroth/files/roth_pretrends_20190730.pdf)

## Instrumental Variables

[Consistency without Inference: Instrumental Variables in Practical Application](http://personal.lse.ac.uk/YoungA/ConsistencyWithoutInference.pdf)

## Regression Discontinuity

[A Practical Introduction to Regression Discontinuity Designs: Foundations](https://cattaneo.princeton.edu/books/Cattaneo-Idrobo-Titiunik_2019_CUP-Vol1.pdf)

[A Practical Introduction to Regression Discontinuity Designs: Volume II](https://cattaneo.princeton.edu/books/Cattaneo-Idrobo-Titiunik_2018_CUP-Vol2.pdf)

[The Regression Discontinuity Design](https://cattaneo.princeton.edu/papers/Cattaneo-Titiunik-VazquezBare_2019_Sage.pdf)

## DAGs (Directed Acyclical Graphs)

[Chapter in *Causal Inference: The Mixtape by Scott Cunningham*](http://scunning.com/cunningham_mixtape.pdf)

## Synthetic controls

[Matrix Completion Methods for Causal Panel Data Models](https://arxiv.org/abs/1710.10251)

[Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects](http://economics.mit.edu/files/17847)

## Bayesian statistics

[Bayesian Causal Inference in Political Science (Mike DeCrescenzo)](https://github.com/mikedecr/causal-bayes)

[Bayesian Nonparametric Modeling for Causal Inference (Jennifer Hill on Bayesian Additive Regression Trees)](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2010.08162)

[City Limits to Partisan Polarization in the American Public](https://williammarble.co/docs/CityLimits-July2019.pdf)

## Experimental design

[Adaptive Experimental Design: Prospects and Applications in Political Science](https://alexandercoppock.com/papers/OCG_adaptive.pdf)

[Adaptive treatment assignment in experiments for policy choice (Kasy and Sautmann)](https://maxkasy.github.io/home/files/papers/adaptiveexperimentspolicy.pdf)

[Why Experimenters Might Not Always Want to Randomize, and What They Could Do Instead (Kasy)](https://maxkasy.github.io/home/files/papers/experimentaldesign.pdf)

[Conjoint Survey Experiments](https://cpb-us-w2.wpmucdn.com/web.sas.upenn.edu/dist/f/49/files/2019/09/handbook-draft-07-09202019-1.pdf)

[Analyzing Two-Stage Experiments in the Presence of Interference](https://www.tandfonline.com/doi/abs/10.1080/01621459.2017.1323641)

[Randomization tests of causal effects under interference](https://academic.oup.com/biomet/article-abstract/106/2/487/5306899)

## Inference

[Sampling-based vs. Design-based Uncertainty in Regression Analysis](https://arxiv.org/abs/1706.01778)

[Multiple Hypothesis Testing in Experimental Economics](https://rd.springer.com/article/10.1007/s10683-018-09597-5)

## Visualization

[Visualize as You Randomize: Design-Based Statistical Graphs for Randomized Experiments](https://alexandercoppock.com/papers/Coppock_VAYR.pdf)

## Matching and Propensity Score methods

## Heterogeneous Treatment Effects and External Validity

[LOCAL INSTRUMENTS, GLOBAL EXTRAPOLATION:
EXTERNAL VALIDITY OF THE LABOR SUPPLY-FERTILITY LOCAL AVERAGE TREATMENT EFFECT (James Bisbee, Rajeev Dehejia, Cristian Pop-Eleches, Cyrus Samii)](https://www.nber.org/papers/w21663.pdf)

[From Local to Global: External Validity in a Fertility Natural Experiment (Rajeev Dehejia, Cristian Pop-Eleches, Cyrus Samii)](https://arxiv.org/abs/1906.08096)

[A Nonparametric Bayesian Analysis of Heterogenous Treatment Effects in Digital Experimentation](https://amstat.tandfonline.com/doi/abs/10.1080/07350015.2016.1172013#.XZ95ri2ZMUE)

[Heterogeneous Treatment Effects in Impact Evaluation (Eva Vivalt)](http://evavivalt.com/wp-content/uploads/2015/05/aer20151015.pdf)

[How Much Can We Generalize from Impact Evaluations? (Eva Vivalt)](http://evavivalt.com/wp-content/uploads/How-Much-Can-We-Generalize.pdf)

[Understanding the Average Impact of Microcredit Expansions: A Bayesian Hierarchical Analysis of Seven Randomized Experiments(Rachael Meager)](http://eprints.lse.ac.uk/88190/1/app.20170299.pdf); [Voxdev article for more general audience](https://voxdev.org/topic/methods-measurement/understanding-average-effect-microcredit)

[Aggregating Distributional Treatment Effects: A Bayesian Hierarchical Analysis of the Microcredit Literature](https://mfr.osf.io/render?url=https://osf.io/bq6pn/?action=download%26mode=render)


## Partial Identification
