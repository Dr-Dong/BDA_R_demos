# Bayesian Data Analysis R Demos

The [BDA_R_demos repository](https://github.com/avehtari/BDA_R_demos) contains some R demos and additional notes for the book [Bayesian Data
Analysis, 3rd ed by Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin (BDA3)](http://www.stat.columbia.edu/~gelman/book/).

Currently there are demos for BDA3 Chapters 2, 3, 4, 5, 6, 10 and 11.
Furthermore there are demos for
[RStan](https://github.com/stan-dev/rstan) and
[RStanARM](https://github.com/stan-dev/rstanarm).

The initial demos were originally written for Matlab by [Aki
Vehtari](http://users.aalto.fi/~ave/) and translated to R by [Markus
Paasiniemi](https://github.com/paasim). Recently more demos have been
added for [RStan and RStanARM](demos_rstan).

The corresponding [Python demos](https://github.com/avehtari/BDA_py_demos)
and the corresponding [Matlab/Octave demos](https://github.com/avehtari/BDA_m_demos).

See also [Model Selection tutorial](https://github.com/avehtari/modelselection_tutorial).

List of demos (not including [rstan and rstanarm demos](demos_rstan))
- [Chapter 2](demos_ch2)
  - [demo2_1: Probability of a girl birth given placenta previa (BDA3 p. 37)](demos_ch2/demo2_1.html)
  - [demo2_2: Illustrate the effect of prior in binomial model](demos_ch2/demo2_2.html)
  - [demo2_3: Illustrate simulation based inference](demos_ch2/demo2_3.html)
  - [demo2_4: Illustrate grid and inverse-cdf sampling](demos_ch2/demo2_4.html)
- [Chapter 3](demos_ch3)
  - [demo3_1_4: Normal model with unknown mean and variance (BDA3 section 3.2 on p. 64)](demos_ch3/demo3_1_4.html)
  - [demo3_5: Estimating the speed of light using normal model BDA3 p. 66](demos_ch3/demo3_5.html)
  - [demo3_6: Binomial regression and grid sampling with bioassay data (BDA3 p. 74-)](demos_ch3/demo3_6.html)
- [Chapter 4](demos_ch4)
  - [demo4_1: Normal approximation for binomial regression model and Bioassay data](demos_ch4/demo4_1.html)
- [Chapter 5](demos_ch5)
  - [demo5_1: Hierarchical model for Rats experiment (BDA3, p. 102)](demos_ch5/demo5_1.html)
  - [demo5_2: Hierarchical model for SAT-example data (BDA3, p. 102)](demos_ch5/demo5_2.html)
- [Chapter 6](demos_ch6)
  - [demo6_1: Posterior predictive checking of normal model for light data](demos_ch6/demo6_1.html)
  - [demo6_2: Posterior predictive checking for independence in binomial trials](demos_ch6/demo6_2.html)
  - [demo6_3: Posterior predictive checking of normal model with poor test statistic](demos_ch6/demo6_3.html)
  - [demo6_4: Marginal posterior predictive checking with PIT test](demos_ch6/demo6_4.html)
- Chapter 7
  - See [model selection tutorial](https://github.com/avehtari/modelselection_tutorial)
- [Chapter 10](demos_ch10)
  - [demo10_1: Rejection sampling](demos_ch10/demo10_1.html)
  - [demo10_2: Importance sampling](demos_ch10/demo10_2.html)
  - [demo10_3: Importance sampling with normal distribution as a proposal for Bioassay model](demos_ch10/demo10_3.html)
- [Chapter 11](demos_ch11)
  - [demo11_1: Gibbs sampling illustration](demos_ch11/demo11_1.html)
  - [demo11_2: Metropolis sampling + convergence illustration](demos_ch11/demo11_2.html)
  - [demo11_3_4: Metropolis sampling + convergence illustration](demos_ch11/demo11_3_4.html)
- [Chapter 12](demos_ch12)
  - [demo12_1: Static Hamiltonian Monte Carlo illustration](demos_ch12/demo12_1.html)
