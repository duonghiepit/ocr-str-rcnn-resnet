# OCR SCENE TEXT RECOGNITION PROJECT
-------------------------------

## Introduction
This repo can use to train a OCR model which can recognize variable length character(depend on the width of img), and transform it's pytorch model to a jit script model, that can use libtorch to load and run it. This means it can be used in a production environment.

## Notice
This project refers to other people's code, thanks to their open source behavior to promote the development of this industry.  

+ the code of training and demo is based on [CRNN_Chinese_Characters_Rec](https://github.com/Sierkinhane/CRNN_Chinese_Characters_Rec)  
+ the model is based on [Resnet.CRNN](https://github.com/zamling/Resnet.CRNN)
+ the method of constructing dataset is based on [YoloV8]

## Pipeline
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/7825998b-2d88-4f78-ac1c-47def4a07bf5)

### CRNN
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/41c8372d-0b83-440a-8046-638d300c3a24)
#### CTC Loss
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/da15bcde-e680-4dcc-94e9-3017bdb55e8f)




## Environment

The project has only been tested in the following environments:
+ OS: Windwos 11
+ CPU: i5-12400F
+ GPU: GTX 2060 6GB

## Dependencies

#### Python
+ Pytorch
+ OpenCV
+ tqdm

#### Cpp
+ libtorch
+ OpenCV

## Train
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/fcf66d0c-29bd-4e69-b06c-e98513d01907)

## Demo
### Detection
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/e2f44580-67fd-4894-a1b9-1106d3c55bc9)

### Recognition
![image](https://github.com/duonghiepit/ocr-str-rcnn-resnet/assets/138808781/8b6d5885-3bcb-4a38-9093-d745f22f2f07)
