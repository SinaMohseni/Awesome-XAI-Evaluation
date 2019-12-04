# Awesome-XAI-Evaluation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome and organized reference list of evaluation measures and methods for explainable machine learning (XAI) algorithms and systems. If you need more details and descriptions, you can read the [*full paper*](https://arxiv.org/pdf/1811.11839.pdf) or visit [my page](http://people.tamu.edu/~sina.mohseni/webpage/research.html) for more resources!


## How to Evaluate XAI?

We reviewed XAI-related research to organize different XAI design goals and evaluation measures. This awesome-list presents our categorization of selected existing design and evaluation methods that organizes literature along three perspectives: **design goals**, **evaluation methods**, and **targeted users** of the XAI system. We provide summarized ready-to-use tables of evaluation methods and recommendations for different goals in XAI research. 
<!-- ## What is this awesome list about? -->

![dog 1](figures/target-users.png)



## Evaluation Methods

* **Computational Measures**
   * [Fidelity of Interpretability Method](#fidelity-of-interpretability-method)
   * [Model Trustworthiness](#model-trustworthiness)
* **Human-grounded Measures**
   * [Human-machine Task Performance](#human-machine-task-performance)
   * [User Mental Model](#user-mental-model)
   * [User Trust and Reliance](#conferences)
   * [Explanation Usefulness and Satisfaction](#explanation-usefulness-and-satisfaction)
  

## Fidelity of Interpretability Method


## Model Trustworthiness


## Human-machine Task Performance


## User Mental Model


## User Trust and Reliance


## Explanation Usefulness and Satisfaction
  
## Full Reference Table 

**Informal Identifier**|**Venue**|**Year**|**Title**|**Discipline (HCI - VIS - ML- Psychol)**|**Paper Type (System - Evaluation - Algorithm - Survey)**|**Application Domain**|**Research Sub-Domain**|**Evaluation Targeted User (Novice - data expert - ML expert- all)**|**Evaluation Goal**|**Evaluation Measure**|**Evaluation Type (User Study - Case study - Simulation - Numerical - Crowdsourcing)**|**Study Metrics**|**Number lab-based participants (between subject - within subject)**|**Number Crowdusers  (between subject - within subject)**|**Evaluation Type **|**Study Variables (independent variables/factors)**|**Simulation Metrics**|**Model**|**Explanation Type **|**Data (image-text-sentiment-tabular-game)**|**Dataset**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
ribeiro2016should|KDD|2016|Why Should I Trust You?â€ Explaining the Predictions of Any Classifier|ML|algorithm|ml|Interpretable ML|Novice-ML expert|explanations faithfulness- model trustworthiness|Trust-Mental Model-Insight-Task performance|quantitative user study-simulation|User accuracy|0-0|0-0|Quantitavie | | |SVM-RF-Deep-NN-DT-LR| |text-image-sentiment|20newsgroup-imagenet-books-dvds
Binns:2018:RHP:3173574.3173951|CHI|2018|Reducing a Human Being to a Percentageâ€™; Perceptions of Justice in Algorithmic Decisions|HCI|evaluation|justice|Interpretable ML|Novice|---|Trust-Mental Model-Explanations fairness|qulitative user study-quantitative user study-crowdsourcing| |0-19|325-65|Quantitavie - Qualitative | | |fake model | |tabular|personal loan-promotion at work-car insurance rate-airline rerouting-freezing bank account
narayanan2018humans|arXiv|2018|How do Humans Understand Explanations from Machine Learning Systems? An Evaluation of the Human-Interpretability of Explanatio|HCI|evaluation|food recommendation systems - healthcare decision making|Evaluating ML Explanations|novice|---|Mental Model|user study|Time - Response time - accuracy - subjective satisfaction |0-0|600-0| | | |fake model| |text|---
lim2009and|CHI|2009|Why and Why Not Explanations Improve the Intelligibility of Context-Aware Intelligent Systems |HCI|evaluation|decision making|Context-aware systems|novice|---|mental model - trust|crowdsourcing| |0-0|211-0| | | |decision tree| |tabular| 
ijcai2017-371|IJCAI|2017|Right for the Right Reasons: Training Differentiable Models by Constraining their Explanations|ML|algorithm|ml|Interpretable ML|ML expert|explanations faithfulness - comparison with other methods|---|simulation| |---|---| | | |gradient| |image-text-tabular|20newsgroup-iriscaner-mnist
lakkaraju2016interpretable|KDD|2016|Interpretable Decision Sets: A Joint Framework for Description and Prediction|ML|algorithm|ml|Interpretable ML|Novice-ML expert|Explanation quality|Explanations Understanding|user study with stuents-simulation|User accuracy (based on 2 descriptive questions and 10 true/false questions ) - response time - number of words to answer descriptive questions |0-47|0-0| |Comparing explanation type with base line (decision set or BDL)|number of rules - fraction of overlap between rules - rule length| interpretable decision sets| |tabular|bail outcome - student performance - medical diagnosis 
anchors:aaai18|AAAI|2018|Anchors: High-Precision Model-Agnostic Explanations|ML|algorithm|ml|Interpretable ML|novice-ML expert|Explanation quality|Mental model |user study with students-simulation|coverage and precision in prediction of unseen examples |26-0|0-0| |Comparing user mental model with base line and  with no explanations (Anchors or LIME or none)|Explanations coverage - Explanations percisiopn - time |logistic regression - gradient boosted trees - multilayer perceptron| |tabular-text-image-VQA|adult-lending-rcdv-imagenet-visual7w
kulesza2013too|VL/HCC|2013|Too Much, Too Little, or Just Right? Ways Explanations Impact End Usersâ€™ Mental Models |HCI|evaluation|music recommendation|Recommendation systems |novice|---|mental model - trust |user study|accuracy of explanations -  questionnaire|17-0|0-0|Quantitavie - Qualitative |Explanations soundness - explanations completeness - 4 conditions |---|hybrid recommender system - kNearst neighborhood - Weka| |recommendation| 
smith2018|ExSS workshop|2018|The Problem of Explanations without User Feedback |HCI|evaluation|---|Interpretable ML|novice|---|trust-frustration-surprize|user study-crowdsourcing|think aloud-questionair-survey|0-0|0-0|quantitavie - Qualitative |different levels of user feedback impact-explanation types|---|---| |---|--
holliday2016user|IUI|2016|User Trust in Intelligent Systems: A Journey Over Time |HCI|evaluation|auto qualitative coder|Intelligent Systems|novice|---|trust|user study|think aloud-questionair-survey|15-0|0-0|Quantitavie - Qualitative |with and without explanations |---|---| |text|---
eslami2017careful|ICWSM |2017|Be Careful; Things Can Be Worse than They Appear": Understanding Biased Algorithms and Users' Behavior Around Them in Rating Platforms|CHI|evaluation|online reviews|social media|novice|---|Transparency vai algorithm auditing|analysis on user comments-cross platform audting|user reviews - hotel ratings|---|---|Qualitative |auditing from different hotel booking platforms|---|---| |text|---
kahng2018cti|VAST|2017|ActiVis: Visual Exploration of Industry-Scale Deep Neural Network Models|VIS|system|ML|Visual Analytics|ML expert|---|ML interpretabiltiy - Transparency|case study|---|0-3|---|qualitative |---|---|DNN|Instance and subset explanations - visual explanations - graph|text|facebook internal
kulesza2010explanatory|VL/HCC|2010|Explanatory Debugging: Supporting End-User Debugging of Machine-Learned Programs |HCI|Evaluation|auto qualitative coder|Intelligent Systems|novice|---|mental model-debuging-natural explanations |user study|each features contribution in ML reasoning |0-9|---|qualitative- quantitative|with and without explanations |---|fake model|instance explanations - Textual explanations - why explanations - why not explanations|text| 
kulesza2010explanatory|VL/HCC|2010|Explanatory Debugging: Supporting End-User Debugging of Machine-Learned Programs |HCI|Evaluation|auto qualitative coder|Intelligent Systems|novice|---|mental model-debuging|user study|likert scale about usefulness of explanations - preceived accuracy of system - free form questions about how they beleived system is working - ML accuracy sF1 score|0-74|---|qualitative- quantitative|different types of explanations|---|fake model|instance explanations - Textual explanations - why explanations - why not explanations|text| 
Krause2017workflow|VAST|2017|A Workï¬‚ow for Visual Diagnostics of Binary Classifiers using Instance-Level Explanation|VIS|system|healthcare|Visual Analytics|data expert-ML expert|---|System diagnostic|Case study|---|0-1|---|qualitative|---|---|NB-LR-RF-MLP|instance explanation|tabular|internal hospital 
Liu2017b|TVCG|2017|Towards Better Analysis of Deep Convolutional Neural Networks|VIS|system|ML|Visual Analytics|data expert|---|interpretable ML - debuging |case study|---|0-3|---|qualitative|---|---|CNN|Model|image|---
samek2017evaluating|TNNLS|2016|Evaluating the Visualization of What a Deep Neural Network Has Learne|ML|evaluation|ML|Machine Learning |ML expert|explanations quality |Explanations Quality|numerical|---|---|---|---|---|AOPC|CNN|instance explanations|image|MIT PLACES - ILSVRC2012 - SUN397
Boukhelifa2018|Human and Machine Learning|2018|Evaluation of Interactive Machine Learning Systems|HCI|evaluation|---|ML|---|---|---|---|---|---|---|---|---|---|---|---|---|---
krening2017learning|Transactions on Cognitive and Developmental Systems|2017|Learning from Explanations using Sentiment and Advice in RL|ML|algorithm|ML Agents|RL|novice|---|Interpretable ML - Mental Model|user study|user rating of explanations quality|May-00|---|quantitative|---|---|RL|instance explanations|game|---
chang2009reading|NIPS|2009| Reading tea leaves: How humans interpret topic models|ML|evaluation|Topic modeling|Topic modeling|novice|---|Mental Model|crowdsourcing|word intrusion-topic intrusion|---|X-0|quantitative|number of topics-dataset|---|LDA-pLSI-CTM|instance explanations|text|New York Times-  Wikipedia 
lombrozo2009explanation|cognition journal|2009|Explanation and categorization: How why? informs â€œwhat?.|Psychol|evaluation|---|Human Explanations|novice|---|Explanations Types|user study|questionaire|192-0|---|quantitative|---|---|---|instance explanations|text|---
lombrozo2006structure|Trends in cognitive science|2006|The structure and function of explanations|Psychol|evaluation|---|Human Explanations|novice|---|Explanations Types|user study|questionaire|---|---|quantitative|Explanations-Cause|---|---|instance explanations|text|---
