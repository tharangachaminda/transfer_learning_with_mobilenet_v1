# Binary Classification with Transfer Learning

![Logo](https://github.com/tharangachaminda/transfer_learning_with_mobilenet_v2/blob/main/banner.jpg)

Transfer Learning in Neural Network is a technique used in machine learning where knowledge gained from training one model (source domain) is transferred and applied to a different but related model (target domain). In neural networs, this involves taking a pre-trained model developed for one task and fine-tuned or using its learned features to solve another related task.

In this project I will be implementing a model using transfer learning with [**MobileNetV2**](https://arxiv.org/pdf/1801.04381.pdf) as the source model. The model will predict an image is an Alpaca image or not Alpaca image.

### Data Sources
This project is based on Images stored in the disk. I have used `image_data_set_from_directory()` function provided by `Keras` to prepare Train/Validation datasets.

### Technologies and Tools
- Tensorflow
- Keras
- MobileNetV2


## Installation

I have used [TensorFlow](https://www.tensorflow.org/) framework for this project. 

```bash
pip install tensorflow
```
    
## 🏆 Lessons Learned

1. Creat dataset from a directory
2. Preprocess and augment data using the Sequential API
3. Adapt a pretrained model to new data and train a classifier using the functional API MobileNet
4. Fine-tune a classifier's final layer to improve accuracy

## Demo
[Try it on my profile](http://ec2-34-215-236-233.us-west-2.compute.amazonaws.com/alpaca_mobilenetv2)
