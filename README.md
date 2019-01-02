# DeepXSS

## Research paper

We present the findings of this work in the following research paper:

**DeepXSS: Cross Site Scripting Detection Based on Deep Learning**  
Yong Fang, Yang Li, Liang Liu, Cheng Huang. 
*In Proceedings of the 2018 International Conference on Computing and Artificial (ICCAI 2018) , March 2018*

[[PDF](https://doi.org/10.1145/3194452.3194469)]

## Introduction

Nowadays, Cross Site Scripting (XSS) is one of the major threats to Web applications. Since it's known to the public, XSS vulnerability has been in the TOP 10 Web application vulnerabilities based on surveys published by the Open Web Applications Security Project (OWASP). How to effectively detect and defend XSS attacks are still one of the most important security issues. In this paper, we present a novel approach to detect XSS attacks based on deep learning (called DeepXSS). First of all, we used word2vec to extract the feature of XSS payloads which captures word order information and map each payload to a feature vector. And then, we trained and tested the detection model using Long Short Term Memory (LSTM) recurrent neural networks. Experimental results show that the proposed XSS detection model based on deep learning achieves a precision rate of 99.5% and a recall rate of 97.9% in real dataset, which means that the novel approach can effectively identify XSS attacks.


If you use *DeepXSS* in a scientific publication, we would appreciate citations using this **Bibtex** entry:
``` tex
@inproceedings{fang2018deepxss,
  title={DeepXSS: Cross Site Scripting Detection Based on Deep Learning},
  author={Fang, Yong and Li, Yang and Liu, Liang and Huang, Cheng},
  booktitle={Proceedings of the 2018 International Conference on Computing and Artificial Intelligence},
  pages={47--51},
  year={2018},
  organization={ACM}
}
```
