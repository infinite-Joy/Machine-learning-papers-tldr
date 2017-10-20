# Machine-learning-papers-tldr
Short description on famous machine learning papers

* [Identifying and attacking the saddle point problem in high-dimensional non-convex optimization](http://arxiv.org/abs/1406.2572)

We used to think in high dimension it is local minima where the optimisation got stuck. However this paper proves that it is actually saddle points that trap the optimizer in very high dimension. And in fact local minima are really rare in high dimension.

* [Class-Based n-gram models of Natural Language](10.1.1.13.9919.pdf)

Depending on relatively simple statistics and Markov Chains, using n-gram models based on classes of words, we are able to extract classes that are either syntactically or semantically consistent.

* [Real-valued (Medical) Time Series Generation with Recurrent Conditional GANs](https://arxiv.org/pdf/1706.02633.pdf)

Cool way to evaluate their generative model: TSTR (Train on synthetic, test on real), which consists in training a supervised model on the generated data and testing it on real, held-out data. Using GANS generate time series data from training purposes. Also using Kolmogorov-Smirnov two-sample test to test if the generated data is different from the training data.
