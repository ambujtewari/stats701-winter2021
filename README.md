## Welcome to STATS 701 WI 2021

This is a special topics course on the Theory of Reinforcement Learning (RL). We will focus on the design and analysis of RL algorithms using tools from regret analysis of online algorithms, concentration inequalities, and stochastic approximation. The "core" of this course will be based on online RL in a finite state-action (often called the "tabular" setting) Markov Decision Process (MDP) and will be taught in traditional lecture style (fully remote due to COVID-19). The "advanced" part of this course will choose topics based on audience interest and will be more discussion based. Students will volunteer to read a paper (or a small group of related papers) and lead its discussion in the class. Topics for the advanced part could include:

- RL with function approximation (from simple cases like linear functions to more difficult cases like deep RL)
- continuous state and action spaces (e.g., LQR systems \[linear systems with quadratic costs\])
- offline and off-policy evaluation
- multi-task and transfer learning in RL
- topics related to the above (e.g., lifelong RL, meta RL)
- hierarchical RL
- multi-agent RL

We will use the following resources:
- for the core part: [course notes by Prof. Vidyasagar](https://www.iith.ac.in/~m_vidyasagar/RL/Gen/) and [the boot camp](https://simons.berkeley.edu/workshops/schedule/14378) from the Simons Institute Fall 2020 program on the Theory of Reinforcement Learning
- for the advanced part: the three workshops from the Simons Theory of RL program ([deep RL](https://simons.berkeley.edu/workshops/schedule/14238), [online RL](https://simons.berkeley.edu/workshops/schedule/14239), [RL using batch/simulation data](https://simons.berkeley.edu/workshops/schedule/14240))  
- for more resources, look [here](resources.md)

The course is aimed at advanced graduate students in statistics, computer science, control theory, operations research, and other related disciplines that study sequential decision making under uncertainty. Prior exposure to RL (or at least MDPs) is strongly recommended. This course has a theoretical/mathematical flavor and therefore mathematical maturity is expected.

## Instructor Information

**Name**: Ambuj Tewari  
**Zoom Office Hours**: By appointment  
**Email**: tewaria@umich.edu  

## Grading

There will be no graded homeworks or exams. Grades will be determined on the basis of class presentations and a final project.

## Schedule 

_Caveat Lector_: The material below is provided with the hope that it might be useful in learning the theory of RL. Please note that the content is rough and unplished in many places. It has not been subjected to the scrutiny reserved for scholarly publications. Please watch out for errors and inconsistencies!

- V = Prof. Vidyasagar's course notes (available to UM students via the Canvas website for this course)
- SB = Richard Sutton and Andrew Barto, Reinforcement Learning: An Introduction (2nd edition)

Lecture No. | Date | Topic | Readings | Media. 
--- | --- | --- | --- | ---
01 | Jan 19 | Introduction | V, Chapter 1 (Introduction) <br/> SB, Chapter 1 (Introduction) <br/> SB, Section 16.2 (Samuel's Checkers Player) <br/> SB, Section 16.6 (Mastering the Game of Go) | [slides](slides/Intro.pdf) <br/> [zoom recording](https://www.dropbox.com/s/s5o5up2y7a57p4n/zoom_0.mp4?dl=0)
&nbsp;| &nbsp; | **Tabular Methods** | &nbsp; |
02 | Jan 21 | Markov Processes | V, Section 8.2 (Markov processes) |
03 | Jan 26 | Markov Reward Processes | V, Section 8.3 (Contraction Mapping Theorem) <br/> V, Section 2.1 (Markov Reward Processes) |
04 | Jan 28 | MRPs continued <br/> Markov Decision Processes | V, Section 2.2 (Markov Decision Processes) |
05 | Feb 02 | MDPs continued <br/> Monte Carlo Methods | -- |
06 | Feb 04 | Temporal Difference Methods | -- |
&nbsp;| &nbsp; | **Online Learning and Bandits** | &nbsp; |
07 | Feb 09 | Online Convex Optimization | -- |
08 | Feb 11 | Experts Problem | -- |
09 | Feb 16 | Stochastic and Adversarial Multi-Armed Bandits | -- |
10  | Feb 18 | Pure Exploration and Stochastic Linear Bandits | -- |
&nbsp;| &nbsp; | **Online Learning in MDPs** | &nbsp; |
11 | Feb 23 | Optimism Based Algorithms | -- |
12 | Feb 25 | Posterior/Thompson Sampling | -- |
13 | Mar 02 | Adversarial MDPs <br/> <span style="color:red">Proposals due</span> | -- |
14 | Mar 04 | -- | -- |
15 | Mar 09 | -- | -- |
16 | Mar 11 | -- | -- |
17 | Mar 16 | -- | -- |
18 | Mar 18 | -- | -- |
&nbsp;| Mar 23 | Well-being break | &nbsp; |
19 | Mar 25 | -- | -- |
20 | Mar 30 | -- | -- |
21 | Apr 01 | -- | -- |
22 | Apr 06 | -- | -- |
23 | Apr 08 | -- | -- |
24 | Apr 13 | -- | -- |
25 | Apr 15 | -- | -- |
26 | Apr 20 | -- | -- |
&nbsp;| Apr 27 | <span style="color:red">Reports due</span> | &nbsp; |
