This is the repository to save the recent new literatures collected, skimmed, and read, to keep up with pace of the-state-of-the art works.

# Contents:
- [2023-02-16](#2023-02-16)
- [2023-02-17](#2023-02-17)
- [2023-02-18](#2023-02-18)
- ...
- [2023-02-22](#2023-02-22)
- [2023-02-23](#2023-02-23)
- [2023-02-24](#2023-02-24)
- [2023-02-25](#2023-02-25)
- [2023-02-26](#2023-02-26)
- ...
- [2023-03-01](#2023-03-01)

## 2023-02-16  
**Journal paper**: [Deeper Fine-Tuned Autoencoder for User Datagram Protocol Flooding
Network Traffic Detection in Internet of Things](https://assets.researchsquare.com/files/rs-2442056/v1/2e9544e4-f9c6-439e-85ca-ba8cab820ecf.pdf?c=1675440862), Ömer KASIM (  omerksm@gmail.com ), Kutahya Dumlupinar University: Kutahya Dumlupinar Universitesi https://orcid.org/0000-0003-4021-5412
- Idea: prefer **deeper model** for higher performance rather than shallow models, proposed a classification with high accuracy and performance can be performed by encoding the selected features deeper
- Datasets: N-BaIoT and NSL-KDD
- Attacks: **botnet** is User Datagram Protocol (UDP) flooding
- Model: Fine Tuned **Stacked Autoencoder**
- Result: Experiments in the study showed that the number of optimally selected features was significantly reduced, resulting in the lowest detection time. The accuracy, sensitivity, Cohen kappa, specificity and f1 score of the proposed model were quite high

**Conference paper**: [Attack Detection in IoT Using Machine Learning—A Survey](https://link-springer-com.ezproxy.utm.my/chapter/10.1007/978-3-031-18497-0_16)  , Saeed Ali Haifa Ali & J. Vakula Rani Conference paper First Online: 04 February 2023, [Intelligent Cyber Physical Systems and Internet of Things ICoICI 2022](https://link-springer-com.ezproxy.utm.my/book/10.1007/978-3-031-18497-0)
- Idea: The goal of this paper is to provide a study on the attacks in IoT architectures such as the sensing layer, network layer, and application layer, then present ML and DL that contributed to the solution in attack detection. In addition, we discuss the challenges of IoT architectures.

**A book**: [Internet of Things - New Trends, Challenges and Hurdles](https://www.intechopen.com/books/11197), by Manuel Domínguez-Morales, Ángel Varela-Vaca and Lourdes Miró-Amarante, Submitted: November 8th, 2022 Published: February 8th, 2023
DOI: 10.5772/intechopen.108960
- Idea: Written by leading experts in the field, this book serves as a showcase of the breadth of IoT research conducted in recent years for people who, while not experts in the field, do have prior knowledge of the IoT. The book also serves curious, non-technical readers, enabling them to understand necessary concepts and terminologies associated with the IoT.
- Audience: for how do have prior knowledge of the IoT


## 2023-02-17  
**Journal paper**: [Addressing the class imbalance problem in network intrusion detection systems using data resampling and deep learning
](https://link-springer-com.ezproxy.utm.my/article/10.1007/s11227-023-05073-x), Ahmed Abdelkhalek & Maggie Mashaly The Journal of Supercomputing (2023)
- Idea: In this paper, a data resampling technique is proposed based on **Adaptive Synthetic (ADASYN) and Tomek Links algorithms in combination with different deep learning models** to mitigate the **class imbalance problem**.
- Keyword: Imbalance class
- Datasets: NSL-KDD
- Models: ML, DNN, CNN and CNN-BLSTM models
- Classification: both binary and multi-classification
- Result: The experimental results show that in binary classification, the proposed method improves the performance of the NIDS and outperforms state-of-the-art models with an achieved accuracy of 99.8%. In multi-class classification, the results were also improved, outperforming state-of-the-art models with an achieved accuracy of 99.98%.

**Journal paper**: [NEW NEURAL NETWORK-BASED INTRUSION DETECTION SYSTEM DESIGN BY
USING BAT AND ANT COLONY ALGORITHMS](https://www.researchgate.net/profile/Ouail-Mjahed-2/publication/368390590_New_Neural_Network-Based_Intrusion_Detection_System_Design_by_Using_Bat_and_Ant_Colony_Algorithms/links/63e578c0dea6121757976646/New-Neural-Network-Based-Intrusion-Detection-System-Design-by-Using-Bat-and-Ant-Colony-Algorithms.pdf), Ouail MJAHED et al. 2023
- Keyword: Hybridization of metha-heuristic algorithms
- Idea: **Hybridization of two metha-heuristic algorithms**, involving Ant Colony Optimization (ACO) and Bat Algorithm (BA), to imporve a Back-propagation Neural Network (BPNN) adopted, and to reduce neurons and layers of the NN model.
- Datasets: CICIDS2017 dataset
- Models: NN model
- Result: ACO- and BA-based NNs (referred to as ACONN and BANN, respectively) can achieve favourable performances. ACONN produces a tested efficiency, purity and F1 score of 98.91 %, 99.17 % and 99.04 %, respectively, versus 96.04 %, 96.13 % and 96.09 %, respectively, for BPNN.

**Journal paper**: [Explainable AI-Based DDOS Attack Identification Method for IoT Networks](https://www.mdpi.com/2073-431X/12/2/32), by Chathuranga Sampath Kalutharage 2023
- Keyword: Explainable AI
- Idea: we propose an **explainable artificial intelligence (XAI)-based novel method** to identify DDoS attacks. This DDoS attack detection method defines security policies based on each feature threshold value for **application-layer-based, volumetric-based, and transport control protocol (TCP) state-exhaustion-based features**.
- Datasets: USB-IDS
- Attacks: DDoS attacks
- Models: A fully connected autoencoder model with RELU enabled
- Result: The results of the comparison show that the proposed method provides greater detection accuracy and attack certainty than the state-of-the-art methods.

**Journal paper**: [A deep learning approach for intrusion detection in Internet of Things using focal loss function](https://www-sciencedirect-com.ezproxy.utm.my/science/article/pii/S2542660523000227), by Ayesha S. Dina 2023
- Keyword: focal loss function, imbalance problem
- Idea: we leverage the specialized loss function, called **focal loss**, that automatically down-weighs easy examples and focuses on the hard negatives by facilitating dynamically scaled-gradient updates for training effective ML models.
- Datasets: Bot-IoT, WuSt-IIoT-2021, and WuSt-EHMS-2020
- Attacks: normal/attacks
- Models: FNN, CNN
- Result: (CNN-Focal) performed better with respect to accuracy, precision, F1 score and MCC score by as much as 24%, 39%, 39%, and 60%, respectively, compared to baseline model CNN-ORG over the Bot-IoT dataset. Its performance was also much better than some of the state-of-the art approaches that we compared.

## 2023-02-18  
**Journal paper**: [A deep learning approach for intrusion detection in Internet of Things using focal loss function](https://www.mdpi.com/2079-9292/12/4/930), by Chao Wang, Electronics 2023, 12(4), 930;
- Keyword: **Semi-supervised learning**, Feature extraction, two-stage detectors
- Idea: Semi-supervised anomaly detection algorithms for the cases with no attack labels, combined with two stage detectors. To be specific, the autoencoder (AE) is applied to extract representative features of normal data in the first step, and then two semi-supervised detectors, the **one-class support vector machine (OCSVM)** and **Gaussian mixture model (GMM)**, are trained on the derived features. The two detectors collaborate to detect anomalous samples. The OCSVM predicts the abnormal samples initially, and after that, the GMM is applied to recheck the misclassified samples further.
- Datasets: Bot-IoT and IDS2018
- Attacks: normal/attacks
- Models: autoencoder (AE) for extracting representative features, OCSVM and GMM as the detectors to detect anormal cases.
- Result: The results of the experiment indicate the effectiveness of the suggested approach. In one part, the AE boosts the performance of detectors. In another part, the combination method produces better results than a single detector.

**Journal paper**: [Threats Detection in the Internet of Things Using Convolutional neural networks, long short-term memory, and gated recurrent units](https://www.researchgate.net/profile/Mohammad-Aljanabi/publication/368309410_Threats_Detection_in_the_Internet_of_Things_Using_Convolutional_neural_networks_long_short-term_memory_and_gated_recurrent_units/links/63e23f80f8cf684fe9760bb0/Threats-Detection-in-the-Internet-of-Things-Using-Convolutional-neural-networks-long-short-term-memory-and-gated-recurrent-units.pdf), by Naomi A. Bajao, © 2023 The Authors. Published by Mesopotamian Academic Press
- Keyword:  Convolutional neural networks (CNNs), long shortterm memory (LSTM), and gated recurrent units (GRUs)
- Idea: Comparison on three deep learning algorithms.
interruption location techniques that utilise them.
- Datasets: NSL-KDD

**Journal paper**: [A two-stage intrusion detection method based on light gradient boosting machine and autoencoder](https://www.aimspress.com/article/doi/10.3934/mbe.2023301), by Hao Zhang et al., Mathematical Biosciences and Engineering, 2023, Volume 20, Issue 4: 6966-6992. doi: 10.3934/mbe.2023301
- Keyword: RFE, Focal loss, LightGBM, autoencoder
- Challenges: dimensionality, zero-day attack
- Idea: Two-stage detectors. This paper proposes a novel detection framework based on light gradient boosting machine (LightGBM) and autoencoder.
- Methodology: The **recursive feature elimination (RFE) method** is first used for dimensionality reduction in this framework. Then a **focal loss (FL) function** is introduced into the LightGBM classifier to boost the learning of difficult samples. Finally, a two-stage prediction step with LightGBM and autoencoder is performed. In the first stage, pre-decision is conducted with LightGBM. In the second stage, a residual is used to make a secondary decision for samples with a normal class.
- Datasets: NSL-KDD and UNSWNB15
- Future work: In future work, we will mainly focus on two aspects: First, since the threshold of the autoencoder is the key factor affecting the model, we will develop a method to set the threshold automatically. Second, we segment the attack types and adopt a suitable sampling method to further improve the model performance.

**Journal paper**: [A new deep-learning with swarm based feature selection for intelligent intrusion detection for the Internet of things](https://www-sciencedirect-com.ezproxy.utm.my/science/article/pii/S2665917423000363), by R. Anushiya 2023, Measurement: Sensors, Available online 13 February 2023, 100700
- Keyword: GA, FSO, CNN
- Idea: GA-FR-CNN (Genetic Algorithm and Faster Recurrent Convolution Neural Network), a brand-new feature selection method for IDSs, Network dataset's complexities are greatly reduced and the usage of **AAFSO (Assimilated Artificial Fish Swarm Optimization)** method to improve recommended systems assisted in identifying characteristics that were important to the problem.
- Datasets: Bot-IoT
- Attacks: 
- Models: 
- Result: 


## 2023-02-22
[A Survey: Network Feature Measurement Based on Machine Learning](https://www.mdpi.com/2076-3417/13/4/2551) by Muyi Sun et al., Appl. Sci. 2023, 13(4), 2551; https://doi.org/10.3390/app13042551
- Keyword: network management, machine learning
- Idea: ML applications in the field of network measurement

[Anomaly based network intrusion detection for IoT attacks using deep learning technique](https://www-sciencedirect.com.ezproxy.utm.my/science/article/pii/S0045790623000514)by Bhawana Sharma, Computers and Electrical Engineering Volume 107, April 2023, 108626
- Keyword: Feature selection by DNN, various tuning on hyper parameters, GAN for class imbalance
- Idea: **a filter-based feature selection Deep Neural Network (DNN)** model where highly correlated features are dropped has been presented, further, the model is **tuned with various parameters and hyper parameters**, **Generative Adversarial Networks (GANs)** were used to generate synthetic data of minority attacks to resolve class imbalance issues in the dataset and achieved 91% accuracy with balanced class dataset.
- Datasets: UNSW-NB15

[Android-IoT Malware Classification and Detection Approach Using Deep URL Features Analysis](https://www.igi-global.com/article/android-iot-malware-classification-and-detection-approach-using-deep-url-features-analysis/318414) by Farhan Ullah et al, Journal of Database Management (JDM) 34(2)
- Idea: Malware classification on encrypt application traffic with URL

[A NOVEL APPROACH FOR A NEW MECHANISM IN NETWORK INTRUSION DETECTION SYSTEM ](https://www.journal-dogorangsang.in/no_1_Online_23/16_feb.pdf) by PACHIPULUSU RENUKA DEVI et al., Dogo Rangsang Research Journal 2023
- Keyword: ANN, SVM, wrapper feature selection
- Idea: comparison between ANN and SVM with wrapper FS, and ANN outperformed SVM.
- Datasets: NSL-KDD

[CSK-CNN: Network Intrusion Detection Model Based on Two-Layer Convolution Neural Network for Handling Imbalanced Dataset](https://www.mdpi.com/2078-2489/14/2/130) by Jiaming Song et al., Information 2023, 14(2), 130; https://doi.org/10.3390/info14020130
- Problem: The performance of classifier is not very good in identifying abnormal traffic for **minority classes**.
- Keyword: minority classes, two-layer classifier, 
- Idea: CSK combines the cluster based Synthetic Minority Over Sampling Technique (Cluster-SMOTE) and K-means based under sampling algorithm. Through the **two-layer network**, abnormal traffic can not only be identified, but also be classified into **specific attack types**.
- Datasets: UNSW-NB15 and CICIDS2017
- Attacks: layer1 for abnormal, layer2 for specific attacks
- Metrics: accuracy, recall, precision, F1-score, ROC curve, AUC value, training time and testing time
- Results: The experiment shows that the proposed CSK-CNN in this paper is obviously superior to other comparison algorithms in terms of network intrusion detection performance, and is suitable for deployment in the real network environment.

## 2023-02-23
[An Ensemble Tree-Based Model for Intrusion Detection in Industrial Internet of Things Networks](https://scholar.google.com.au/scholar_url?url=https://www.mdpi.com/2076-3417/13/4/2479/pdf&hl=en&sa=X&d=14855942219278156803&ei=CM3wY8PjNseAywSTq47oAQ&scisig=AAGBfm2y88blA2jA4xBUbxDfQSWkTIVV6w&oi=scholaralrt&hist=dxijuU4AAAAJ:12171303415466890748:AAGBfm1CvZn-d7F9Q_WvAc3ggjulOSp6jg&html=&pos=0&folt=cit) by JB Awotunde et al., Applied Science, 2023
- Problem: the requisite machine learning models **require some time** to detect assaults because of **the diverse IIoT network traffic properties**.
- Keyword: ensemble models, feature selection, IIoT
- Idea: this study proposes **ensemble models** enabled with a **feature selection** classifier for Intrusion Detection in the IIoT network.
- Methodology: The **Chi-Square Statistical method** was used for feature selection, and various ensemble classifiers, such as **eXtreme gradient boosting (XGBoost), Bagging, extra trees (ET), random forest (RF), and AdaBoost** can be used for the detection of intrusion applied to the Telemetry data of the TON_IoT datasets.
- Datasets: Telemetry dataset of ToN_IoT datasets
- Classification: binary and multi-classification
- Metrics: accuracy, recall, precision, F1-score, and confusion matrix
- Results: The results indicate that the **XGBoost ensemble showed superior performance** with the highest accuracy over other models across the datasets in detecting and classifying IIoT attacks.
- Limitations: One of the major limitations of the proposed model is **the inability to deal with the class imbalance** that arises from the datasets used to test the performance of the proposed model.
- Future directions: 1. make use of **imbalanced algorithms** to balance the dataset. 2. focus on applying **deep learning models to optimize their hyper-parameters** to improve the dataset classification performance for the IDS. 3. The proposed model will be applied to **other IIoT-based datasets**.

## 2023-02-24
[Flow-based intrusion detection system in Vehicular Ad hoc Network using context-aware feature extraction](https://www-sciencedirect-com.ezproxy.utm.my/science/article/pii/S2214209623000153) by Erfan A. Shams et al., 2023 Vehicular Communications
- Problem: The safety that is provided by VANETs can be easily compromised by malicious users. Hence there is a need for an Intrusion Detection System (IDS).
- Keyword: Vehicular Ad hoc Network (VANET), IDS, CNN, 
- Idea: We designed an IDS model that can collect network data cooperatively from vehicles and Roadside Units (RSUs).
- Methodology: employed a **multi-class IDS** using **Convolutional Neural Network (CNN)** with a novel feature extraction method known as **Context-Aware Feature Extraction-Based CNN (CAFECNN)**
- Results: The results show that the proposed model is stronger in identification of **hard-to-detect passive attacks** compared to traditional machine learning methods. 
- Future directions: work on the **feature extraction method** to ensure that it can unify the most popular network data collection methods into a single format that can be employed for developing or extending the capability of existing IDS models **without the need to restructure the entire system**. This includes applying the system to other types of networks such as wireless sensor networks.

[A Machine Learning-Based Intrusion Detection System for IoT Electric Vehicle Charging Stations (EVCSs)](https://www.mdpi.com/2079-9292/12/4/1044)
- Problem: The risks associated with cyber-attacks on IoT systems are also increasing at the same pace.
- Keyword: electric vehicle charging station management systems (EVCSMSs), IDS, IoT, machine learning
- Idea: **IDS using machine learning models applied on EVCS industry.**
- Methodology: The proposed system uses a real IoT dataset derived from real IoT traffic. Multiple classifying algorithms are evaluated. Results were obtained on both binary and multiclass traffic models.
- Datasets: IoT-23
- Classification: binary and multi-classification
- Metrics: precision, recall, and F-1 score
- Limitations: Did not use DLs, building model offline, just use IoT-23 dataset and will try real data from EVC, also other datasets.
- Results: The proposed algorithm can also be applied to any **critical industrial control system (ICS)**, such as **SCADA systems** and **green hydrogen control systems**, to enhance their security resilience as they were originally built without taking security into consideration.
- Limitations: One of the major limitations of the proposed model is **the inability to deal with the class imbalance** that arises from the datasets used to test the performance of the proposed model.
- Future directions: 1. build a **dedicated dataset for EVCSs**. 2. find the **minimum amount of data** to be used in training while preserving the same accuracy level 3. measuring the **impact of feature selection** and consider **new methodological steps to developing deep learning models**.

[Intrusion detection model of Internet of Things based on LightGBM](https://www.jstage.jst.go.jp/article/transcom/advpub/0/advpub_2022EBP3169/_pdf) by Guosheng Zhao et al., 2023 IEICE Transactions on Communications
- Problem: Traditional intrusion detection systems (IDS) focus on high accuracy and low false alarm rate (FAR), making them often have **too high spatiotemporal complexity** to be deployed in IoT devices.
- Keyword: CNN, LightGBM, IDS, IoT
- Idea: an intrusion detection model of IoT based on the **light gradient boosting machine (LightGBM)**
- Methodology: The proposed method was evaluated using the NSL-KDD dataset (KDD TEST PLUS and KDD TEST21) for validation and testing. Many efficient features were selected using an enhanced technique, namely, the **particle swarm optimization**. The selected features serve for effective classification using **an enhanced LSTM framework**, where it is used to efficiently classify and detect the attack data from the normal data.
- Datasets: NSL-KDD, UNSW-NB15, CICIDS2017, CSE-CIC-IDS2018, and BOT _DATASET
- Classification: binary and multi-classification
- Metrics: accuracy, precision, recall, and error rate
- Results: Results show that **the training time** of the proposed system is much less than that of other methods for different classes. Finally, the performance of the proposed ELSTM-RNN framework is analyzed using various metrics, such as accuracy, precision, recall, and error rate. Our proposed method outperformed LPBoost and DNNs methods.
- Future directions: The use of XAI algorithms to interpret and develop the provided PSO-driven strategy, 

[Optimization of Intrusion Detection Using Likely Point PSO and Enhanced LSTM-RNN Hybrid Technique in Communication Networks](https://ieeexplore-ieee-org.ezproxy.utm.my/stamp/stamp.jsp?arnumber=10026342) by AHMED ABD EL-BASET DONKOL et al., 2023
- Problem: inefficient against new/distinct attacks, IDS has various problems involving gradient vanishing, generalization, and overfitting issues.
- Idea: **the enhanced long-short term memory (ELSTM) technique** with **recurrent neural network (RNN)** (ELSTM-RNN) to enhance security in IDS


## 2023-02-25
[Anomaly Detection In IoT Networks Using Hybrid Method Based On PCA-XGBoost](https://ieeexplore-ieee-org.ezproxy.utm.my/abstract/document/10043986) by Ali Taghavirashidizadeh et al., 2022 8th Iranian Conference on Signal Processing and Intelligent Systems (ICSPIS)
- Problem: With the increasing use of IoT infrastructure in various fields, threats and attacks on these infrastructures are also growing. 
- Keyword: anomaly detection; Intrusion Detection; internet of things; principal component analysis; XGBoost.
- Idea: combining feature dimensionality reduction and machine learning methods
- Methodology: a method based on a combination of **Principal Component Analysis (PCA)** and **XGBoost algorithms** for anomaly detection in IoT was presented
- Datasets: UNSW-NB15
- Classification: binary classification
- Metrics: accuracy, precision, recall, and f1-score
- Results: the performance of PCA-XGBoost outperformed other ML methods, involving DT, KNN, SVM, LR
- Future directions: we can also focus on identifying **the type of attack**. In addition to the XGBoost algorithm, **metaheuristic algorithms** can also be used to reduce more efficient features. **Deep learning algorithms** can also be used for classification.
- My comments: relatively simple method without enough explanation, but can be a way to start experiment.

## 2023-02-26
[Hybrid Intrusion Detection System Based on Combination of Random Forest and Autoencoder](https://www.mdpi.com/2073-8994/15/3/568) by Chao Wang et al., 2023, symmetry, MDPI
- Problem: difficult to deal with unknown attacks, high false positive rate
- Keyword: intrusion detection; random forest; autoencoder; hybrid model; unknown attack
- Idea: As different models learn data characteristics from different perspectives, in this work we propose a hybrid IDS which leverages both random forest (RF) and autoencoder (AE).
- Methodology: The hybrid model operates in two steps. In particular, in the first step, we utilize the probability output of the RF classifier to determine whether a sample belongs to attack. The unknown attacks can be identified with the assistance of the probability output. In the second step, an additional AE is coupled to reduce the false positive rate. To simulate an unknown attack in experiments, we explicitly remove some samples belonging to one attack class from the training set.
- Datasets: IDS2018, BOT-IOT
- Classification: binary classification
- Metrics: accuracy, precision, recall, f1-score, and FAR
- Results: The experimental results prove that the combina- tion method boosts the detection rate and reduces the FPR in comparison to the single detection methods.
- Future directions: Only one type of attack was set as the unknown during the experiments; it is important to set **more than one type of attack** as the unknown to test the model. We plan to expand the method into a **multi-class approach** to provide more diagnostic information for security operators in the future.
- My comments: an approach on handling unknown attack, and reducing false positive rate.

## 2023-03-01
Survey: [A Deep Learning and Optimization Method for Detecting Network Intrusion in IOT](https://ieeexplore-ieee-org.ezproxy.utm.my/abstract/document/10047140) by Rekha Gangula et al., 2022 Second International Conference on Advanced Technologies in Intelligent Control, Environment, Computing and Communication Engineering ICATIECE
- Problem: Researchers and engineers must be able to interpret the complicated structure from imprecise information, recognize the dynamic anomaly patterns, and find anomalies when there aren't enough labels to describe them. As a result, using deep learning techniques rather than conventional shallow learning methods is necessary to improve anomalous detection capability.
- Keyword: intrusion detection, neural networks, optimization, Internet of things, accuracy, false alarm rate.
- Idea: DL vs traditional shallow ML on IDS in IoT
- Methodology: This article offers a survey on anomalous intrusion detection using deep learning techniques, with a focus on IoT devices utilized in real-world issues that have limited resources.
- Metrics: accuracy, precision, recall, f1-score, and FAR
- Results: The results of the research that were evaluated demonstrated that deep learning is better to traditional learning when it comes to high identification efficiency and low rate of false alarms. 
- Future directions: how to manage amount of alerts, how to handle useless info for deep learning, constant updated model in IoT for unknown attacks, further investigation on IDS and blockchain.
- My comments: seems like a follow-up topic on DL on IDS IoT and a quick survey paper.

[ADCL: Towards An Adaptive Network Intrusion Detection System Using Collaborative Learning in IoT Networks](https://ieeexplore-ieee-org.ezproxy.utm.my/abstract/document/10050513)
- Problem:  it is well-known that the NIDS performance depends heavily on the effectiveness of detection model, which can be influenced significantly by the learning mechanism and the available training data. Many existing studies try to mitigate the above challenges, but few of them consider the adaptability and the cost of deploying an NIDS, the integrity of learning process, the capacity of model based on concrete traffic samples at the same time.
- Keyword: Intrusion Detection, System Adaptability, Collaborative Learning, Multiple Model, Internet of Things
- Idea: propose a **collaborative learning** based detection framework called ADCL, which can mitigate the limitations on the knowledge of a single model by **leveraging multiple models trained in similar environments and detecting intrusions in a collaborative manner**.
- Results: Our evaluation results indicate that ADCL can provide better performance compared with a single model on detecting various attacks in IoT networks. Specifically, ADCL improves F-score by up to 80% for adaptability, 42% in mitigating the reliance on learning integrity, 85% for model capacity. Furthermore, the detection results of ADCL guide those single models to update and increase the F-score by 15%.
- Future directions: 
- My comments: A model selection mechanism with mulitple models tranined, using suitable detector for attack detection.
