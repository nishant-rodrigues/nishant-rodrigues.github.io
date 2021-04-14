---
title: "Dilated CNN for Brain Tumor Detection"
date: 2020-07-17T13:34:00+05:30
tags: [ brain tumor, classification, dilation, convolutional, deep learning]
---
Brain tumor classification is a challenging task in the field of medical image processing. Technology has now enabled medical doctors to have additional aid for diagnosis. We aim to classify brain tumors using MRI images, which were collected from anonymous patients and artificial brain simulators. In this article, we carry out a comparative study between Simple Artificial Neural Networks with dropout, Basic Convolutional Neural Networks (CNN), and Dilated Convolutional Neural Networks. The experimental results shed light on the high classification performance (accuracy 97%) of Dilated CNN. On the other hand, Dilated CNN suffers from the gridding phenomenon. An incremental, even number dilation rate takes advantage of the reduced computational overhead and also overcomes the adverse effects of gridding. Comparative analysis between different combinations of dilation rates for the different convolution layers, help validate the results. The computational overhead in terms of efficiency for training the model to reach an acceptable threshold accuracy of 90% is another parameter to compare the model performance. 

[Full paper](https://www.mdpi.com/2076-3417/10/14/4915/htm)

{{< details "Cite" >}}
```bibtex
@Article{app10144915,
AUTHOR = {Roy, Sanjiban Sekhar and Rodrigues, Nishant and Taguchi, Y-h.},
TITLE = {Incremental Dilations Using CNN for Brain Tumor Classification},
JOURNAL = {Applied Sciences},
VOLUME = {10},
YEAR = {2020},
NUMBER = {14},
ARTICLE-NUMBER = {4915},
URL = {https://www.mdpi.com/2076-3417/10/14/4915},
ISSN = {2076-3417},
DOI = {10.3390/app10144915}
}
```
{{< /details >}}
