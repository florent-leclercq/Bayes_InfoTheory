# Bayes_InfoTheory #

This is a repository of Jupyter notebooks used by Florent Leclercq during lectures on Bayesian statistics and Information Theory.
The homepage of the lectures is accessible [here](http://www.florent-leclercq.eu/teaching.php).

### Contents ###
* Ignorance priors (exemplified with the [lighthouse problem](LighthouseProblem.ipynb)) and the [maximum entropy principle](MaximumEntropy.ipynb)
* Gaussian random fields:
  * [Examples and a digression on non-Gaussianity](GRF_and_fNL.ipynb)
  * Bayesian signal processing and reconstruction:  [de-noising](WienerFilter_denoising.ipynb)
  * Bayesian signal processing and reconstruction: [de-blending](WienerFilter_deblending.ipynb)
* [Bayesian decision theory](DecisionTheory.ipynb)
* Markov Chain Monte Carlo:
  * [Monte-Carlo integration, importance sampling, rejection sampling](Sampling_Importance_Rejection.ipynb)
  * [Metropolis-Hastings algorithm & Gelman-Rubin test](MCMC_MH.ipynb) (MCMC)
  * [Slice sampling](MCMC_Slice.ipynb)
  * [Gibbs sampling](MCMC_Gibbs.ipynb)
  * [Hamiltonian sampling](MCMC_Hamiltonian.ipynb) (HMC), and [comparison of 2nd and 4th order integrators for HMC](MCMC_Hamiltonian_4th_order.ipynb)
* Approximate Bayesian Computation:
  * [Likelihood-free rejection sampling](ABC_rejection.ipynb)
  * [Synthetic likelihood (parametric approximation)](ABC_synthetic_likelihood.ipynb)
  * [Discrepancy and effective likelihood (non-parametric approximation)](ABC_discrepancy_effective_likelihood.ipynb)
* Information theory:
  * [The noisy binary symmetric channel](IT_noisy_binary_channel.ipynb)
  * [Supervised Machine Learning basics: Titanic example](Machine_Learning_basics.ipynb)
* Cosmological and physical examples:
  * [Wiener filtering for the Cosmic Microwave Background](WienerFilter_denoising_CMB.ipynb)
  * [Bayesian decision theory for Cosmic Web classification](DecisionTheory.ipynb)
  * Supernova cosmology: [data and simulations](Supernova_data_simulations.ipynb) (preliminary exercise) and [inference with MCMC and HMC](Supernova_MCMC_HMC.ipynb)
  * The 1919 Eclipse: [parameter inference and model comparison](Eclipse1919_MCMC_HMC.ipynb)

### Acknowledgments ###

I thank Benjamin Wandelt for his own lectures, which have inspired a fraction of this material, and the SOC/LOC of the [ICIC Data Analysis workshop 2021](https://www.imperial.ac.uk/astrophysics/centre-for-inference-and-cosmology/seminars-and-events/data-analysis-workshops/) and [STFC Summer School on Data Intensive Science 2021](https://conference.astro.dur.ac.uk/event/3/overview).

### Warranty ###

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
