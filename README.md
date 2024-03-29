# Hybrid Attention Multi-modal learning for Percieved Mental workload Classification
The level of measured mental effort exerted by an individual in response to one or more cognitive tasks is referred to as cognitive workload. It reflects the quantity of mental resources necessary to complete a collection of concurrent tasks.
In past, The classification of PMWL has been attempted in a unimodal setting using various physiological signals, such as such as pupil diameter,eeg, functional near-infrared spectroscopy , galvanic skin response  and heart rate (HR), through photoplethysmography. All the aforementioned modalities have individually proven to be useful for the classification of PMWL. However,  no one sensor can give a complete view of how someone is reacting to a task. In a sense, this makes mental workload the quintessential use case for multimodal biosensors. The focus of this work is on quantifying perceived mental workload (PMWL) using measures based on Hybrid Attention Architecture using convolution-lstm self attention modeling with bi-modal fusion.

The biosignals employed are Functional Near-Infrared Spectroscopy(fNIRS), Eye tracking(ET) and photoplethysmography(PPG) and galvanic skin response(GSR). Relative changes in brain (de)oxyhaemoglobin concentrations can be assessed with fNIRS. Energy use and haemoglobin distribution vary during brain function activation (Villringer et al., 1993).PPG is an optical method for determining blood volume changes in microvascular tissues, which is directly linked to cardiac activity (Selvaraj et al., 2008).GSR is an electrodermal response linked with sympathetic nervous system innervation that is frequently used to assess affective and cognitive arousal. As a result, it may be used to calculate measurements like HR variability and inter-beat intervals as well as measure HR. (Venables and Christie, 1980). ET is used to learn where a person is looking at any given time, which can help researchers better understand how visual and display-based information is processed (Poole and Ball, 2006). 
 

The results demonstrate the applicability of brain-computer interface using multimodal biosignals  and  attention networks for quantifying cognitive load in well-validated problem-solving tasks. These quantitative cognitive load metrics could help with the design of domains that require real-time problem solving, such as e-learning, psychometric examinations, military training, and more.

# Pipeline

The model uses convolution and recurrent neural network based multi-modal hybrid attention framework that leverages the contextual information through biosignals data. The proposed approach firstly models each modality through LSTM and Convolution based self attention and then applies bi-modal attention on pairwise modalities and tries to learn the contributing features amongst them.

Model : 

![alt.text](Model.jpg)

Base:
![alt.text](Base.jpg)
# Running instructions


Open and run the notebook on Colab

