# NLP-Deep
A repository of POCs related to Natural Language Processing using Deep Learning Frameworks

**1. A Tensorflow Implementation of 'Text Understanding From Scratch' by Xiang Zhang and Yann LeCun**

This file is 'Character-Level-CNN-Sentence-Classification.ipynb'
This POC is an implementation in Tensorflow of the paper 'Text Understanding From Scratch' by Xiang Zhang and Yann LeCun. 

The dataset used is the **Full Amazon Product Reviews Dataset**, which contains three columns:
1. The Review Number, on a scale of 1-5
2. The Review Title
3. The Review Description
Only the Review Number and the Review Description are used.

For comparison, the accuracy reported by the Authors (using Torch7) for the dataset is
**Training: 62.96%** (Sample size: 3,000,000)
**Test: 58.69%** (Sample size: 650,000)

The accuracy from this POC is as below: 
**Training: 63.45%** (Sample size: 624,000)
**Dev: 51.34%** (Sample size: 20,000)
**Test: tbd** (Sample size: 135,340)

