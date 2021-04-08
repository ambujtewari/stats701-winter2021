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

_Caveat Lector_: The material below is provided with the hope that it might be useful in learning the theory of RL. Please note that the content is rough and unpolished in many places. It has not been subjected to the scrutiny reserved for scholarly publications. Please watch out for errors and inconsistencies!

- V = Prof. Vidyasagar's course notes (available to UM students via the Canvas website for this course)
- SB = Richard Sutton and Andrew Barto, [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book.html) (2nd edition)
- P = Martin L. Puterman, Markov Decision Processes: Discrete Stochastic Dynamic Programming
- H = Elad Hazan, [Introduction to Online Convex Optimization](https://arxiv.org/pdf/1909.05207.pdf)
- LS = Tor Lattimore and Csaba Szepesvari, [Bandit Algorithms](https://tor-lattimore.com/downloads/book/book.pdf)

Lecture No. | Date | Topic | Readings | Media
--- | --- | --- | --- | ---
01 | Jan 19 | Introduction | V, Chapter 1 (Introduction) <br/> SB, Chapter 1 (Introduction) <br/> SB, Section 16.2 (Samuel's Checkers Player) <br/> SB, Section 16.6 (Mastering the Game of Go) | [slides](slides/Intro.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/s5o5up2y7a57p4n/zoom_0.mp4?dl=0)
&nbsp;| &nbsp; | **Tabular Methods** | &nbsp; |
02 | Jan 21 | Markov Processes | V, Section 8.2 (Markov processes) | [slides](slides/MRP.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/yx123soh439120x/zoom_0.mp4?dl=0)
03 | Jan 26 | Markov Reward Processes | V, Section 8.4 (Contraction Mapping Theorem) <br/> V, Section 2.1 (Markov Reward Processes) | [slides](slides/MRP2.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/scxb2behhqkrkg3/zoom_0.mp4?dl=0)
04 | Jan 28 | MRPs Continued <br/> Markov Decision Processes | V, Section 2.2 (Markov Decision Processes) <br/> SB, Chapter 3 (Finite Markov Decision Processes)| [slides](slides/MDP.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/nn0cqpclsr09nz1/zoom_0.mp4?dl=0)
05 | Feb 02 | MDPs Continued | SB, Chapter 4 (Dynamic Programming) | [slides](slides/MDP2.pdf)<br/><br/> [zoom recording](https://www.dropbox.com/s/179yab2qa465y4x/zoom_0.mp4?dl=0)
06 | Feb 04 | LP Approach to Solving MDPs <br/> MLE of Markov Processes <br/> Hoeffding's Inequality | P, Section 6.9 (Linear Programming) <br/> V, Section 8.3 (MLE of Markov Processes) | [slides](slides/MC_methods.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/a0ubuosk81931ct/zoom_0.mp4?dl=0)
07 | Feb 09 | Monte Carlo Methods | V, Section 4.1 (Monte-Carlo Methods) <br/> SB, Chapter 5 (Monte Carlo Methods) | [slides](slides/MC_methods2.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/tg84g76ti7jfm6y/zoom_0.mp4?dl=0)
08 | Feb 11 | Temporal Difference Methods | V, Section 4.2 (Temporal Difference Methods) <br/> SB, Chapter 6 (Temporal-Difference Learning) | [slides](slides/TD-methods.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/6idxa97b3eevf92/zoom_0.mp4?dl=0)
09 | Feb 16 | Project Discussion | &nbsp; |
&nbsp;| &nbsp; | **Online Learning and Bandits** | &nbsp; |
10  | Feb 18 | Online Convex Optimization (OCO)  | H, Chapter 1 (Introduction) <br/> H, Chapter 2 (First order algorithms for OCO) | [slides](slides/full-info_slides.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/cdu0dfum6xejott/zoom_0.mp4?dl=0)
11 | Feb 23 | Experts Problem <br/> Follow the Regularized Leader <br/> Mirror Descent | H, Chapter 5 (Regularization) | [slides](slides/full-info_slides2.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/5esvjth771xt6dc/zoom_0.mp4?dl=0)
12 | Feb 25 | Adversarial Multi-Armed Bandits | LS, Chapter 11 (The Exp3 Algorithm) | [slides](slides/bandits_slides.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/azu5pluwg54sh56/zoom_0.mp4?dl=0)
-- | Mar 05 | <span style="color:red">Proposals due</span> | Note: Mar 2nd, Mar 4th lectures were cancelled |
13 | Mar 09 | Stochastic Multi-Armed Bandits | LS, Chapter 4 (Stochastic Bandits) <br/> LS, Chapter 6 (The Explore-Then-Commit Algorithm) <br/> LS,  Chapter 7 (The Upper Confidence Bound Algorithm) <br/> LS, Chapter 36 (Thompson Sampling) | [slides](slides/bandits_slides2.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/duamck0ep8s9sua/zoom_0.mp4?dl=0)
&nbsp;| &nbsp; | **Online Learning in MDPs** | &nbsp; |
14 | Mar 11 | Optimism Based Algorithms | [UCRL2 paper](https://www.jmlr.org/papers/volume11/jaksch10a/jaksch10a.pdf) | [slides](slides/UCRL.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/btqs0xl1w7tq0aa/zoom_0.mp4?dl=0)
15 | Mar 16 | Posterior/Thompson Sampling | [PSRL paper](https://arxiv.org/pdf/1306.0940.pdf) | [slides](slides/TS.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/7ge5nuaovdlk07q/zoom_0.mp4?dl=0)
16 | Mar 18 | Adversarial MDPs | [MDP Experts paper](https://papers.nips.cc/paper/2004/file/421b3ac5c24ee992edd6087611c60dbb-Paper.pdf) ([Journal version](https://www.jstor.org/stable/40538442)) <br/><br/> [O-REPS paper](https://proceedings.neurips.cc/paper/2013/file/68053af2923e00204c3ca7c6a3150cf7-Paper.pdf) | [slides](slides/advMDPs.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/6qrfbpw8mhxjiue/zoom_0.mp4?dl=0)
&nbsp;| Mar 23 | <span style="color:red">Well-being break</span> | &nbsp; |
&nbsp;| Mar 25 | <span style="color:red">Well-being break</span> | &nbsp; |

### Student Presentations

Date | Group | Topic | Media
--- | --- | --- | ---
Mar 30 | Dhar-Weitze | Reinforcement Learning in Enormous Action Spaces | [slides](student%20presentation%20slides/Dhar-Weitze.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/hru07l0hwxw0lhl/zoom_0.mp4?dl=0)
Mar 30 | Gupta-Li-Li | Game Theoretical Foundations for Multi-agent Reinforcement Learning | [slides](student%20presentation%20slides/Gupta-Li-Li.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/smnydmbc5t1lqk9/zoom_1.mp4?dl=0)
Apr 01 | Liu-Qiao-Sun |  A deep reinforcement learning based long-term recommender system | [slides](student%20presentation%20slides/Liu-Qiao-Sun.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/f5qcmph3txys9ok/zoom_0.mp4?dl=0)
Apr 01 | DiGiovanni-Zell | Self-Play Compatibility in Multi-Agent Learning | [slides](student%20presentation%20slides/Zell-DiGiovanni.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/hc3t2euluujqg5c/zoom_1.mp4?dl=0)
Apr 06 | Li-Xu | Overview of Thompson sampling in RL and BCI applications | [slides](student%20presentation%20slides/Li-Xu.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/ntflh5q29mywo3e/zoom_0.mp4?dl=0)
Apr 06 | Jang-Moug | Comparison of Safe Reinforcement Learning Algorithms in Safety Gym | [slides](student%20presentation%20slides/Jang-Moug.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/mlr73edut1pub79/zoom_1.mp4?dl=0)
Apr 08 | Park-Yu | Real-time Update in Robot Imitation Learning | [slides](student%20presentation%20slides/Park-Yu.pdf) <br/><br/> zoom recording to be added
Apr 08 | Otero-Leon | Patient panel prioritization with finite resources | [slides](student%20presentation%20slides/Otero-Leon.pdf) <br/><br/> [zoom recording](https://www.dropbox.com/s/8x44hicy8zjzpk2/zoom_1.mp4?dl=0)
Apr 13 | Wang-Zhong | -- |
Apr 13 | Chandrasekaran-De | -- |
Apr 15 | Zhalechian | -- |
Apr 15 | Bull-Li | -- |
Apr 20 | Chakraborty-Roy | -- |
Apr 20 | Li-Shang | -- |
Apr 27 | <span style="color:red">Reports due</span> | &nbsp; |
