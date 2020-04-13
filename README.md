## *Work carried out by Nicola Zotto and Rony Abecidan*

#### In this repo, you can find our study about the paper titled "On the Optimality of the Simple Bayesian Classifier under Zero-One Loss" by Domigos and Michael Pazzani of the University of California  published for the "Machine Learning" international forum in 1997. 

In the paper, the authors verify both theoretically and empirically that the "naive" Bayesian classifier does not require attribute independence to be optimal under zero-one loss and that it can perform quite well in practice on data sets with strong attribute dependence.
Additionally, the authors review how to best extend the simple Bayesian classifier and propose necessary conditions to verify that the Bayesian classifier is an optimal predictor under zero-one loss even when the independence assumption is violated.

In our report, we first recall the definition of the "naive" Bayesian classifier and it's main advantages and drawbacks. We then resume the conclusions of the article studied on the optimality of this classifier when the "naive" assumption is violated and on the conditions for this optimality. Finally, we propose an extension of the paper by implementing and studying some points evoked in the article and we propose at the end some strategies that may help the naive Bayes classifier to achieve a better performance on any dataset.

#### You will find in the notebook 'Experiments.py' some experiments we have made in order to :

- Illustrate some specific points treated in the article 
- Propose some strategies enabling to make the Naive Bayes Classifier more efficient in general

All the details are given in the report and the notebook, there is no particular installation to make except the classical machine learning librairies such as numpy, pandas and sklearn. We wish you a good reading =)

References : 
[1]    Pedro Domingos and Michael Pazzani. “On the Optimality of the Simple Bayesian Classifier under Zero-One Loss”. en. In: (), p. 28.
[2]    George H John and Pat Langley. “Estimating Continuous Distributions in Bayesian Classi ers”. en. In: (), p. 8.
[3]    Igor Kononenko. “Semi-naïve Bayesian classifier”. In: vol. 58. Apr. 2006, pp. 206–219.DOI:10.1007/BFb0017015.
[4]    Pat Langley. “Induction of recursive Bayesian classifiers”. en. In:Machine Learning: ECML-93. Ed. by J. Siekmann et al. Vol. 667.Series Title: Lecture Notes in Computer Science. Berlin, Heidelberg: Springer Berlin Heidelberg, 1993, pp. 153–164.ISBN: 978-3-540-56602-1 978-3-540-47597-2.DOI:10.1007/3-540-56602-3_134.URL:http://link.springer.com/10.1007/3-540-56602-3_134(visited on 04/11/2020).
[5]    Pat Langley and Stephanie Sage. “Induction of Selective Bayesian Classi ers”. en. In: (), p. 8.
[6]    Michael J Pazzani. “Searching for Dependencies in Bayesian Classi ers”. en. In: (), p. 10