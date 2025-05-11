# SP-PDS
Code for  separate preconditioned primal-dual splitting algorithm on image denoising and LASSO problems


Xiaokai Chang. School of Science, Lanzhou University of Technology, Lanzhou, Gansu, P. R. China.  xkchang@lut.edu.cn


By incorporating a linear constraint and solving the resulting linear subproblems, a separate preconditioned PDS algorithm is proposed, where the preconditioning strategy is separate from proximal operator evaluation, thus avoiding computation of complex preconditioned proximal op- erators. Only a few inner iterations are required to approximate the solutions of linear subproblems or the closed-form solution can be used for the matrix inversion problem without error control. Furthermore, the proposed preconditioning strategy is extended to alternating direction method of multipliers for solving more general linear constraint optimization.

By different measures under inclusion and optimization frameworks, global iterative convergence and ergodic convergence rate results are established under any positive constant step size, so the proposed algorithm is step-free. 

Finally, the performance of PDS with separate preconditioning strategy is verified through preliminary numerical experiments.
