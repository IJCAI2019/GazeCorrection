# GazeCorrection: Self-Guided Eye Manipulation in the wild using Generative Adversarial Networks
The code of paper "GazeCorrection: Self-Guided Eye Manipulation in the wild using Generative Adversarial Networks". 

--------------------------------------------

'<img src = "https://github.com/IJCAI2019/Eye_Correction/blob/master/img/1.jpg" width = 400>
<img src = "https://github.com/IJCAI2019/Eye_Correction/blob/master/img/2.jpg" width = 400>


# Introduction

Gaze correction aims to redirect the person’s gaze into the camera by manipulating the eye region, and it can be considered as a speciﬁc image resynthesis problem. Gaze correction has a wide range of applications in real life, such as, the eye contract of remote users in video conference systems. In this paper, we propose a novel method which is based on the inpainting model to learn from the face image to ﬁlling-in eye regions with new contents representing corrected eye gaze. Moreover, our model does not require the training dataset labelled with the speciﬁc head pose and eye angle information; thus, the training data is easy to collect. To retain the identity information of the eye region in the original input, we propose a self-guided pretrained model to learn the angle-invariance feature. Experiments show our model achieves very compelling gaze-correction results in the wild dataset which is collected from the website and will be introduced in details.

## Network Architecture

![](/img/model.jpg)


## 

## Dependencies
* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [Tensorflow 1.4+](https://github.com/tensorflow/tensorflow)


## Usage

- Clone this repo:
```bash
git clone https://github.com/IJCAI2019/GazeCorrection.git
```
- Download the NewGaze dataset

Coming soon!!!

- Train the model using the default parameter
```bash
python main.py 
```


            
