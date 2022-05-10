
<h1 align="center">Explainable Anomaly Detection System for Categorical Sensor Data in Internet of Things</h1>
<p align="center">
Peng Yuan<sup>1</sup>, Lu-An Tang<sup>1</sup>, Haifeng Chen<sup>1</sup>, Moto Sato<sup>1</sup>, and Kevin Woodward<sup>2</sup>
</p>

<p align="center">
<sup>1</sup> NEC Labs America, Princeton, NJ, USA
</p>
<p align="center">
<sup>2</sup> Lockheed Martin Space, Denver, CO, USA
</p>
       
           
## Abstract
Internet-of-thing (IoT) applications deploy massive number of sensors to monitor the system and environment. Anomaly detection on streaming sensor data is an important task for IoT maintenance and operation. However, there are two major problems for anomaly detection in real IoT applications: (1) many sensors report categorical values rather than numerical readings; (2) end users require more knowledge and explanations to understand the anomalies and take actions. Unfortunately, most existing works cannot satisfy such requirements. To bridge the gap, we design and develop an eXplainable Anomaly Detection System (XADS) for categorical sensor data. XADS trains models from historical normal data and conducts online monitoring. XADS detects the anomalies in an explainable way: the system will not only report the anomalies' time period, type, value details, but also provide explanations on why they are abnormal, and what should the normal data like. Such information will significantly help the end user making decision and taking actions. XADS requires very limit parameter setting, yields high accuracy on detection results and comes with user-friendly interface, making it an efficient and effective tool for monitoring a wide variety of IoT applications.

## XADS Demo for ECML PKDD 2022:
[![Video](https://github.com/pengyuan0106/eXplainable-Anomaly-Detection-System/blob/main/frame.jpg)](https://youtu.be/TOZoA7dprGk)

