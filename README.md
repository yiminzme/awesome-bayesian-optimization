<br>

# **Awesome Bayesian Optimization** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


# Table of Contents
* **[Table of Contents](#table-of-contents)**
* **[Tutorials](#tutorials)**
  * **[Talks / Lectures](#talks--lectures)**
* **[Papers](#papers)**
  * **[Sorted by acquisition functions](#sorted-by-acquisition-functions)**
    * **[Expected Improvement](#expected-improvement)**
    * **[Entropy Search](#entropy-search)**
    * **[Knowledge Gradient](#knowledge-gradient)**
    * **[Upper Confidence Bound](#upper-confidence-bound)**
    * **[Probability of Improvement](#probability-of-improvement)**
  * **[Sorted by settings](#sorted-by-settings)**
    * **[multi-objective](#multi-objective)**
    * **[parallel](#parallel)**
    * **[constraints](#constraints)**
    * **[multi-fidelity](#multi-fidelity)**
    * **[noisy evaluations](#noisy-evaluations)**
* **[Software](#software)**
* **[Acknowledgement](#acknowledgement)**


























# Tutorials
[Back to Top](#table-of-contents)
  * 2018 | A Tutorial on Bayesian Optimization
  * 2010 | A tutorial on Bayesian optimization of expensive cost functions, with application to active user modeling and hierarchical reinforcement learning
  * 2015 | Taking the human out of the loop: A review of Bayesian optimization
  * 2012 | Practical bayesian optimization of machine learning algorithms
### Talks / Lectures
  * Bayesian Methods for Machine Learning by Coursera | [course page](https://www.coursera.org/learn/bayesian-methods-in-machine-learning)


























# Papers

## Sorted by acquisition functions
[Back to Top](#table-of-contents)

* ### Expected Improvement
  * 2019 | Multi-objective Bayesian global optimization using expected hypervolume improvement gradient | EHVI ext
  * 2019 | Multi-objective Bayesian optimisation with preferences over objectives | multi-obj EHI-BO with preference
  * 2018 | Expected Hypervolume Improvement with Constraints | constrained EHI-BO
  * 2017 | A bayesian approach to constrained single- and multi-objective optimization | constrainted multi-obj EHI-BO BMOO
  * 2016 | Pareto frontier learning with expensive correlated objectives | multi-obj EHI-BO with correlated objs
  * 2016 | Multiobjective optimization of expensive-to-evaluate deterministic computer simulator models | multi-obj EMI
  * 2010 | Multiobjective optimization of expensive black-box functions via expected maximin improvement | multi-obj EMI
  * 2015 | Faster exact algorithms for computing expected hypervolume improvement | faster EHI-BO
  * 2011 | Hypervolume-based expected improvement: Monotonicity properties and exact computation | EHVI
  * 2008 | The computation of the expected improvement in dominated hypervolume of Pareto front approximations | EHVI
  * 2019 | Constrained Bayesian optimization with noisy experiments | constrained EI
  * 2015 | Scalable bayesian optimization using deep neural networks | constrained EI
  * 2014 | Bayesian optimization with unknown constraints | constrained EI
  * 2014 | Bayesian Optimization with Inequality Constraints | constrained EI
  * 2006 | ParEGO: a hybrid algorithm with on-line landscape approximation for expensive multiobjective optimization problems | multi-obj EI-BO ParEGO
  * 1998 | Efficient global optimization of expensive black-box functions | EI
* ### Entropy Search
  * 2020 | Multi-fidelity Bayesian Optimization with Max-value Entropy Search and its Parallelization | parallel MES
  * 2020 | Multi-objective Bayesian Optimization using Pareto-frontier Entropy | multi-obj ES-BO PFES
  * 2019 | Constrained Bayesian Optimization with Max-Value Entropy Search | constrained MES
  * 2020 | Noisy-Input Entropy Search for Efficient Robust Bayesian Optimization | noisy robust MES NESEP
  * 2019 | Max-value Entropy Search for Multi-Objective Bayesian Optimization | multi-obj MES-BO MESMO
  * 2017 | Max-value entropy search for efficient Bayesian optimization | MES
  * 2016 | Predictive entropy search for multi-objective bayesian optimization with constraints | constrained multi-obj PES-BO PESMOC
  * 2016 | Predictive entropy search for multi-objective bayesian optimization | multi-obj PES-BO PESMO
  * 2015 | Predictive entropy search for bayesian optimization with unknown constraints | constrained BO
  * 2014 | Predictive entropy search for efficient global optimization of black-box functions | PES
  * 2012 | Entropy search for information-efficient global optimization | ES
  * 2009 | An informational approach to the global optimization of expensive-to-evaluate functions | ES-like
* ### Knowledge Gradient
  * 2020 | Bayesian multi-objective optimization with noisy evaluations using the Knowledge Gradient | multi-obj KG with noise
  * 2009 | The knowledge-gradient policy for correlated normal beliefs | KG
  * 2016 | The parallel knowledge gradient method for batch bayesian optimization | q-KG
  * 2017 | Multi-information source optimization | MF-KG misoKG
* ### Upper Confidence Bound
  * 2009 | Gaussian process optimization in the bandit setting: No regret and experimental design | GP-UCB
* ### Probability of Improvement
  * 1964 | A new method of locating the maximum point of an arbitrary multipeak curve in the presence of noise | PI probability of improvement























































## Sorted by settings
[Back to Top](#table-of-contents)

* ### multi-objective
  * 2020 | Multi-objective Bayesian Optimization using Pareto-frontier Entropy | multi-obj ES-BO PFES
  * 2019 | Max-value Entropy Search for Multi-Objective Bayesian Optimization | multi-obj MES-BO MESMO
  * 2016 | Predictive entropy search for multi-objective bayesian optimization with constraints | constrained multi-obj PES-BO PESMOC
  * 2016 | Predictive entropy search for multi-objective bayesian optimization | multi-obj PES-BO PESMO
  * 2020 | Differentiable Expected Hypervolume Improvement for Parallel Multi-Objective Bayesian Optimization | parallel EHVI
  * 2019 | Multi-objective Bayesian global optimization using expected hypervolume improvement gradient | EHVI ext.
  * 2019 | Multi-objective Bayesian optimisation with preferences over objectives | multi-obj EHI-BO with preference Journal of Global 2017 | A bayesian approach to constrained single- and multi-objective optimization | constrainted multi-obj EHI-BO BMOO
  * 2016 | Pareto frontier learning with expensive correlated objectives | multi-obj EHI-BO with correlated objs.
  * 2016 | Multiobjective optimization of expensive-to-evaluate deterministic computer simulator models | multi-obj EMI
  * 2010 | Multiobjective optimization of expensive black-box functions via expected maximin improvement | multi-obj EMI
  * 2011 | Hypervolume-based expected improvement: Monotonicity properties and exact computation | EHVI
  * 2008 | The computation of the expected improvement in dominated hypervolume of Pareto front approximations | EHVI IEEE Evolutionary 2006 | ParEGO: a hybrid algorithm with on-line landscape approximation for expensive multiobjective optimization problems | multi-obj EI-BO ParEGO
  * 2020 | Bayesian multi-objective optimization with noisy evaluations using the Knowledge Gradient | multi-obj KG with noise
  * 2018 | A flexible multi-objective bayesian optimization approach using random scalarizations | multi-obj BO scalarization approach TS-TCH
  * 2016 | Multi-objective parameter configuration of machine learning algorithms using model-based optimization | multi-obj BO
  * 2016 | Multiobjective optimization of expensive-to-evaluate deterministic computer simulator models | multi-obj BO EMmI
  * 2016 | ε-pal: an active learning approach to the multi-objective optimization problem | multi-obj AL-based e-PAL
  * 2015 | Multiobjective optimization using Gaussian process emulators via stepwise uncertainty reduction | multi-obj EHI-like-BO SUR
  * 2013 | Active learning for multi-objective optimization | multi-obj AL-based PAL
  * 2008 | Multiobjective optimization on a limited budget of evaluations using model-assisted S-metric selection | multi-obj UCB-BO SmsEGO
  * 2002 | Bayesian optimization algorithms for multi-objective optimization | multi-obj BO
* ### parallel
  * 2020 | Parallel Predictive Entropy Search for Multi-objective Bayesian Optimization with Constraints | multi-point PES-based PPESMOC
  * 2020 | Differentiable Expected Hypervolume Improvement for Parallel Multi-Objective Bayesian Optimization | multi-point EHVI
  * 2020 | Differentiable Expected Hypervolume Improvement for Parallel Multi-Objective Bayesian Optimization | multi-obj multi-point BO qParEGO
  * 2019 | A multi-point mechanism of expected hypervolume improvement for parallel multi-objective bayesian global optimization | multi-point EHVI
  * 2019 | Bayesian Optimization for Multi-objective Optimization and Multi-point Search | multi-point EHVI MMBO
  * 2019 | Balancing exploration and exploitation in multiobjective batch bayesian optimization | multi-obj multi-point BO
  * 2018 | Efficient multiobjective optimization employing Gaussian processes, spectral sampling and a genetic algorithm | multi-obj multi-point BO TS-based TSEMO
  * 2018 | Exploiting strategy-space diversity for batch bayesian optimization | multi-point BO
  * 2018 | Batch bayesian optimization via multi-objective acquisition ensemble for automated analog circuit design | multi-obj BO MACE
  * 2017 | An efficient batch expensive multi-objective evolutionary algorithm based on Decomposition | multi-obj multi-point BO UCB-based MOBO/D
  * 2017 | Distributed batch Gaussian process optimization | multi-point BO
  * 2016 | Parallel bayesian global optimization of expensive functions | q-EI
  * 2016 | Batched gaussian process bandit optimization via determinantal point processes | multi-point BO
  * 2016 | Batch bayesian optimization via local penalization | General multi-point BO
  * 2016 | Investigation on parallel algorithms in efficient global optimization based on multiple points infill criterion and domain decomposition | multi-point BO
  * 2015 | Parallel predictive entropy search for batch global optimization of expensive objective functions | PES-based PPES
  * 2015 | Differentiating the multipoint expected improvement for optimal batch design | q-EI
  * 2014 | Parallelizing exploration-exploitation tradeoffs in gaussian process bandit optimization | BUCB batch-UCB
  * 2014 | Efficient global optimization with adaptive target setting | naive multi-obj multi-point BO
  * 2014 | Parallelizing exploration-exploitation tradeoffs in gaussian process bandit optimization | multi-point BO
  * 2013 | Fast computation of the multi-point expected improvement with applications in batch selection | q-EI
  * 2013 | Parallel Gaussian process optimization with upper confidence bound and pure exploration | GP-UCB-PE
  * 2012 | Hybrid batch Bayesian optimization | multi-point EI-based
  * 2010 | Kriging is well-suited to parallelize optimization | multi-point EI-based q-EI
  * 2010 | Batch bayesian optimization via simulation matching | multi-point BO simulated matching (SM)
  * 2009 | Expensive multiobjective optimization by MOEA/D with Gaussian process model | multi-obj multi-point BO ParEGO-based MOEA/D-EGO
* ### constraints
  * 2019 | Constrained Bayesian Optimization with Max-Value Entropy Search | constrained MES
  * 2016 | Predictive entropy search for multi-objective bayesian optimization with constraints | constrained multi-obj PES-BO PESMOC
  * 2015 | Predictive entropy search for bayesian optimization with unknown constraints | constrained BO
  * 2018 | Expected Hypervolume Improvement with Constraints | constrained EHI-BO
  * 2017 | A bayesian approach to constrained single- and multi-objective optimization | constrainted multi-obj EHI-BO BMOO
  * 2019 | Constrained Bayesian optimization with noisy experiments | constrained EI
  * 2015 | Scalable bayesian optimization using deep neural networks | constrained EI
  * 2014 | Bayesian optimization with unknown constraints | constrained EI
  * 2014 | Bayesian Optimization with Inequality Constraints | constrained EI
  * 2016 | A general framework for constrained bayesian optimization using information-based search | constrained BO
  * 2015 | Safe exploration for optimization with Gaussian processes | constrained BO
  * 2015 | Constrained Bayesian Optimization and Applications | constrained BO
* ### multi-fidelity
  * 2020 | Multi-fidelity Bayesian optimization with max-value entropy search | MF-MES
  * 2019 | A general framework for multi-fidelity bayesian optimization with gaussian processes | MF Entropy-based
  * 2018 | Practical bayesian optimization for variable cost objectives | MF-PES
  * 2017 | Information-based multi-fidelity Bayesian optimization | MF-PES
  * 2017 | Fast bayesian optimization of machine learning hyperparameters on large datasets | MF-ES
  * 2017 | Multi-fidelity bayesian optimisation with continuous approximations | MF-UBC BOCA
  * 2016 | Gaussian process bandit optimisation with multi-fidelity evaluations | MF-UBC
  * 2017 | Multi-information source optimization | MF-KG misoKG
  * 2015 | Multifidelity optimization using statistical surrogate modeling for non-hierarchical information sources | MF-EI
  * 2006 | Sequential kriging optimization using multiple-fidelity evaluations | MF-EI MF-SKO
* ### noisy evaluations
  * 2020 | Noisy-Input Entropy Search for Efficient Robust Bayesian Optimization | noisy robust MES NESEP
  * 2020 | Bayesian multi-objective optimization with noisy evaluations using the Knowledge Gradient | multi-obj KG with noise
  * 2019 | Constrained Bayesian optimization with noisy experiments | constrained EI











































































# Software
[Back to Top](#table-of-contents)
* [BoTorch](https://github.com/pytorch/botorch) | includes MES, MESMO, MF-MES, GIBBON, qKG, qEHVI, qParEGO, EHVI
* [Spearmint](https://github.com/HIPS/Spearmint) | includes PESMOC, PESMO, PESC, PES, ParEGO, SMSego, EHI, SUR
* [Cornell-MOE](https://github.com/wujian16/Cornell-MOE) | includes PES, KG, qEI, qKG


























































# Acknowledgement
[Back to Top](#table-of-contents)

Special thanks to everyone who contributed to this project.

| Name       | Bio        |
| :--------: | :--------: |
| [~](https://example.com) | PhD Student @XX University |
