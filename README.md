# CANet-on-Indian-Driving-Dataset
Building the Context aggregation network model for testing on Indian Driving Dataset for Semantic Segmentation
1.   One of the main issues in semantic segmantation is to aggregate multiscale contextual information effectively. For this, a novel paradigm called Chained Context Agregation Module (CAM) has been proposed.CAM gains features of various
spatial scales through chain-connected ladder-style information flows. CAM captures features of various scales at different levels and aggregates them in stages
by the chain-connected ladder-style information flows.
2.   Semantic segmentation is a vital task in computer vision used to assign currosponding semantic labels to individual pixels in images and has applications in automatic driving, medical imaging etc.
3. FCN's gain increasing receptive feild and high level contexts - through cascaded convolution and pooling layers. However, continuous downsampling process causes loss of spatial details, resulting in poor object delination.

- I developed the model architecture as explained in the paper and ran it for 70 but stopped at 53 epochs since the metrics stopped improving. Link: https://arxiv.org/pdf/2002.12041.pdf
- I got a final accuracy of Accuracy is 69.96%; Mean IoU as 46.84 and Dice Coefficient as 62.64 on my test dataset.
