---
layout: project
type: project
image: img/phish.jpg
title: "Classifying Phishing Websites with Machine Learning"
date: 2025
published: true
labels:
  - Machine Learning
  - Algorithms
  - Performance Analysis
  - Phishing & Malware
summary: "A study I did while taking machine learning at Yonsei University, which compares the performances metrics of models to classify phishing websites when trained with different algorithms."
---



## Introduction 
One person is all it takes for a business to collapse under the hand of cyber attack. The most common medium of this is phishing. To protect the company’s confidentiality, integrity, and accessibility of data, cyber defense tools can be implemented into the network and device infrastructure. These can serve many purposes, such as an access gateway, web proxy, or detection system, to name a few. Everyday, the average individual, consumer, and employee alike browse the internet and generate endless data transactions on the worldwide web. To heed off the most common method attack of human exploitation, such tools also exist to classify legitimate, suspicious, and phishing websites through the use of algorithmic and machine learning. 

As a student in the field of technology, I have always been intrigued by the systems we have so intelligently developed, and will continue to outlive us in our time. And as a student experiencing the field of cybersecurity and enthusiastic about the protection of data and the investigation of cybercrime, I find that nobody is ever fully protected from phishing, and by the speed that we can communicate digitally, can be manipulated at any given moment. 

Through the very technology we’ve studied, we can also enhance our protection and awareness of these through machine learning methods that classify malicious vs. legitimate websites. Websites have many attributes that can provide suspicious indicators, and in these datasets from UCI’s Machine Learning Repository, we can analyze how K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Decision Tree (DT) Classifiers compare in accuracy, precision, recall, and F1-score when classifying websites as legitimate, suspicious, or malicious.

## Datasets
Dataset 1: [“Website Phishing”](https://archive.ics.uci.edu/dataset/379/website+phishing) (10 attributes, 1355 Samples) 
Supplementary Article: [“Phishing Attacks and Websites Classification Using Machine Learning and Multiple Datasets (A Comparative Analysis)”] (https://arxiv.org/pdf/2101.02552)

Dataset 2: [“Phishing Websites”](https://archive.ics.uci.edu/dataset/327/phishing+websites) (31 attributes, 11055 Samples)
Supplementary Article: [“An Assessment of Features Related to Phishing Websites using an Automated Technique”](https://ieeexplore.ieee.org/document/6470857)
Extensive Feature Details: [“Phishing Websites Features”](https://docs.google.com/document/d/18UR797f4JmD1AYxEy-Os7mQvf4jvhKo2/edit)

In both of the datasets, the number of samples corresponds to the number of websites that were analyzed with a malware analyzer. For each specific attribute (such as having IP address, web traffic, pop up window, etc.), the analyzer assigns that website’s attribute an integer, where -1 means phishing, 0 means suspicious (either phishing or legitimate), and 1 means legitimate. For each website, the overall disposition is given the label “Result” and also uses the same integer assignment classification system. We will be comparing the performance metrics of our classification methods and report both the baseline models’ and optimized models’ accuracy, precision, recall, and F1-score statistics, as well as the gain in the models’ performance metrics after K-fold cross validation optimization. 

<div>
  <img class="img-fluid" src="../img/dataset2(1)" style="display: inline-block; width: 30%; margin-right: 1%;">
  <img class="img-fluid" src="../img/dataset2(2)" style="display: inline-block; width: 30%; margin-right: 1%;">
  <img class="img-fluid" src="../img/dataset2(3)" style="display: inline-block; width: 30%;">
</div>

## Results & Discussion
Overall, Dataset 1 models showed a moderate to accurate performance in overall metrics, while Dataset 2 shows significantly higher scores across the board. Among the models trained with Dataset 1, the optimized SVM outperformed all other models in every scoring. In this dataset, SVM also had the greatest improvement in accuracy by 0.0258 from the optimization, whereas KNN showed no improvement, and the decision tree decreased in accuracy by 0.0259. In the case of the Dataset 1 decision tree models, after optimizing, the model decreased in all metrics from its baseline model’s performance. Though GridSearchCV found the best hyperparameters for the decision tree, this decrease in performance may be attributed to some overfitting of the data, where the model learns the specific patterns in the training set, rather than generalizing underlying patterns in the test set. This highlights the importance of gathering metrics from a model’s baseline performance, and gauging if an optimization may even be an computationally and performance effective approach. 

In light of such findings, Dataset 2 also helps to inform how these results differ, and how accuracy can improve more from using a larger training dataset rather than optimizing models. In Dataset 2, SVM also had a greater improvement than the other models, having an increase in accuracy of 0.0195, whereas KNN and Decision Tree experienced no improvement. In contrast to Dataset 1, Decision Tree performed the best at a high 0.9701 accuracy. Through this, we are able to see how training with much larger data produces far greater accuracy and precision. We are even able to observe that the optimization of these training models may serve little to no improvement and can be computationally expensive, yet baseline models can produce high performing metrics if a larger and more robust dataset is used to train the model. 

## Conclusion

Conclusion
Through the analysis of KNN, SVN, and Decision Tree performance with both a smaller sample set (Dataset 1) and a larger sample sent (Dataset 2), we can say that these machine learning techniques are highly effective in aiding to recognize malicious websites, and machine learning models are able to achieve high accuracy to distinguish phishing sites from legitimate ones, with our best model reaching over 97% accuracy. 
We have also learned that although hyperparameter tuning can optimize some gain in accuracy, as seen in SVM's consistent improvement in both Dataset 1 and Dataset 2, the quantity and quality of the training data itself is often more influential on model performance. This is seen also in the KNN and Decision Tree models, which did not improve in accuracy in either datasets, yet reached substantially higher accuracy in their baseline models when given such a sample as Dataset 2. 

These findings suggest that for real-world tools such as attack prevention and detection tools, collecting robust and strongly representative data can supplement a higher performing learning model than using excessive computational resources to fine-tune, thus bettering the success of the tool, increasing the defense for its users, and maximizing the cost efficiency for further developments or wider deployments of tool. Ultimately, this project confirms that machine learning can be used as powerful tools for practical cybersecurity defense, and an efficient approach balances both the scale of the data and the appropriate optimization. 
