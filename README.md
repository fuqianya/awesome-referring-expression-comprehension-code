# Awesome-referring-expression-comprehension-code

![REC](./REC.png)

This repo reproduces a wide rage of papers about Referring Expression Comprehension (REC). The task of REC aims to localize a target object in an image described by a referring expression, as we can see above. In this repo, we advocate **high-quality** implementation. Unlike most open source repos which only implement methods roughly, we carefully check our code and read the original paper to make sure the consistent between them. We also compare the performance of our implementation with the results reported in the original paper to further validate the correctness of our implementation. Only the implementation with closely performance of the original paper will be included in this repo. Furthermore, We rewrite some code, which is originally written with `caffe` or `Tensorflow 1.x` that may annoy someone not familiar with it, with `Tensorflow 2.x` and `PyTorch` which are more readable.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![Python 3.7](https://img.shields.io/badge/python-3.7-green.svg) ![tensorflow2.2.0](https://img.shields.io/badge/tensorflow-2.2.0-orange) ![pytorch](https://img.shields.io/badge/pytorch-1.5.0-blue) [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) [![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE.md)

<style>
table th:first-of-type {
    width: 25%;
}
table th:nth-of-type(2) {
    width: 50%;
}
table th:nth-of-type(3) {
    width: 15%;
}
table th:nth-of-type(3) {
    width: 15%;
}
</style>

## Finished

## Ongoing
 **Model** | **Paper** | **Paper** | **Code** 
|:-:|:-:|:-:|:-:|
| [Rohrhach, 2016'ECCV] |Grounding of Textual Phrases in Images by Reconstruction | [1511.03745](https://arxiv.org/abs/1511.03745)| - |

## TODO

 **Model** | **Paper** | **Paper** | **Code** 
|:-:|:-:|:-:|:-:|
| [Mao, 2016'CVPR] |Generation and Comprehension of Unambiguous Object Descriptions| [1511.02283](https://arxiv.org/abs/1511.02283)|  |
| [Hu, 2016'CVPR] | Natural Language Object Retrieval | [1511.04164](https://arxiv.org/abs/1511.04164)| - |
| [Nagaraja, 2016'ECCV] | Modeling Context Between Objects for Referring Expression Understanding | [1608.00525](https://arxiv.org/abs/1608.00525)| - |