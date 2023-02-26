# HerIoT: Learning Generalisable Attack Detection Models from Heterogeneous Public IoT Datasets

# Overview
In this repository you will find a Python implementation of the methods in the paper HerIoT: Learning Generalisable Attack Detection Models from Heterogeneous Public IoT Datasets.

[link of artickle](https://kahramankostas.github.io/)


# What is HerIoT?

The Internet of Things is becoming more and more involved in our daily lives. In parallel with this, IoT is the target of many cyber attacks. Due to IoT's heterogeneous nature and unusual interfaces, the solutions used in classical instruments may not be suitable. This paper proposes a generalisable intrusion detection model based on machine learning. While building this model, we propose a sliding and expanding window-oriented feature set that can detect attacks earlier and with higher performance. We also compare our method with alternatives. In the feature selection phase, we use a genetic algorithm based on external feedback to generate the optimal feature set combination. In order to demonstrate the generalisability of our results, we present our results by comparing the models we have developed with isolated attack data.

# Requirements and Infrastructure: 

Wireshark and Python 3.6 were used to create the application files. Before running the files, it must be ensured that [Wireshark](https://www.wireshark.org/), [Python 3.6+](https://www.python.org/downloads/) and the following libraries are installed.

| Library | Task |
| ------ | ------ |
|[ Scapy ](https://scapy.net/)| Packet(Pcap) crafting |
|[ tshark ](https://www.wireshark.org/)| Packet(Pcap) crafting |
|[ Sklearn ](http://scikit-learn.org/stable/install.html)| Machine Learning & Data Preparation |
| [ Numpy ](http://www.numpy.org/) |Mathematical Operations|
| [ Pandas  ](https://pandas.pydata.org/pandas-docs/stable/install.html)|  Data Analysis|
| [ Matplotlib ](https://matplotlib.org/users/installing.html) |Graphics and Visuality|
| [Seaborn ](https://seaborn.pydata.org/) |Graphics and Visuality|




The technical specifications of the computer used for experiments are given below.

|  | |   |
| ------ |--|  ------ |
|Central Processing Unit|:|Intel(R) Core(TM) i7-7500U CPU @ 2.70GHz 2.90 GHz|
| Random Access Memory	|:|	8 GB (7.74 GB usable)|
| Operating System	|:|	Windows 10 Pro 64-bit |
| Graphics Processing Unit	|:|	AMD Readon (TM) 530|

# Implementation: 

The implementation phase consists of 5 steps, which are:

* Feature Extraction
* Feature Selection 
* Algorithm Selection 
* Performance Evaluation
* Comparison with Previous Work


Each of these steps is implemented using one or more Python files. The same file was saved with both "py" and "ipynb" extensions. The code they contain is exactly the same. The file with the ipynb extension has the advantage of saving the state of the last run of that file and the screen output. Thus, screen output can be seen without re-running the files. Files with the ipynb extension can be run using [jupyter notebook](http://jupyter.org/install). 

## Datasets
The datasets we used in our study are listed below.

| Dataset | capture year | Number of Devices | Number of Attacks  |
|---|---|---|---|
|[CIC-IoT-2022](https://www.unb.ca/cic/datasets/iotdataset-2022.html)| 2022|40|4|
|[BoT-IoT](https://research.unsw.edu.au/projects/bot-iot-dataset)| 2018|5|10|
|[Edge-IIoT](https://ieee-dataport.org/documents/edge-iiotset-new-comprehensive-realistic-cyber-security-dataset-iot-and-iiot-applications)| 2022|9|13|
|[IoT-ENV](https://ocslab.hksecurity.net/Datasets/iot-environment-dataset)| 2021|5|3|
|[IoT-NID](https://ocslab.hksecurity.net/Datasets/iot-network-intrusion-dataset)|2019|2|10|
|[Kitsune](https://www.kaggle.com/datasets/ymirsky/network-attack-dataset-kitsune)| 2019|9|9|
|[MazeBolt](https://kb.mazebolt.com/kbe_taxonomy/ddos-general/)|NA|NA|NA|






We used these datasets for different purposes at different stages of our study. Table 1 indicates which part of the dataset and for what purpose it was used in our study.




![Datasets](./imgs/datasets.svg)
<p style="text-align: center;">Table 1 - The datasets used in the study and their usage purposes.</p>


## 1- Feature Extraction (PCAP2CSV) 

### 1.1- Individual and Window based Features
This section uses the *pcap2csv* tool to extract features from pcap files. Packet-level labels are required for labelling. Some datasets have packet-based labels (such as Kitsune). If you have labels, save them with the same name as the pcap file (such as example.pcap & example.csv). The *pcap2csv* file will transfer the labels to *CSV* during the feature extraction process. 

If you do not have packet-level labels, the LabelMaker file will generate them from the *pcap* file. To do this, simply add the [WireShark](https://www.wireshark.org/) rules for identifying attacks to the "dataset_description.csv" file (see Fig.1).


![Alt text](./imgs/tshark.svg)
<p style="text-align: center;">Fig. 1 - Pcap file labelling with LabelMaker</p>



### 1.2- Flow-based features

For flow-based feature extraction, we used [CICFlowMeterV3](https://www.unb.ca/cic/research/applications.html), a tool that quickly converts pcap files into flow-based features (CSV files). For labelling, most of the databases provide their own labelled CSV files. You can use these labels. We have used a python script to import the labels of some datasets into these files. You can find a few examples of how we did this in the *FLOW-LABELLER.ipynb* file.

 


-------------------------------------------------------------------------------------------------------------------------------------------------------
I WILL ADD MORE

