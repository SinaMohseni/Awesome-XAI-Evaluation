# Awesome-XAI-Evaluation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome and organized reference list of evaluation measures and methods for explainable machine learning (XAI) algorithms and systems. If you need more details and descriptions, you can read the [*full paper*](https://arxiv.org/pdf/1811.11839.pdf) or visit [my page](http://people.tamu.edu/~sina.mohseni/webpage/research.html) for more resources!


## How to Evaluate XAI?

We reviewed XAI-related research to organize different XAI design goals and evaluation measures. This awesome-list presents our categorization of selected existing design and evaluation methods that organizes literature along three perspectives: **design goals**, **evaluation methods**, and **targeted users** of the XAI system. We provide summarized ready-to-use tables of evaluation methods and recommendations for different goals in XAI research. 
<!-- ## What is this awesome list about? -->

![users 1](figures/target-users.png)



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


**Title**| |**Discipline (HCI - VIS - ML- Psychol)**|**Paper Type**|**Research Sub-Domain**|**Design Goal**|**Targeted User**|**Evaluation Measure**|**Evaluation Method**|**Evaluation Type**|**Study Metrics**|**Study Variables**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
[Why Should I Trust You? Explaining the Predictions of Any Classifier][1]|KDD 2016|ML|Technique|Interpretable ML|explanations faithfulness- model trustworthiness|Novice-ML expert|Trust-Mental Model-Insight-Task performance|quantitative user study-simulation|Quantitavie |User accuracy| 
[It's Reducing a Human Being to a Percentage; Perceptions of Justice in Algorithmic Decisions][2]|CHI 2018|HCI|Evaluation|Transparency in AI (Justice)|---|Novice|Trust-Mental Model-Explanations fairness|qulitative user study-quantitative user study-crowdsourcing|Quantitavie - Qualitative | | 
[Human Evaluation of Models Built for Interpretability][3]|arXiv 2018|HCI|Evaluation|Evaluating Interpretable ML|---|novice|Mental Model|user study| |Time - Response time - accuracy - subjective satisfaction | 
[Why and Why Not Explanations Improve the Intelligibility of Context-Aware Intelligent Systems][4]|CHI 2009|HCI|Evaluation|Context-aware systems|---|novice|mental model - trust|crowdsourcing| | | 
[Right for the Right Reasons: Training Differentiable Models by Constraining their Explanations][5]|IJCAI 2017|ML|Technique|Interpretable ML|explanations faithfulness - comparison with other methods|ML expert|---|simulation| | | 
Interpretable Decision Sets: A Joint Framework for Description and Prediction|KDD 2016|ML|Technique|Interpretable ML|Explanation quality|Novice-ML expert|Explanations Understanding|user study with stuents-simulation| |User accuracy (based on 2 descriptive questions and 10 true/false questions ) - response time - number of words to answer descriptive questions |Comparing explanation type with base line (decision set or BDL)
Anchors: High-Precision Model-Agnostic Explanations|AAAI 2018|ML|Technique|Interpretable ML|Explanation quality|novice-ML expert|Mental model |user study with students-simulation| |coverage and precision in prediction of unseen examples |Comparing user mental model with base line and  with no explanations (Anchors or LIME or none)
Too Much, Too Little, or Just Right? Ways Explanations Impact End Usersâ€™ Mental Models |VL/HCC 2013|HCI|Evaluation|Recommendation systems (Music)|---|novice|mental model - trust |user study|Quantitavie - Qualitative |accuracy of explanations -  questionnaire|Explanations soundness - explanations completeness - 4 conditions 
The Problem of Explanations without User Feedback |ExSS workshop 2018|HCI|Evaluation|Interpretable ML|---|novice|trust-frustration-surprize|user study-crowdsourcing|quantitavie - Qualitative |think aloud-questionair-survey|different levels of user feedback impact-explanation types
User Trust in Intelligent Systems: A Journey Over Time |IUI 2016|HCI|Evaluation|Intelligent Systems (Data coder)|---|novice|trust|user study|Quantitavie - Qualitative |think aloud-questionair-survey|with and without explanations 
Be Careful; Things Can Be Worse than They Appear": Understanding Biased Algorithms and Users' Behavior Around Them in Rating Platforms|ICWSM  2017|CHI|Evaluation|Social media (Online reviews)|---|novice|Transparency vai algorithm auditing|analysis on user comments-cross platform audting|Qualitative |user reviews - hotel ratings|auditing from different hotel booking platforms
ActiVis: Visual Exploration of Industry-Scale Deep Neural Network Models|VAST 2017|VIS|System|Visual Analytics (Deep Learning)|---|ML expert|ML interpretabiltiy - Transparency|case study|qualitative |---|---
Explanatory Debugging: Supporting End-User Debugging of Machine-Learned Programs |VL/HCC 2010|HCI|Evaluation|Intelligent Systems|---|novice|mental model-debuging-natural explanations |user study|qualitative- quantitative|each features contribution in ML reasoning |with and without explanations 
A Workï¬‚ow for Visual Diagnostics of Binary Classiï¬ers using Instance-Level Explanation|VAST 2017|VIS|System|Visual Analytics (Healthcare)|---|data expert-ML expert|System diagnostic|Case study|qualitative|---|---
Towards Better Analysis of Deep Convolutional Neural Networks|TVCG 2017|VIS|System|Visual Analytics (Deep Learning)|---|data expert|interpretable ML - debuging |case study|qualitative|---|---
Evaluating the Visualization of What a Deep Neural Network Has Learne|TNNLS 2016|ML|Evaluation|Visual Analytics (Deep Learning)|explanations quality |ML expert|Explanations Quality|numerical|---|---|---
Learning from Explanations using Sentiment and Advice in RL|Transactions on Cognitive and Developmental Systems 2017|ML|Technique|Reinforcement Learning|---|novice|Interpretable ML - Mental Model|user study|quantitative|user rating of explanations quality|---
 Reading tea leaves: How humans interpret topic models|NIPS 2009|ML|Evaluation|Topic Modeling|---|novice|Mental Model|crowdsourcing|quantitative|word intrusion-topic intrusion|number of topics-dataset
Explanation and categorization: How â€œwhy?â€ informs â€œwhat?â€.|cognition journal 2009|Social Science|Evaluation|Human Explanations|---|novice|Explanations Types|user study|quantitative|questionaire|---
The structure and function of explanations|Trends in cognitive science 2006|Social Science|Evaluation|Human Explanations|---|novice|Explanations Types|user study|quantitative|questionaire|Explanations-Cause

[1]: https://dl.acm.org/citation.cfm?id=2939778
[2]: https://dl.acm.org/citation.cfm?id=3173951
[3]: https://aaai.org/ojs/index.php/HCOMP/article/view/5280
[4]: https://dl.acm.org/citation.cfm?id=1519023
[5]: https://www.ijcai.org/proceedings/2017/371


<!-- Topics / Domains: 
- interpretable machine learning
- Algorithmic fairness
- Recommendation systems
- Transparency AI
- Intelligent interactive systems and agents,
- Explainable intelligent systems and agents
- Human explanations 
- Human trust -->

<!--  main attributes: 
- research discipline (social science, HCI, visualization, or machine learning), 
- paper type (interface design, algorithm design, or evaluation paper), 
- application domain (machine learning
interpretability, algorithmic fairness, recommendation systems, transparency of intelligent systems,
intelligent interactive systems and agents, explainable intelligent systems and agents, human
explanations, or human trust), 
- machine learning model (e.g., deep learning, decision trees, SVM),
- data modality (image, text, tabular data), 
- explanation type (e.g., graphical, textual, data visualization),
- design goal (e.g., model debugging, user reliance, bias mitigation), 
- evaluation type (e.g., qualitative, computational, quantitative with human-subjects), 
- targeted user (AI novices, data experts, AI
experts), 
- evaluation measure (e.g., user trust, task performance, user mental model ). -->