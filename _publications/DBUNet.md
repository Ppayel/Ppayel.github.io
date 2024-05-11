---
title: "DBU-Net: Dual branch U-Net for tumor segmentation in breast ultrasound images"
collection: publications
permalink: /publication/DBUNet
excerpt: 'This paper is about the DBU-Net.'
date: 2023/11/6
venue: 'Plos one'
paperurl: 'https://doi.org/10.1371/journal.pone.0293615'
citation: 'Pramanik, P., Pramanik, R., Schwenker, F., & Sarkar, R. (2023). DBU-Net: Dual branch U-Net for tumor segmentation in breast ultrasound images. Plos one, 18(11), e0293615.'
---
In this study, drawing inspiration from the U-Net concept, we propose a new variant of the U-Net architecture, called DBU-Net, for tumor segmentation in breast ultrasound images. To enhance the feature extraction capabilities of the encoder, we introduce a novel approach involving the utilization of two distinct encoding paths. In the first path, the original image is employed, while in the second path, we use an image created using the Roberts edge filter, in which edges are highlighted. This dual branch encoding strategy helps to extract the semantic rich information through a mutually informative learning process. At each level of the encoder, both branches independently undergo two convolutional layers followed by a pooling layer. To facilitate cross learning between the branches, a weighted addition scheme is implemented. These weights are dynamically learned by considering the gradient with respect to the loss function. We evaluate the performance of our proposed DBU-Net model on two datasets, namely BUSI and UDIAT, and our experimental results demonstrate superior performance compared to state-of-the-art models.

[Download paper here](https://doi.org/10.1371/journal.pone.0293615)
