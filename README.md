# Awesome Human Activity Recognition (mainly related/interacted to SENSOR data)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<p align="center">
  <img width="300" src="https://i.imgur.com/Ky2jxnj.png" "Awesome!">
</p>

An up-to-date & curated list of Awesome IMU-based Human Activity Recognition(Ubiquitous Computing) papers, methods & resources. Please note that most of the collections of researches are mainly based on IMU data.

## Acknowledgment

Many thanks to the useful publications and repos: [Jingdong Wang](https://github.com/jindongwang), [Awesome-Deep-Vision](https://github.com/kjw0612/awesome-deep-vision), [Awesome-Deep-Learning-Papers](https://github.com/terryum/awesome-deep-learning-papers), [Awesome-Self-Supervised-Learning](https://github.com/jason718/awesome-self-supervised-learning), [Awesome-Semi-Supervised-Learning](https://github.com/yassouali/awesome-semi-supervised-learning) and [Awesome-Crowd-Counting](https://github.com/gjy3035/Awesome-Crowd-Counting#datasets).

## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please feel free to contribute this list.

## Misc

### Events and Conferences
- IMWUT,UbiComp, IJCAI, AAAI, TIP, TNNLS, TPAMI, TMM, Pattern Recognition, AI, Nature Communication

## Datasets

- mHealth [[**link**](http://archive.ics.uci.edu/ml/datasets/mhealth+dataset)]
- Opportunity [[**link**](https://archive.ics.uci.edu/ml/datasets/opportunity+activity+recognition#:~:text=Data%20Set%20Information%3A-,The%20OPPORTUNITY%20Dataset%20for%20Human%20Activity%20Recognition%20from%20Wearable%2C%20Object,%2C%20feature%20extraction%2C%20etc)]
- PAMAP2 [[**link**](https://archive.ics.uci.edu/ml/datasets/pamap2+physical+activity+monitoring)]
- GOTOV [[**link**](https://data.4tu.nl/articles/dataset/GOTOV_Human_Physical_Activity_and_Energy_Expenditure_Dataset_on_Older_Individuals/12716081)]
- REALDISP [[**link**](https://archive.ics.uci.edu/ml/datasets/REALDISP+Activity+Recognition+Dataset)]
- UCIDSADS [[**link**](https://archive.ics.uci.edu/ml/datasets/daily+and+sports+activities)]
- MMAct [[**link**](https://paperswithcode.com/dataset/mmact#:~:text=Human%20Action%20Understanding-,MMAct%20is%20a%20large%2Dscale%20dataset,multi%2Fcross%20modal%20action%20understanding.&text=and%20pressure%20signal.-,The%20dataset%20consists%20of%20more%20than%2036k%20video%20clips%20for,in%20four%20different%20distinct%20scenarios.)]
- TotalCapture [[**link**](https://cvssp.org/data/totalcapture/)]
- WISDM [[**link**](https://www.cis.fordham.edu/wisdm/dataset.php)]
- MotionSense [[**link**](https://paperswithcode.com/dataset/motionsense)]
- MobiAct [[**link**](https://bmi.hmu.gr/the-mobifall-and-mobiact-datasets-2/)]
- Fenland [[**link**](https://www.cambridge.org/core/journals/british-journal-of-nutrition/article/crosssectional-association-between-snacking-behaviour-and-measures-of-adiposity-the-fenland-study-uk/8DD5F30489DA45BA5723C6ED00876307)]
- Salad 50 [[**link**](https://cvip.computing.dundee.ac.uk/datasets/foodpreparation/50salads/)]
- DIP [[**link**](https://dip.is.tuebingen.mpg.de/)]
- LARa [[**link**](https://www.mdpi.com/1424-8220/20/15/4083)]

## Tools
- SimTK [[**link**](https://simtk.org/projects/opensim)]
- OpenSense [[**link**](https://simtk-confluence.stanford.edu:8443/display/OpenSim/OpenSense+-+Kinematics+with+IMU+Data)]

## Potential Research Direction
* Large-Scale/Diverse Dataset Research
* Multi-Modality: sensor-vision, sensor-skeleton, sensor-3DPose, Sensor-Motion
* window selection
* Generative Model: e.g., cross modality data generation, IMU2Skeleton
* Handling the NULL-Class problem
* Open-World, Real-World: complex/non-repetitive activities
* Advanced model
* Data-cental: active learning, unsupervised learning, semi-supervised learning, self-supervised learning
* Actiion Segmentation
* Are the existing settings/models reliable?
* Graph Representation
* Motion-Capture, Kinetic
* Privacy related
* Interpretability
* Data Imbalance
* Domain Adaptation
* Fine-Grained
* Multi-Label
* Federated Learning
* Ensemble
* Knowledge Integragation/distillation

## Papers

### Surveys & Overview

- <a name="DLHAR"></a> A Survey on Deep Learning for Human Activity Recognition (**ACM Computing Surveys (CSUR)**) [[paper](https://dl.acm.org/doi/abs/10.1145/3472290)]

- <a name="ML4SENSORHAR"></a> Applying Machine Learning for Sensor Data Analysis in Interactive Systems: Common Pitfalls of Pragmatic Use and Ways to Avoid Them (**ACM Computing Surveys (CSUR)**) [[paper](https://dl.acm.org/doi/abs/10.1145/3459666)]

- <a name="DL4SAR"></a> **[DL4SAR]** Deep Learning for Sensor-based Activity Recognition: A Survey (**Pattern Recognition Letters**) [[paper](https://arxiv.org/pdf/1707.03502.pdf)][[code](https://github.com/jindongwang)]

- <a name="Overview"></a> Deep Learning for Sensor-based Human Activity Recognition: Overview, Challenges, and Opportunities (**ACM Computing Surveys (CSUR)**) [[paper](https://dl.acm.org/doi/abs/10.1145/3447744)]

### 2022

- Zero-Shot Learning for IMU-Based Activity Recognition Using Video Embeddings
- Deep Transfer Learning with Graph Neural Network for Sensor-Based Human Activity Recognition
- Meta-learning meets the Internet of Things: Graph prototypical models for sensor-based human activity recognition
- Federated Multi-Task Learning
- Hierarchical Self Attention Based Autoencoder for Open-Set Human Activity Recognition
- Assessing the State of Self-Supervised Human Activity Recognition using Wearables
- ROBUST AND EFFICIENT UNCERTAINTY AWARE BIOSIGNAL CLASSIFICATION VIA EARLY EXIT ENSEMBLES
- Machine learning detects altered spatial navigation features in outdoor behaviour of Alzheimer’s disease patients
- Evaluating Contrastive Learning on Wearable Timeseries for Downstream Clinical Outcomes
- Segmentation-free Heart Pathology Detection Using Deep Learning
- Anticipatory Detection of Compulsive Body-focused Repetitive Behaviors with Wearables
- Assessing the State of Self-Supervised Human Activity Recognition using Wearables
- Method and system for automatic extraction of virtual on-body inertial measurement units
- Enhancing the Security & Privacy of Wearable Brain-Computer Interfaces
- What Makes Good Contrastive Learning on Small-Scale Wearable-based Tasks?
- Detecting Smartwatch-Based Behavior Change in Response to a Multi-Domain Brain Health Intervention
- ColloSSL: Collaborative Self-Supervised Learning for Human Activity Recognition
- Multi-scale Deep Feature Learning for Human Activity Recognition Using Wearable Sensors
- Improving Wearable-Based Activity Recognition Using Image Representations
- Multi-sensor information fusion based on machine learning for real applications in human activity recognition: State-of-the-art and research challenges
- A recurrent neural network architecture to model physical activity energy expenditure in older people
- Application of artificial intelligence in wearable devices: Opportunities and challenges
- A Close Look into Human Activity Recognition Models using Deep Learning
- YONO: Modeling Multiple Heterogeneous Neural Networks on Microcontrollers
- CogAx: Early Assessment of Cognitive and Functional Impairment from Accelerometry
- Deep Temporal Conv-LSTM for Activity Recognition
- Human Activity Recognition from Wearable Sensor Data Using Self-Attention
- Combined deep centralized coordinate learning and hybrid loss for human activity recognition
- Real-time human activity recognition using conditionally parametrized convolutions on mobile and wearable devices
- Proposing a Fuzzy Soft‐max‐based classifier in a hybrid deep learning architecture for human activity recognition
- HAR-GCNN: Deep Graph CNNs for Human Activity Recognition From Highly Unlabeled Mobile Sensor Data
- Sensor-based human activity recognition using fuzzified deep CNN architecture with λmax method
- WearRF-CLA: Continuous Location Authentication with Wrist Wearables and UHF RFID
- Non-Bayesian Out-of-Distribution Detection Applied to CNN Architectures for Human Activity Recognition
- Improving the Performance of Open-Set Classification in Human Activity Recognition by Applying a Residual Neural Network Architecture
- A Review on Topological Data Analysis in Human Activity Recognition
- UBIWEAR: An End-To-End Framework for Intelligent Physical Activity Prediction With Machine and Deep Learning
- High-Precision and Personalized Wearable Sensing Systems for Healthcare Applications
- ColloSSL: Collaborative Self-Supervised Learning for Human Activity Recognition
- DANA: Dimension-Adaptive Neural Architecture
- DeXAR: Deep Explainable Sensor-Based Activity Recognition in Smart-Home Environments
- Latent Independent Excitation for Generalizable Sensor-based Cross-Person Activity Recognition
- The Severity Prediction of The Binary And Multi-Class Cardiovascular Disease -- A Machine Learning-Based Fusion Approach
- An Unsupervised User Adaptation Model for Multiple Wearable Sensors Based Human Activity Recognition
- Machine Learning on Clinical Time Series: Classification and Representation Learning
- Learning Disentangled Behaviour Patterns for Wearable-based Human Activity Recognition
- What Makes Good Contrastive Learning on Small-scale Wearable-based Tasks?
- Leveraging Activity Recognition to Enable Protective Behavior Detection in Continuous Data,
- IMU2Doppler: Cross-Modal Domain Adaptation for Doppler-based Activity Recognition Using IMU Data
- A CNN-based Human Activity Recognition System Combining a Laser Feedback Interferometry Eye Movement Sensor and an IMU for Context-aware Smart Glasses
- Winect: 3D Human Pose Tracking for Free-form Activity Using Commodity WiFi
- Zero-Shot Learning for IMU-Based Activity Recognition Using Video Embeddings
- KATN: Key Activity Detection via Inexact Supervised Learning
- Fusing Visual and Inertial Sensors with Semantics for 3D Human Pose Estimation
- Multi-gat: A graphical attention-based hierarchical multimodal representation learning approach for human activity recognition
- Semantics-aware adaptive knowledge distillation for sensor-to-vision action recognition
- Human action recognition from various data modalities: A review
- Eldersim: A synthetic data generation platform for human action recognition in eldercare applications
- Home action genome: Cooperative compositional action understanding
- Cross-modal Knowledge Distillation for Vision-to-Sensor Action Recognition
- Sensor-Augmented Egocentric-Video Captioning with Dynamic Modal Attention
- Disentanglement Approach for Video Action Recognition
- Fusion-GCN: Multimodal Action Recognition using Graph Convolutional Networks
- Meta-learning meets the Internet of Things: Graph prototypical models for sensor-based human activity recognition
- Human Activity Recognition Based on Wearable Sensor Data: A Standardization of the State-of-the-Art


### 2021
- <a name="POSE"></a> Approaching the Real-World: Supporting Activity Recognition Training with Virtual IMU Data [[paper](https://dl.acm.org/doi/abs/10.1145/3478096)]

- <a name="CANYOU"></a> Can You See It? Good, So We Can Sense It! [[paper](https://dl.acm.org/doi/abs/10.1145/3486880.3486891)]

- <a name="ENCT"></a> An Ensemble of ConvTransformer Networks for the Sussex-Huawei Locomotion-Transportation (SHL) Recognition Challenge [[paper](https://dl.acm.org/doi/abs/10.1145/3460418.3479383)]

- <a name="NASHAR"></a> Fast Deep Neural Architecture Search for Wearable Activity Recognition by Early Prediction of Converged Performance [[paper](https://dl.acm.org/doi/abs/10.1145/3460421.3478813)]

- <a name="ACCESSHAR"></a> Human Activity Recognition Based on Acceleration Data From Smartphones Using HMMs [[paper](https://ieeexplore.ieee.org/abstract/document/9557268)]

- <a name="ORCL"></a> On the Role of Context Length for Feature Extraction and Sequence Modeling in Human Activity Recognition [[paper](https://dl.acm.org/doi/abs/10.1145/3460421.3478825)]

- <a name="ON"></a> ObscureNet: Learning Attribute-invariant Latent Representation for Anonymizing Sensor Data [[paper](https://dl.acm.org/doi/10.1145/3450268.3453534)]

- <a name="SC"></a> SenseCollect: We Need Efficient Ways to Collect On-body Sensor-based Human Activity Data! [[paper](https://dl.acm.org/doi/10.1145/3478119)]

- <a name="SSRAC"></a> Self-supervised Learning for Reading Activity Classification [[paper](https://dl.acm.org/doi/10.1145/3478088)]

- <a name="ARW"></a> Approaching the Real-World: Supporting Activity Recognition Training with Virtual IMU Data [[paper](https://dl.acm.org/doi/10.1145/3478096)]

- <a name="RMA"></a> Reducing Muscle Activity when Playing Tremolo by Using Electrical Muscle Stimulation to Learn Efficient Motor Skills [[paper](https://dl.acm.org/doi/10.1145/3478110)]

- <a name="LORA"></a> Pushing the Limits of Long Range Wireless Sensing with LoRa [[paper](https://dl.acm.org/doi/10.1145/3478080)]

- <a name="CW"></a> CardiacWave: A mmWave-based Scheme of Non-Contact and High-Definition Heart Activity Computing [[paper](https://dl.acm.org/doi/10.1145/3478127)]

- <a name="MFL"></a> Multimodal Federated Learning [[paper](https://arxiv.org/pdf/2109.04833.pdf)]

- <a name="HARSH"></a> A Deep Learning-Based Framework for Human Activity Recognition in Smart Homes [[paper](https://www.hindawi.com/journals/misy/2021/6961343/)]

- <a name="HHH"></a> Interactive Hybrid Intelligence Systems for Human-Ai/Robot Collaboration: Improving the Practices of Physical Stroke Rehabilitation [[paper](https://www.proquest.com/openview/ba001b91ff18a4238cb6d61037ebffd0/1?cbl=18750&diss=y&pq-origsite=gscholar)]

- <a name="CAR"></a> Continual Activity Recognition with Generative Adversarial Networks [[paper](https://dl.acm.org/doi/10.1145/3440036)]

- <a name="MCNNLSTM"></a> A multibranch CNN-BiLSTM model for human activity recognition using wearable sensor data [[paper](https://link.springer.com/article/10.1007/s00371-021-02283-3)]

- <a name="SALIENCE"></a> Unsupervised User Adaptation Model for Multiple Wearable Sensors Based Human Activity Recognition [[paper](https://github.com/wdkhuans/SALIENCE)]

- <a name="CFLHAR"></a> ClusterFL: A Similarity-Aware Federated Learning System for Human Activity Recognition (**MobiSys**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3458864.3467681)]

- <a name="SLSTMS"></a> Improving Deep Learning for HAR with shallow LSTMs (**ISWC/ubicomp**) [[paper](https://arxiv.org/abs/2108.00702)]

- <a name="CPC"></a> Contrastive Predictive Coding for Human Activity Recognition (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463506)]

- <a name="LAR"></a> Leveraging Activity Recognition to Enable Protective Behavior Detection in Continuous Data (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463508)]

- <a name="WYPB"></a> Watching Your Phone's Back: Gesture Recognition by Sensing Acoustical Structure-borne Propagation (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463522)]

- <a name="ApneaDetector"></a> ApneaDetector: Detecting Sleep Apnea with Smartwatches (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463514)]

- <a name="NeckFace"></a> NeckFace: Continuously Tracking Full Facial Expressions on Neck-mounted Wearables (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463511)]

- <a name="pace"></a> We Hear Your PACE: Passive Acoustic Localization of Multiple Walking Persons (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463510)]

- <a name="mTeeth"></a> mTeeth: Identifying Brushing Teeth Surfaces Using Wrist-Worn Inertial Sensors (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3463494)]

- <a name="AFAR"></a> Acoustic-based Upper Facial Action Recognition for Smart Eyewear (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3448105)]

- <a name="tst"></a> Two-Stream Convolution Augmented Transformer for Human Activity Recognition (**AAAI2021**) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16103)]

- <a name="UNCLUSTER"></a> Unsupervised Human Activity Representation Learning with Multi-task Deep Clustering (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3448074)]

- <a name="AD4HAR"></a> Attend and Discriminate: Beyond the State-of-the-Art for Human Activity Recognition Using Wearable Sensors (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3448083)]

- <a name="AIJQHW"></a> SelfHAR: Improving Human Activity Recognition through Self-training with Unlabeled Data (**IMWUT/ubicomp**) [[paper](https://arxiv.org/abs/2102.06073)]

- <a name="LIEG"></a> Latent Independent Excitation for Generalizable Sensor-based Cross-Person Activity Recognition (**AAAI 2021**) [[paper](https://github.com/Hangwei12358/cross-person-HAR)]

- <a name="AIJQHW"></a> Weakly-Supervised Sensor-based Activity Segmentation and Recognition via Learning from Distributions (**Artificial Intelligence (AIJ)**) [[paper](http://hangwei12358.github.io/Publications/)]

### 2020

- <a name="GF"></a> GIobalFusion: A Global Attentional Deep Learning Framework for Multisensor Information Fusion (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3380999)]

- <a name="METIER"></a> METIER: A Deep Multi-Task Learning Based Activity and User Recognition Model Using Wearable Sensors (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3381012?casa_token=K86hi7pQN6IAAAAA:4rd6C-6AermBNwwe_6JoEXr-nb7AgbvWjLwfCkElg2MPomb08BV8GOpDxdEQJhwJVCY6g18r5hJiGw)]

- <a name="IWDSS4HAR"></a> Instance-Wise Dynamic Sensor Selection for Human Activity Recognition (**AAAI 2020**) [[paper](https://ojs.aaai.org//index.php/AAAI/article/view/5461)]

- <a name="CDTL"></a> Cross-Dataset Activity Recognition via Adaptive Spatial-Temporal Transfer Learning (**IMWUT/ubicomp**) [[paper](http://jd92.wang/assets/files/a20_ubicomp20.pdf)]

- <a name="MARS"></a> MARS: Mixed Virtual and Real Wearable Sensors for Human Activity Recognition with Multi-Domain Deep Learning Model [[arXiv](https://arxiv.org/abs/2009.09404)]

- <a name="TDCHAR"></a> Towards Deep Clustering of Human Activities from Wearables (**ISWC/ubicomp**) [[paper](https://arxiv.org/abs/2008.01659)]

- <a name="UDA4HAR"></a> **[UDA4HAR]** A Systematic Study of Unsupervised Domain Adaptation for Robust Human-Activity Recognition (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3380985)]

- <a name="AMNAR"></a> Adversarial Multi-view Networks for Activity Recognition (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3397323)]

- <a name="WSMT4HAR"></a> Weakly Supervised Multi-Task Representation Learning for Human Activity Analysis Using Wearables (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3397330)]

- <a name="IMUTube"></a> **[IMUTube]** IMUTube: Automatic Extraction of Virtual on-body Accelerometry from Video for Human Activity Recognition (**IMWUT/ubicomp**) [[paper](https://arxiv.org/abs/2006.05675)]

- <a name="TSMSDM"></a> Robust Unsupervised Factory Activity Recognition with Body-worn Accelerometer Using Temporal Structure of Multiple Sensor Data Motifs
 (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3411836)]
 
 - <a name="MSS"></a> Masked reconstruction based self-supervision for human activity recognition (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3410531.3414306)]
 
 - <a name="TSMSDM"></a> Digging deeper: towards a better understanding of transfer learning for human activity recognition with Body-worn Accelerometer Using Temporal Structure of Multiple Sensor Data Motifs  (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/pdf/10.1145/3410531.3414311)]
 
 - <a name="HASCA1"></a> IndRNN based long-term temporal recognition in the spatial and frequency domain  (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3410530.3414355)]
 
 - <a name="HASCA2"></a> Tackling the SHL challenge 2020 with person-specific classifiers and semi-supervised learning  (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3410530.3414848)]
 
 - <a name="HASCA3"></a> DenseNetX and GRU for the sussex-huawei locomotion-transportation recognition challenge  (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3410530.3414349)]


### 2019

- <a name="NDENNSBAR"></a> A Novel Distribution-Embedded Neural Network for Sensor-Based Activity Recognition (**IJCAI**) [[paper](https://www.ijcai.org/Proceedings/2019/0779.pdf)][[code](https://github.com/Hangwei12358/IJCAI2019_DDNN)]

- Learning Bodily and Temporal Attention in Protective Movement Behavior Detection

- <a name="AttnSense"></a> **[AttnSense]** AttnSense: Multi-level Attention Mechanism For Multimodal Human Activity Recognition (**IJCAI**) [[paper](https://www.ijcai.org/Proceedings/2019/0431.pdf)]

- <a name="MAAR"></a> Multi-agent Attentional Activity Recognition (**IJCAI**) [[paper](https://arxiv.org/pdf/1905.08948.pdf)][[code](https://github.com/KaixuanChen/Multi-agent-Attentional-Activity-Recognition)]

- <a name="DSEMI4HAR"></a> Distribution-based Semi-Supervised Learning for Activity Recognition (**AAAI**) [[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4765)][[code](https://github.com/Hangwei12358/AAAI2019_DSSL)]

- <a name="ORFHAR"></a> On the Role of Features in Human Activity Recognition (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3341163.3347727)]

- <a name="HAUHAR"></a> Handling Annotation Uncertainty in Human Activity Recognition (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3341163.3347744)]

- <a name="ALAHAR"></a> Leveraging Active Learning and Conditional Mutual Information to Minimize Data Annotation in Human Activity Recognition (**IMWUT/ubicomp**) [[paper](http://users.ece.utexas.edu/~ethomaz/papers/j6.pdf)]

<!-- - <a name="MTSSHAR"></a> Multi-task Self-Supervised Learning for Human Activity Detection (**IMWUT/ubicomp**) [[paper](https://arxiv.org/abs/1907.11879)]
 -->
- <a name="Vision2Sensor"></a> **[Vision2Sensor]** Vision2Sensor: Knowledge Transfer Across Sensing Modalities for Human Activity Recognition (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3351242)]

- <a name="HDNW"></a> How Does a Nation Walk? Interpreting Large-Scale Step Count Activity with Weekly Streak Patterns (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3328928)]

### 2018

- <a name="UIRNHAR"></a> Understanding and Improving Recurrent Networks for Human Activity Recognition by Continuous Attention (**ISWC/ubicomp**) [[paper](https://arxiv.org/abs/1810.04038)]

- <a name="OSWDHAR"></a> On specialized window lengths and detector based human activity recognition (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3267242.3267246)]

- <a name="ASCDARHAR"></a> Adding structural characteristics to distribution-based accelerometer representations for activity recognition using wearables (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3267242.3267258)]

- <a name="OAHAR"></a> On Attention Models for Human Activity Recognition (**ISWC/ubicomp**) [[paper](https://arxiv.org/abs/1805.07648)]

- <a name="AROMA"></a> **[AROMA]** AROMA: A Deep Multi-Task Learning Based Simple and Complex Human Activity Recognition Method Using Wearable Sensors (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3214277?download=true)]

### 2017

- <a name="ELSTM"></a> **[EnsemblesLSTM]** Ensembles of Deep LSTM Learners for Activity Recognition using Wearables (**IMWUT/ubicomp**) [[paper](https://arxiv.org/pdf/1703.09370.pdf)] [[Tensorflow](https://github.com/tploetz/LSTMEnsemble4HAR)]

- <a name="DL4HAR"></a> Deep Learning for Sensor-based Activity Recognition: A Survey (**Pattern Recognition Letters**) [[paper](https://arxiv.org/pdf/1707.03502.pdf)]

- <a name="ARQABSCHR"></a> Activity Recognition for Quality Assessment of Batting Shots in Cricket using a Hierarchical Representation (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3130927)]

- <a name="LPARS"></a> Label Propagation: An Unsupervised Similarity Based Method for Integrating New Sensors in Activity Recognition Systems (**IMWUT/ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/3130959)]

- <a name="CNNHAR"></a> CNN-based sensor fusion techniques for multimodal human activity recognition (**ISWC/ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/3123021.3123046)]

### 2016

- <a name="SEMIHAR"></a> Learning from less for better: semi-supervised activity recognition via shared structure discovery (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2971648.2971701)]

- <a name="WSMMHAR"></a> Wearable sensor based multimodal human activity recognition exploiting the diversity of classifier ensemble (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2971648.2971708)]

### 2015

- <a name="BYAR"></a> Beyond activity recognition: skill assessment from accelerometer data (**ubicomp**) [[paper](https://research.monash.edu/en/publications/beyond-activity-recognition-skill-assessment-from-accelerometer-d)]

- <a name="100CT"></a> I did not smoke 100 cigarettes today!: avoiding false positives in real-world activity recognition (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2750858.2804256)]

- <a name="LST"></a> Let's (not) stick together: pairwise similarity biases cross-validation in activity recognition (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2750858.2807551)]

- <a name="IAR"></a> Improved activity recognition by using enriched acceleration data (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2750858.2805844)]

- <a name="ASCACA"></a> A field study comparing approaches to collecting annotated activity data in real-world settings (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2750858.2807524)]

- <a name="PRAR"></a> Personalization revisited: a reflective approach helps people better personalize health services and motivates them to increase physical activity (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2750858.2807552)]

### 2014

- <a name="MHAULCUT"></a> MONITORING HOUSEHOLD ACTIVITIES AND USER LOCATION WITH A CHEAP, UNOBTRUSIVE THERMAL SENSOR ARRAY (**ubicomp**) [[paper](https://www.dfki.de/en/web/research/projects-and-publications/publications-overview/publication/7531/)]

- <a name="CPSN"></a> Connecting personal-scale sensing and networked community behavior to infer human activities  (**ubicomp**) [[paper](https://dl.acm.org/doi/abs/10.1145/2632048.2636094)]

- <a name="UEAREECSI"></a> Using electrodermal activity to recognize ease of engagement in children during social interactions (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2632048.2636065)]

### 2013

- <a name="FGSSPA"></a> Fine-Grained Sharing of Sensed Physical Activity: A Value Sensitive Approach  (**ubicomp**) [[paper](https://homes.cs.washington.edu/~jfogarty/publications/ubicomp2013.pdf)]

- <a name="ZSLHAR"></a> Towards zero-shot learning for human activity recognition using semantic attribute sequence model (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2493432.2493511)]

- <a name="PMPAR"></a> Personalized mobile physical activity recognition  (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2493988.2494349)]

- <a name="AHUSMGAR"></a> A Hybrid Unsupervised/Supervised Model for Group Activity Recognition (**ubicomp**) [[paper](http://www-mmde.ist.osaka-u.ac.jp/~maekawa/paper/maekawa-ISWC2013.pdf)]

- <a name="CMAPAR"></a> Confidence-based Multiclass AdaBoost for Physical Activity Monitoring (**ubicomp**) [[paper](https://www.researchgate.net/publication/257820467_Confidence-based_Multiclass_AdaBoost_for_Physical_Activity_Monitoring)]

- <a name="AEOCAR"></a> An exploration with online complex activity recognition using cellphone accelerometer  (**ubicomp**) [[paper](https://www.researchgate.net/publication/262159302_An_exploration_with_online_complex_activity_recognition_using_cellphone_accelerometer)]

- <a name="UniPad"></a> [**UniPad**] UniPad: Orchestrating collaborative activities through shared tablets and an integrated wall display  (**ubicomp**) [[paper](https://uclic.ucl.ac.uk/publications/912121)]

- <a name="HARUHS"></a> Human Activity Recognition Using Heterogeneous Sensors  (**ubicomp**) [[paper](http://ubicomp.org/ubicomp2013/dc/shoaib-jr-ds-crc.pdf)]

- <a name="POFMHAR"></a> A probabilistic ontological framework for the recognition of multilevel human activities  (**ubicomp**) [[paper](https://dl.acm.org/doi/10.1145/2493432.2493501)]

- <a name="USMLDA"></a> Ubiquitous support for midwives to leverage daily activities  (**ubicomp**) [[paper](https://www.researchgate.net/publication/262366613_Ubiquitous_support_for_midwives_to_leverage_daily_activities)]

- <a name="CEACVRFPA"></a> Combining Embedded Accelerometers with Computer Vision for Recognizing Food Preparation Activities  (**ubicomp**) [[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.371.8684&rep=rep1&type=pdf)]


### 2012

- <a name="ASOA"></a> A Spark Of Activity: Exploring Information Art As Visualization For Physical Activity  (**ubicomp**) [[paper](https://www.researchgate.net/publication/262176140_A_spark_of_activity_Exploring_informative_art_as_visualization_for_physical_activity)]

- <a name="BodyScope"></a> **[BodyScope]** BodyScope: A Wearable Acoustic Sensor for Activity Recognition (**ubicomp**) [[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2012/09/Ubicomp2012.pdf)]

- <a name="AIF4HAR"></a> An Integrated Framework for Human Activity Classification (**ubicomp**) [[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.2178&rep=rep1&type=pdf)]

### 2011

- <a name="TPUCS"></a> The Place for Ubiquitous Computing in Schools: Lessons Learned from a School-Based Intervention for Youth Physical Activity  (**ubicomp**) [[paper](https://www.andrewmiller.net/pdf/2011_Poole.pdf)]

- <a name="CSN"></a> **[CSN]** Enabling Large-scale Human Activity Inference on Smartphones using Community Similarity Networks  (**ubicomp**) [[paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.724.3380&rep=rep1&type=pdf)]

### 2010

- <a name="UWATDIPAE"></a> Using Wearable Activity Type Detection to Improve Physical Activity Energy Expenditure Estimation (**ubicomp**) [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6122605/)]
