This is the repository to save the recent new literatures collected, skimmed, and read, to keep up with pace of the-state-of-the art works.

# Contents:
- [2023-02-16 ](#2023-02-16)
- [2023-02-17 ](#2023-02-17)
- [2023-02-18 ](#2023-02-18)


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
