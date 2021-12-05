# K-ompanion
Hackathon Repository

## [TRAINING Notebook](https://colab.research.google.com/drive/1ylJkBkTyJKYme370JfXaRW_AW5xW82rz?usp=sharing)

## [Training Log and Result](https://wandb.ai/curieuxjy/YOLOv5?workspace=user-curieuxjy)

## Goal : Dog Action dataset + Yolov5 + Jetson Nano

### Dataset

https://aihub.or.kr/aidata/34146

### Jetbot

http://www.yahboom.net/study/JETBOT

### Retina Net

`python keras_retinanet/bin/train.py --gpu=0 --epochs=10 --steps=1000 --workers=0 csv .\csv\action.csv .\csv\action_mapping.csv`

[keras-retinanet
](https://github.com/fizyr/keras-retinanet)

[Object Detection with RetinaNet - keras docs](https://keras.io/examples/vision/retinanet/)

[Custom Dataset으로 Retinanet 학습하기](https://boysboy3.tistory.com/149)

[Keras Model을 TensorRT로 변환하기](https://hagler.tistory.com/188)

### Pytorch (Lightining) - Efficient Net

https://github.com/arvcode/TensorRT_classifier_efficientNet

https://kamilake.com/306

https://ys-cs17.tistory.com/34

### Other source

https://github.com/DeepLabCut/DeepLabCut
http://www.mackenziemathislab.org/dlc-modelzoo

https://github.com/DeepLabCut/DeepLabCut/blob/master/docs/installation.md

https://github.com/GuillaumeMougeot/DogFaceNet

https://github.com/Jinhyeok1489/hakathon
