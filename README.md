# mc_asymptotic_analysis

This repository contains materials for the course “Cadenas de Markov & Aplicaciones.” It centers on the asymptotic analysis of different methods for finding the stationary distribution of a particular class of Markov chains, with emphasis on comparing their efficiency.

Our Markov Chain nxn transition matrix $P$ looks like this:

$$\begin{bmatrix}
q & p & 0 & 0 & \dots & 0 \\
q & 0 & p & 0 & \dots & 0 \\
0 & q & 0 & p & \dots & 0 \\
0 & 0 & q & 0 & \ddots & 0 \\
\vdots & \vdots & \vdots & \ddots & \ddots & p \\
0 & 0 & 0 & 0 & q & p
\end{bmatrix}$$

In this case we would have a discrete-time, finite-state BDP; or also a Nearest-Neighbor Random Walk (we will also see what happens when the walk is biased ($p\neq q$).

Made by: tuli-pen, Fran7373, jnardosp
