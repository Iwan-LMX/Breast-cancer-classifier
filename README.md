# Analyze

## Accuracy
The assignment evaluated three models: Bayesian Network, Naïve Bayes, and TAN Bayes Classifiers. The accuracy of each model was as follows:
  
  - Bayesian Network: 91.25%. The accuracy is really amazing I haven't notice the reason before. But in this assignment I fount it is because it able to capture complex dependencies between features.
  - Naïve Bayes: 86.93%. The independence assumption between features limited its performance compared to the other models
  - TAN Bayes: 90.50%. This model' accuracy is slightly lower than BN, I guess this is because less flexible structure.

## Calibration Runtime
  - Bayesian Network: The calibration process was computationally intensive and required significant runtime due to the complexity of capturing dependencies among all features.
  - Naive Bayes: Calibration was fast and efficient as it only required calculating probabilities for each feature independently.
  - TAN Bayes: The runtime was moderate. While more complex than Naïve Bayes, it was faster than the full Bayesian Network due to the tree structure simplifying dependencies.

## Time Complexity
  - Bayesian Network: High time complexity, $O(n^2)$
  - Naive Bayes: Low complexity $O(n)$
  - TAN Bayes: Moderate time complexity $O(n logn)$

## Memory Complexity
  - Bayesian Network: High memory complexity, $O(n^2)$
  - Naive Bayes: Low memory $O(n)$
  - TAN Bayes: Moderate memory complexity $O(n logn)$

## Summary

The Bayesian Network offers the highest accuracy at the cost of time and memory complexity. Naive Bayes is the fastest and simplest but sacrifices accuracy due to unrealistic independence assumptions. TAN Bayes provides a balance between the two, offering improved accuracy over Naïve Bayes with moderate complexity.
