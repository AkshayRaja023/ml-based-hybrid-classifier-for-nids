# ml-based-hybrid-classifier-for-nids
The traditional signature-based NIDS (Network-based Intrusion Detection
System) are very inefficient in detecting modern day attacks and it is safe to
say they are very much outdated. The traditional signature-based NIDS are
currently replaced by the Anomaly-based NIDS which is the next level
solution for the need of a smarter and highly efficient intrusion detection
system. Various Machine Learning and Deep Learning classifiers were
proposed over the years and the search for a optimal anomaly-based NIDS is
still on.
Most of the classifiers which produces high scores in terms of performance
metrics are very complicated deep learning models. The ML-based
classifiers faces challenges like moderate performance on large network
traffic dataset, high false alarm rates, etc. which makes it very inefficient
comparing the deep learning classifiers. To address these challenges we
have developed a new hybrid ML-based classifier, called RFXG (Random
Forest - XGBoost). For the purpose of evaluation and constructive
comparison the RFXG model is trained alongside four other ML models
namely Decision Tree, Random Forest, Naive Bayes and XGBoost.
The RFXG, even though less in complexity, has provided high scores in
various performance metrics. The model when trained and tested with the
CICIDS17 dataset gave out results of 99.91% accuracy, 99.90% precision,
99.87% recall value, 99,89% F1 score, 99.97% AUC score and a low false
alarm rate of 0.07% which clearly outperformed many of the previous works.
