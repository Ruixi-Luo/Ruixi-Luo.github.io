---
title: "Simple $$k$$-Crashing Plan with a Good Approximation Ratio"
collection: publications
category: conferences
permalink: /publication/k-crashing-AAMAS
excerpt: 'A project is considered as an activity-on-edge network (AOE network, which is a directed acyclic graph) $$N$$, where each activity / job of the project is an edge. Some jobs must be finished before others can be started, as described by the topology structure of $$N$$.
It is known that job $$j_i$$ in normal speed would take $$b_i$$ days to be finished after it is started, and hence the (normal) duration of the project $$N$$, denoted by $$d(N)$$, is determined, which equals the length of the critical path (namely, the longest path) of $$N$$.
To speed up the project, the manager can crash a few jobs (namely, reduce the length of the corresponding edges) by investing extra resources into that job. However, the time for completing $$j_i$$ has a lower bound due to technological limits - it requires at least $a_i$ days to be completed. Following the convention, assume that the duration of a job has a linear relation with the extra resources put into this job; equivalently, there is a parameter $$c_i$$ (slope), so that shortening $$j_i$$ by $$d~(0\leq d \leq b_i-a_i)$$ days costs $$c_i\cdot d$$ resources. 
Given project $$N$$ and an integer $$k \geq 1$$, the \emph{$$k$$-crashing problem} asks the minimum cost to speed up the project by $$k$$ days. 
In this paper, we present a simple solution with the approximation ratio $$\frac{1}{1}+\ldots+\frac{1}{k}$$. For simplicity, we focus on the linear case throughout the paper, but our proofs are still correct for the convex case, where shortening an edge becomes more difficult after a previous shortening.'
date: 2024-5-06
venue: '23rd International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2024)'
paperurl: 'https://Ruixi-Luo.github.io/files/k-crashing-AAMAS.pdf'
bibtexurl: 'https://Ruixi-Luo.github.io/files/k-crashing-AAMAS.bib'
citation: '<strong>Luo, R.</strong>, Jin, K., & Ye, Z. (2024, May). Simple k-crashing Plan with a Good Approximation Ratio. In Proceedings of the 23rd International Conference on Autonomous Agents and Multiagent Systems (pp. 2366-2368).'
---
