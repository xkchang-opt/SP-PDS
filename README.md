# SP-PDS
Code for a separate preconditioned primal-dual splitting algorithm 


Xiaokai Chang. School of Science, Lanzhou University of Technology, Lanzhou, Gansu, P. R. China.  
Email: xkchang@lut.edu.cn


We propose a separable preconditioned primal dual splitting (SP-PDS) method for solving composite monotone inclusion problems. The linear subproblem arising in this method can be approximately solved. 

We prove weak convergence in Hilbert space by reformulating the proposed SP-PDS as a decomposed proximal point algorithm, where the preconditioner is decomposed non-symmetrically. In particular, various efficient preconditioners are introduced in this framework for which only a few inner iterations are needed to solve the subproblem, instead of computing an exact solution or controlling the error. 

The performance of separate preconditioning strategy is verified through preliminary numerical experiment results on the image denoising and LASSO problems.
