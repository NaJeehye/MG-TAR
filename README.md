# MG-TAR
## Multi-view Graph Convolutional Networks for Traffic Accident Risk Prediction

This is the implementation of a paper _submitted_ to IEEE Transactions on Intelligent Transportation Systems [Paper]

## Abstract
Due to the continuing colossal socio-economic losses caused by traffic accidents, it is of prime importance to precisely forecast the traffic accident risk for reduce future accidents. In this paper, we use _dangerous driving statistics_ from driving log data and multi-graph learning to enhance predictive performance. We first conduct geographical and temporal correlation analyses to quantify the relationship between dangerous driving and actual accidents. Then, to learn similarities between districts in addition to the traditional adjacency matrix, we explicitly model the spatio-temporal contextual relationships with heterogeneous environmental data, including the dangerous driving behavior. A graph model is generated for each type of the relationships. Ultimately, we propose an end-to-end framework, called MG-TAR, to effectively learn the association of multiple graphs for accident risk prediction by adopting multi-view graph neural networks with an interview attention module. Thorough experiments on ten real-world datasets show that, compared with state-of-the-art methods, MG-TAR reduces the error of predicting the accident risk by up to 23% and improves the accuracy of predicting the most dangerous areas by up to 29%.

## Note for Driving Record Data
- **Digital Tachograph (Driving Log) Data**: _cannot be publicly accessible_ 
  - For demonstration purpose, we partially provide the aggregated number of _classified_ dangerous driving cases in the `datasets` folder. 
  - If you are interested in the original data, there is a sample file provided [here](https://www.data.go.kr/en/data/15050068/fileData.do) by Korea Transportation Safety Authority.

## Example Run
For package installation: `pip install -r requirements.txt` 

For model testing: `Example Run.ipynb`

## Citation
```
TBD
```
