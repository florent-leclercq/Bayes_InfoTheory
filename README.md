# Bayes_InfoTheory #

This is a repository of Jupyter notebooks used by Florent Leclercq during lectures on Bayesian statistics and Information Theory.
The homepage of the lectures is accessible [here](http://www.florent-leclercq.eu/teaching.php).

### Contents ###
* Ignorance priors (exemplified with the [lighthouse problem](LighthouseProblem.ipynb)) and the [maximum entropy principle](MaximumEntropy.ipynb)
* Gaussian random fields:
  * [Examples and a digression on non-Gaussianity](GRF_and_fNL.ipynb)
  * Bayesian signal processing and reconstruction: de-noising ([example](WienerFilter_denoising.ipynb), [example with the CMB](WienerFilter_denoising_CMB.ipynb))
  * Bayesian signal processing and reconstruction: [de-blending](WienerFilter_deblending.ipynb)
* [Bayesian decision theory](DecisionTheory.ipynb)
* Markov Chain Monte Carlo:
  * [Monte-Carlo integration, importance sampling, rejection sampling](Sampling_Importance_Rejection.ipynb)
  * [Metropolis-Hastings algorithm & Gelman-Rubin test](MCMC_MH.ipynb)
  * [Slice sampling](MCMC_Slice.ipynb)
  * [Gibbs sampling](MCMC_Gibbs.ipynb)
  * [Hamiltonian sampling](MCMC_Hamiltonian.ipynb)
* Approximate Bayesian Computation:
  * [Likelihood-free rejection sampling](ABC_rejection.ipynb)
  * [Synthetic likelihood (parametric approximation)](ABC_synthetic_likelihood.ipynb)
  * [Discrepancy and effective likelihood (non-parametric approximation)](ABC_discrepancy_effective_likelihood.ipynb)
* Information theory:
  * [The noisy binary symmetric channel](IT_noisy_binary_channel.ipynb)
  * [Supervised Machine Learning basics: Titanic example](Machine_Learning_basics.ipynb)

### Acknowledgments ###
FL thanks Benjamin Wandelt for his own lectures, which have inspired a fraction of this material. 

### Warranty ###

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
