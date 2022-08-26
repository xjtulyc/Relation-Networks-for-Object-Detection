# PyTorch Implementation of Relation Networks for Object Detection

## Abstract

Although it is well believed for years that modeling relations between objects would help object recognition, there has not been evidence that the idea is working in the deep learning era. All state-of-the-art object detection systems still rely on recognizing object instances individually, without exploiting their relations during learning.

This work proposes an object relation module. It processes a set of objects simultaneously though interaction between their appearance feature and geometry, thus allowing modeling of their relations. It is lightweight and in-place. It does not require additional supervision and is easy to embed in existing networks. It is shown effective on improving object recognition and duplicate removal steps in the modern object detection pipeline. It verifies the efficacy of modeling object relations in CNN based detection. It gives rise to the first fully end-to-end object detector.

## How to train the model?

```
python train.py
```

## The implement of Relation Network Version 2

```
cd RelationNet
python train.py
python test.py
```
