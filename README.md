# Awesome-XAI-Evaluation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome and organized multidisciplinary reference list of evaluation measures and methods for explainable machine learning (XAI) algorithms and systems. If you need more details and descriptions, you can read the [*full paper*](https://arxiv.org/pdf/1811.11839.pdf) or visit [my page](http://people.tamu.edu/~sina.mohseni/webpage/research.html) for more resources!


## How to Evaluate XAI?

We reviewed XAI-related research to organize different XAI design goals and evaluation measures. This awesome-list presents our categorization of selected existing design and evaluation methods that organizes literature along with three perspectives: **design goals**, **evaluation methods**, and **targeted users** of the XAI system. We provide summarized, ready-to-use tables of evaluation methods and recommendations for different goals in XAI research. <!-- ## What is this awesome list about? -->

![users 1](figures/target-users.png)


  
### Citation

Description and details in this paper: https://arxiv.org/pdf/1811.11839.pdf

```
@article{mohseni2018multidisciplinary,
  title={A Multidisciplinary Survey and Framework for Design and Evaluation of Explainable AI Systems},
  author={Mohseni, Sina and Zarei, Niloofar and Ragan, Eric D},
  journal={arXiv preprint arXiv:1811.11839},
  year={2018}
}
```


## Evaluation Measures

* Computational Measures
  * [M1: Fidelity of Interpretability Method](#m1:-fidelity-of-interpretability-technique)
  * [M2: Model Trustworthiness](#m2:-model-trustworthiness)
* Human-grounded Measures
  * [M3: Human-machine Task Performance](#m3:-human-machine-task-performance)
  * [M4: User Mental Model](#m4:-user-mental-model)
  * [M5: User Trust and Reliance](#m5:-user-trust-and-reliance)
  * [M6: Explanation Usefulness and Satisfaction](#m6:-explanation-usefulness-and-satisfaction)
  

## M1: Fidelity of Interpretability Technique

**Paper**|**Evaluation Method**
:-----:|:-----:
[The Building Blocks of Interpretability][16]|Sanity Check Experiment
[Graying the black box: Understanding DQNs][17]|Sanity Check Experiment
[Visualizing deep neural network decisions: Prediction difference analysis][18]|Sanity Check Experiment
[Understanding neural networks through deep visualization][19]|Sanity Check Experiment
[The (Un)reliability of saliency methods][20]|Sanity Check Experiment
[Improving the adversarial robustness and interpretability of deep neural networks by regularizing their input gradients][21]|Sanity Check Experiment
[Why Should I Trust You? Explaining the Predictions of Any Classifier][1]|Simulated Experiment
[Anchors: High-precision model-agnostic explanations][22]|Simulated Experiment
[Evaluating the visualization of what a deep neural network has learned][23]|Comparative Evaluation
[Right for the Right Reasons: Training Differentiable Models by Constraining their Explanations][5]|Comparative Evaluation
[On the Robustness of Interpretability Methods][alvarez2018robustness]|Sanity Check Experiment
[Human-grounded Evaluations of Explanation Methods for Text Classification][Lertvittayakumjorn2019human]|Human-grounded Evaluation
[Sanity Checks for Saliency Metrics][tomsett2019sanity]|Sanity Check Experiment
[Benchmarking Attribution Methods with Relative Feature Importance][yang2019benchmarking]|Comparative Evaluation
[Many Faces of Feature Importance: Comparing Built-in and Post-hoc Feature Importance in Text Classification][lai2019many]|Comparative Evaluation
[Towards Ground Truth Evaluation of Visual Explanations][Osman2020towards]|Feature-based Baseline
[Evaluating Recurrent Neural Network Explanations][arras2019evaluating]|Sanity Check
[Evaluating neural network explanation methods using hybrid documents and morphosyntactic agreement][poerner2018evaluating]|Comparative Evaluation



## M2: Model Trustworthiness

**Paper**|**Evaluation Method**
:-----:|:-----:
[A Human-Grounded Evaluation Benchmark for Local Explanations of Machine Learning][mohseni2018human]|Human-grounded Baseline
[A unified approach to interpreting model predictions][lundberg2017unified]|Human Judgment 
[Quantifying Interpretability and Trust in Machine Learning Systems][schmidt2019quantifying]|Human Judgment
[Human attention in visual question answering: Do humans and deep networks look at the same regions?][das2017human]|Human-grounded Baseline
[Visualizing and understanding convolutional networks][zeiler2014visualizing]|Debugging model and training
[Towards Explanation of DNN-based Prediction with Guided Feature Inversion][Du2018towards]|Human-grounded Baseline
[Explainable Deep Classification Models for Domain Generalization][Zunino2020explainable ]| Human Judgment
[Score-CAM: Improved Visual Explanations Via Score-Weighted Class Activation Mapping][Wang2019score]|Human-grounded Baseline
[Human-in-the-Loop Interpretability Prior][Lage2018human]|Human Judgment


## M3: Human-machine Task Performance

**Paper**|**Evaluation Method**
:-----:|:-----:
[Explanatory debugging: Supporting end-user debugging of machine-learned programs][15]|Task Performance, Task Throughput
[Why and why not explanations improve the intelligibility of context-aware intelligent systems][4]|Task Performance, Task Throughput
[ActiVis: Visual Exploration of Industry-Scale Deep Neural Network Models][14]|Task Performance 
[You are the only possible oracle: Effective test selection for end users of interactive machine learning systems][13]|Task Performance, Model Failure Prediction
[Interpretable decision sets: A joint framework for description and prediction][12]|Task Throughput
[A Workflow for Visual Diagnostics of Binary Classifiers using Instance-Level Explanations][11]|Model Failure Prediction
[Interacting meaningfully with machine learning systems: Three experiments][10]|Model Failure Prediction, Model Accuracy 
[Why should I you?: Explaining the predictions of any classifier][1]|Model Accuracy 
[Principles of explanatory debugging to personalize interactive machine learning][9]|Model Accuracy 
[Towards better analysis of deep convolutional neural networks][6]|Model Accuracy 
[Deepeyes: Progressive visual analytics for designing deep neural networks][8]|Model Accuracy 
[Topicpanorama: A full picture of relevant topics][7]|Model Tuning and Selection
[Updates in human-ai teams: Understanding and addressing the performance/compatibility tradeoff][Bansal2019updates] | Success Rate
[Human Evaluation of Models Built for Interpretability][Lage2019human]|User Prediction Accuracy
[Evaluating Visual Explanations for Similarity-Based Recommendations: User Perception and Performance][tsai2019evaluating]|--
[Can You Explain That? Lucid Explanations Help Human-AI Collaborative Image Retrieval][Ray2019can]|--
[Leveraging Rationales to Improve Human Task Performance][Das2020leveraging]|--


## M4: User Mental Model

**Paper**|**Evaluation Method**
:-----:|:-----:
[Updates in human-ai teams: Understanding and addressing the performance/compatibility tradeoff][Bansal2019updates] | Success Rate
[Intellingo: An Intelligible Translation Environment][coppers2018intellingo]|--
[Human Evaluation of Models Built for Interpretability][Lage2019human]|User Prediction Accuracy
[Evaluating Visual Explanations for Similarity-Based Recommendations: User Perception and Performance][tsai2019evaluating]|--
[When People and Algorithms Meet: User-reported Problems in Intelligent Everyday Applications][eiband2019people]|--
[Towards Accountable AI: Hybrid Human-Machine Analyses for Characterizing System Failure][Nushi2018towards]|--
[Beyond Accuracy: The Role of Mental Models in Human-AI Team Performance][bansal2019beyond]|User Success Rate
[Can You Explain That? Lucid Explanations Help Human-AI Collaborative Image Retrieval][Ray2019can]|--
[A Case for Backward Compatibility for Human-AI Teams][bansal2019case]|--
[Leveraging Rationales to Improve Human Task Performance][Das2020leveraging]|--



## M5: User Trust and Reliance

**Paper**|**Evaluation Method**
:-----:|:-----:
[The Impact of Placebic Explanations on Trust in Intelligent Systems][eiband2019impact]|Agreement Rate
[The Effects of Meaningful and Meaningless Explanations on Trust and Perceived System Accuracy in Intelligent Systems][Nourani2019effects]|User Perceived Accuracy
[I Drive — You Trust: Explaining Driving Behavior Of Autonomous Cars][wiegand2019drive]|Subjective Rating 
[The role of explanations on trust and reliance in clinical decision support systems][bussone2015role]|Agreement Rate
[Understanding the Effect of Accuracy on Trust in Machine Learning Models][yin2019understanding]|Agreement and Switch Rate
[How much information?: Effects of transparency on trust in an algorithmic interface][kizilcec2016much]|Subjective Rating
[“How do I fool you?”: Manipulating User Trust via Misleading Black Box Explanations][Lakkaraju2019fool]|--
[Do I Trust My Machine Teammate? An Investigation from Perception to Decision][Yu2019trust]| --
[Evaluating Effects of User Experience and System Transparency on Trust in Automation][Yang2017evaluating]|--
[Trust Calibration within a Human-Robot Team: Comparing Automatically Generated Explanations][Wang2016trust]|--
[User trust in intelligent systems: A journey over time][holliday2016user]|Subjective Rating
[What Does Explainable AI Really Mean? A New Conceptualization of Perspectives][doran2018does]|--
[The effects of example-based explanations in a machine learning interface][Cai2019effects]|--
[Let Me Explain: Impact of Personal and Impersonal Explanations on Trust in Recommender Systems][Kunkel2019let]|--
[Trust Dynamics in Human Autonomous Vehicle Interaction: A Review of Trust Models][basu2016trust]|--
[Effects of Model Confidence and Explanation on Accuracy and Trust Calibration][zhang2020effect]|Agreement and Switch Rate
[“How do I fool you?”: Manipulating User Trust via Misleading Black Box Explanations][Lakkaraju2019fool]| Subjective Rating



## M6: Explanation Usefulness and Satisfaction

**Paper**|**Evaluation Method**
:-----:|:-----:
[Are explanations always important? a study of deployed, low-cost intelligent interactive systems][bunt2012explanations]| Interview and Self-report
[Assessing demand for intelligibility in context-aware applications][lim2009assessing]| Interview and Self-report
[How should I explain? A comparison of different explanation types for recommender systems][gedikli2014should]| Interview, Self-report, User Learning duration
[Why and why not explanations improve the intelligibility of context-aware intelligent systems][lim2009and]| Interview and Self-report
[Intellingo: An Intelligible Translation Environment][coppers2018intellingo]| Likert-scale Questionnaire
[Human Evaluation of Models Built for Interpretability][lage2019human]| Likert-scale Questionnaire
[Intellingo: An Intelligible Translation Environment][coppers2018intellingo]| Engagement with Explanations





[1]: https://dl.acm.org/citation.cfm?id=2939778
[2]: https://dl.acm.org/citation.cfm?id=3173951
[3]: https://aaai.org/ojs/index.php/HCOMP/article/view/5280
[4]: https://dl.acm.org/citation.cfm?id=1519023
[5]: https://www.ijcai.org/proceedings/2017/371
[6]: https://ieeexplore.ieee.org/document/7536654
[7]: https://ieeexplore.ieee.org/document/7042494
[8]: https://ieeexplore.ieee.org/document/8019872
[9]: https://dl.acm.org/citation.cfm?id=2701399
[10]: https://dl.acm.org/citation.cfm?id=1555106
[11]: https://arxiv.org/abs/1705.01968
[12]: https://dl.acm.org/citation.cfm?id=2939672.2939874
[13]: https://ieeexplore.ieee.org/document/6682887
[14]: https://ieeexplore.ieee.org/abstract/document/8022871
[15]: https://ieeexplore.ieee.org/document/5635185
[16]: https://distill.pub/2018/building-blocks/
[17]: https://dl.acm.org/citation.cfm?id=3045591
[18]: https://openreview.net/forum?id=BJ5UeU9xx
[19]: https://arxiv.org/pdf/1506.06579.pdf
[20]: https://arxiv.org/pdf/1711.00867.pdf
[21]: https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/17337/15866
[22]: https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16982
[23]: https://ieeexplore.ieee.org/document/7552539
[Bansal2019updates]: https://www.microsoft.com/en-us/research/publication/updates-in-human-ai-teams-understanding-and-addressing-the-performance-compatibility-tradeoff/
[coppers2018intellingo]:https://dl.acm.org/doi/abs/10.1145/3173574.3174098
[Lage2019human]:https://www.aaai.org/ojs/index.php/HCOMP/article/view/5280
[tsai2019evaluating]: https://dl.acm.org/doi/10.1145/3320435.3320465
[eiband2019people]: https://dl.acm.org/doi/10.1145/3301275.3302262
[Nushi2018towards]: https://www.microsoft.com/en-us/research/uploads/prod/2018/07/accountable_AI_hcomp_2018.pdf
[bansal2019beyond]: https://www.microsoft.com/en-us/research/publication/beyond-accuracy-the-role-of-mental-models-in-human-ai-team-performance/
[Ray2019can]: https://www.aaai.org/ojs/index.php/HCOMP/article/download/5275/5127/
[bansal2019case]: https://arxiv.org/abs/1906.01148
[Das2020leveraging]: https://arxiv.org/pdf/2002.04202.pdf
[eiband2019impact]: https://dl.acm.org/doi/10.1145/3290607.3312787
[Nourani2019effects]: https://www.aaai.org/ojs/index.php/HCOMP/article/view/5284
[wiegand2019drive]: https://dl.acm.org/doi/10.1145/3290607.3312817
[bussone2015role]: https://ieeexplore.ieee.org/document/7349687
[yin2019understanding]: https://www.microsoft.com/en-us/research/publication/understanding-the-effect-of-accuracy-on-trust-in-machine-learning-models/
[kizilcec2016much]: https://dl.acm.org/doi/10.1145/2858036.2858402
[Lakkaraju2019fool]: https://www.aies-conference.com/2020/wp-content/papers/182.pdf
[Yu2019trust]: https://dl.acm.org/doi/10.1145/3301275.3302277
[Yang2017evaluating]: https://dl.acm.org/doi/10.1145/2909824.3020230
[Wang2016trust]: https://ieeexplore.ieee.org/document/7451741
[holliday2016user]: https://openaccess.city.ac.uk/id/eprint/14845/
[doran2018does]: https://arxiv.org/abs/1710.00794
[Cai2019effects]: https://dl.acm.org/doi/10.1145/3301275.3302289
[Kunkel2019let]: https://dl.acm.org/doi/10.1145/3290605.3300717
[basu2016trust]: https://www.aaai.org/ocs/index.php/SSS/SSS16/paper/download/12746/11926
[zhang2020effect]: https://dl.acm.org/doi/abs/10.1145/3351095.3372852
[mohseni2018human]: https://arxiv.org/abs/1801.05075
[lundberg2017unified]: https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions
[schmidt2019quantifying]: https://arxiv.org/abs/1901.08558
[das2017human]: https://arxiv.org/abs/1606.03556
[zeiler2014visualizing]: https://arxiv.org/abs/1311.2901
[bunt2012explanations]: https://dl.acm.org/doi/10.1145/2166966.2166996
[lim2009assessing]: https://dl.acm.org/doi/10.1145/1620545.1620576
[gedikli2014should]: https://dl.acm.org/doi/10.1016/j.ijhcs.2013.12.007
[lim2009and]: https://dl.acm.org/doi/10.1145/1518701.1519023
[alvarez2018robustness]: https://papers.nips.cc/paper/8003-towards-robust-interpretability-with-self-explaining-neural-networks
[Lertvittayakumjorn2019human]:https://www.aclweb.org/anthology/D19-1523/
[Du2018towards]:https://www.kdd.org/kdd2018/accepted-papers/view/towards-explanation-of-dnn-based-prediction-with-guided-feature-inversion
[Osman2020towards]: https://arxiv.org/abs/2003.07258
[Zunino2020explainable]:https://arxiv.org/abs/2003.06498
[Wang2019score]:https://arxiv.org/abs/1910.01279
[tomsett2019sanity]: https://papers.nips.cc/paper/8160-sanity-checks-for-saliency-maps
[lai2019many]:https://arxiv.org/abs/1910.08534
[Lage2018human]:https://papers.nips.cc/paper/8219-human-in-the-loop-interpretability-prior
[arras2019evaluating]:https://www.aclweb.org/anthology/W19-4813/
[Lakkaraju2019fool]: https://www.aies-conference.com/2020/wp-content/papers/182.pdf
[yang2019benchmarking]: https://arxiv.org/abs/1907.09701
[poerner2018evaluating]: https://www.aclweb.org/anthology/P18-1032/