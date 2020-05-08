# Pretrained EfficientDet Model for Character Head Detection

This repository contains pretrained EfficientDet model which detects character heads in illustrations. Models are trained using [zylo117's EfficientDet implementation](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch) and can be tested using the implementation.

## Model Performance

Models are trained on a dataset with manual annotations by myself.

\#Train Images = 3184

\#Val Images = 197

| coefficient | Download URL | mAP (IoU:0.5-0.95) | recall (IoU:0.5-0.95) | Note |
| --- | --- | --- | --- | --- |
| D0 | [character-face-efficientdet-c0.pth](https://github.com/kosuke1701/pretrained-efficientdet-character-head/releases/download/0.0/character-face-efficientdet-c0.pth) | 0.713 |  0.781 | Tested with PyTorch==1.5.0 |
| D2 | [character-face-efficientdet-c2.pth](https://github.com/kosuke1701/pretrained-efficientdet-character-head/releases/download/0.0/character-face-efficientdet-c2.pth) | 0.767 | 0.812 | Tested with Pytorch==1.5.0 |