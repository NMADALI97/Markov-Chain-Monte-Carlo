##  Markov Chain Monte Carlo    

I implement from scratch, the Metropolis-Hastings algorithm in Python to find parameter distributions for a dummy data example and then of a real world problem.    

I will only use numpy to implement the algorithm, and matplotlib to present the results. Scipy can be used to compute the density functions when needed, but I will also show how to implement them using numpy.

## The Markov-chain Monte Carlo Interactive Gallery

[![HitCount](http://hits.dwyl.io/chi-feng/mcmc-demo.svg)](http://hits.dwyl.io/chi-feng/mcmc-demo)

*Example*: Hamiltonian Monte Carlo

<a href="https://chi-feng.github.io/mcmc-demo/app.html?algorithm=HamiltonianMC&target=banana" target="_blank"><img src="https://raw.githubusercontent.com/chi-feng/mcmc-demo/master/docs/hmc.gif" width="400" /></a>

Click on an algorithm below to view an interactive demo where you can change algorithm parameters on-the-fly:

### Standard MCMC methods 

*   [Random Walk Metropolis Hastings](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=RandomWalkMH&target=banana)
*   [Adaptive Metropolis Hastings](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=AdaptiveMH&target=banana) [[1]](#ref-1)
*   [Hamiltonian Monte Carlo](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=HamiltonianMC&target=banana) [[2]](#ref-2)
*   [No-U-Turn Sampler](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=NaiveNUTS&target=banana) [[2]](#ref-2)
*   [Metropolis-adjusted Langevin Algorithm (MALA)](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=MALA&target=banana) [[3]](#ref-3)
*   [Hessian-Hamiltonian Monte Carlo (H2MC)](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=H2MC&target=banana) [[4]](#ref-4)
*   [Gibbs Sampling](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=GibbsSampling&target=banana)

### Non-Markovian iterative sampling methods
*   [Stein Variational Gradient Descent (SVGD)](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=SVGD&target=banana&delay=0) [[5]](#ref-5)
*   [Nested Sampling with RadFriends (RadFriends-NS)](https://chi-feng.github.io/mcmc-demo/app.html?algorithm=RadFriends-NS&target=banana) [[6]](#ref-6)

### References

[1] H. Haario, E. Saksman, and J. Tamminen, [An adaptive Metropolis algorithm](http://projecteuclid.org/euclid.bj/1080222083) (2001)

[2] M. D. Hoffman, A. Gelman, [The No-U-Turn Sampler: Adaptively Setting Path Lengths in Hamiltonian Monte Carlo](http://arxiv.org/abs/1111.4246) (2011)

[3] G. O. Roberts, R. L. Tweedie, [Exponential Convergence of Langevin Distributions and Their Discrete Approximations](http://www2.stat.duke.edu/~scs/Courses/Stat376/Papers/Langevin/RobertsTweedieBernoulli1996.pdf) (1996)

[4] Li, Tzu-Mao, et al. [Anisotropic Gaussian mutations for metropolis light transport through Hessian-Hamiltonian dynamics](https://people.csail.mit.edu/tzumao/h2mc/) ACM Transactions on Graphics 34.6 (2015): 209.

[5] Q. Liu, et al. [Stein Variational Gradient Descent: A General Purpose Bayesian Inference Algorithm](http://www.cs.dartmouth.edu/~dartml/project.html?p=vgd) Advances in Neural Information Processing Systems. 2016.

[6] J. Buchner [A statistical test for Nested Sampling algorithms](https://arxiv.org/abs/1407.5459) Statistics and Computing. 2014.
