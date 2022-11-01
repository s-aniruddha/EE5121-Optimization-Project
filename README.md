# EE5121-Optimization

## How Does Batch Normalization Help Optimization?

This is a poster I submitted as part of a group project in the course EE5121 Convex Optimization. It encapsulates key results from the paper [How Does Batch Normalization Help Optimization?](https://papers.nips.cc/paper/2018/hash/905056c1ac1dad141560467e0a99e1cf-Abstract.html) by Shibani Santurkar, Dimitris Tsipras, Andrew Ilyas, and Aleksander Madry. 

### Summary
Batch Normalization is a popular technique to speed up the training of neural networks. Traditionally, the reason attributed to BatchNorm's success is that it reduces Internal Covariate Shift. In the paper [How Does Batch Normalization Help Optimization?](https://papers.nips.cc/paper/2018/hash/905056c1ac1dad141560467e0a99e1cf-Abstract.html), they show that there is no apparent link between the efficacy of Batch Norm and the reduction of internal covariate shift. They also explore the more fundamental effect of BatchNorm: its ability to smoothen both the loss function and the gradient of the loss function, which leads to faster convergence during training. 
