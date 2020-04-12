#### In this repo, you can find our study about the paper titled "On the Optimality of the Simple Bayesian Classifier under Zero-One Loss" by Domigos and Michael Pazzani of the University of California  published for the "Machine Learning" international forum in 1997. 

In the paper, the authors verify both theoretically and empirically that the "naive" Bayesian classifier does not require attribute independence to be optimal under zero-one loss and that it can perform quite well in practice on data sets with strong attribute dependence.
Additionally, the authors review how to best extend the simple Bayesian classifier and propose necessary conditions to verify that the Bayesian classifier is an optimal predictor under zero-one loss even when the independence assumption is violated.

In our report, we first recall the definition of the "naive" Bayesian classifier and it's main advantages and drawbacks. We then resume the conclusions of the article studied on the optimality of this classifier when the "naive" assumption is violated and on the conditions for this optimality. Finally, we propose an extension of the paper by implementing and studying some points evoked in the article and we propose at the end some strategies that may help the naive Bayes classifier to achieve a better performance on any dataset.

#### You will find in the notebook 'Experiments.py' some experiments we have made in order to :

- Illustrate some specific points treated in the article 
- Propose some strategies enabling to make the Naive Bayes Classifier more efficient in general

All the details are given in the report and the notebook, there is no particular installation to make except the classical machine learning librairies such as numpy, pandas and sklearn. We wish you a good reading =)