# NLP-Deep
A repository of POCs related to Natural Language Processing using Deep Learning Frameworks

**1. Sentence Classification: A Tensorflow Implementation of 'Text Understanding From Scratch' by Xiang Zhang and Yann LeCun** <br/>
(paper: https://arxiv.org/abs/1502.01710)

This file is 'Character-Level-CNN-Sentence-Classification.ipynb'
This POC is an implementation in Tensorflow of the paper 'Text Understanding From Scratch' by Xiang Zhang and Yann LeCun. 

The dataset used is the **Full Amazon Product Reviews Dataset**, which contains three columns: <br/>
1. The Review Number, on a scale of 1-5 <br/>
2. The Review Title <br/>
3. The Review Description <br/>
Only the Review Number and the Review Description are used.

For comparison, the accuracy reported by the Authors (using Torch7) for the dataset is <br />
**Training: 62.96%** (Sample size: 3,000,000) <br />
**Test: 58.69%** (Sample size: 650,000) <br />

The accuracy from this POC is as below: <br />
**Training: 63.45%** (Sample size: 624,000) <br/>
**Dev: 51.34%** (Sample size: 20,000) <br/>
**Test: tbd** (Sample size: 135,340) <br/>
<br/>
The training accuracy graph over time:
![alt text](https://github.com/nitinvwaran/NLP-Deep/blob/master/Sentence-Classification/Train_Accuracy_Tensorboard.PNG)
<br />
The average cross-entropy training loss over time:
![alt text](https://github.com/nitinvwaran/NLP-Deep/blob/master/Sentence-Classification/Cross_Entropy_Average_Loss_Tensorboard.PNG)
<br />
The validation / dev accuracy graph over time:
![alt text](https://github.com/nitinvwaran/NLP-Deep/blob/master/Sentence-Classification/Valid_Accuracy_Tensorboard.PNG)
