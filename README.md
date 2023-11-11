# Cross-Modal Fusion Encoder via Graph Neural Network for Referring Image Segmentation

The code of paper: Cross-Modal Fusion Encoder via Graph Neural Network for Referring Image Segmentation 

## Abstract
Referring image segmentation identifies the object masks from images with the guidance of input natural language expressions. Nowadays, many remarkable cross-modal decoder are devoted to this task. But there are mainly two key challenges in these models.
One is that these models usually lack to extract fine-grained boundary information and gradient information of images.  The other is that these models usually lack to explore language associations among image pixels.
In this work, we design a Multi-scale Gradient balanced Central Difference Convolution (MG-CDC) and a Graph convolutional network-based Language and Image Fusion (GLIF) for cross-modal encoder, called Graph-RefSeg.
Specifically, in the shallow layer of our encoder, the MG-CDC captures comprehensive fine-grained image features. It could enhance the perception of target boundaries and provide effective guidance for deeper encoding layers.
In each encoder layer, the GLIF is used for cross-modal fusion. It could explore the correlation of every pixel and its corresponding language vectors by a graph neural network.
Since our encoder achieves robust cross-modal alignment and context mining, we could use a light-weight decoder for segmentation prediction. Extensive experiments show that our proposed Graph-RefSeg outperforms the state-of-the-art methods on three public datasets.

## Overview
![3](https://github.com/ZYQ111/Graph_refseg/blob/main/overview.png)


