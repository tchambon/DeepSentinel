# DeepSentinel

The goal of this repository is to give tools to use Deep Learning on Sentinel-2 satellite images.

A blog post has been written about the context (to be published soon).

This repository shows:

- [How to download Sentinel-2 images](https://github.com/tchambon/DeepSentinel/tree/master/Data%20Download) using Google Earth Engine Python API.
- [How to get a new SOTA](https://github.com/tchambon/DeepSentinel/tree/master/EuroSAT%20pretraining) (july 2019) on [EuroSAT dataset](https://arxiv.org/abs/1709.00029) using multispectral images. The model has a 0.99 accuracy (previous SOTA: 0.9857 => 30% less error rate).
- [How to use the model pretrained on EuroSAT](https://github.com/tchambon/DeepSentinel/tree/master/Training) for you own classification tasks.
- [How to process and visualize](https://github.com/tchambon/DeepSentinel/tree/master/Data%20Preprocessing) multispectral images.

You can download the [weights of the pretrained model](https://github.com/tchambon/DeepSentinel/tree/master/Weights%20of%20pretrained%20model).
