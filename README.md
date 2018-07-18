# Facial Expression Recognizer

####1.Background

VGG 16 architecture is used to classify 6 emotions.

- Paper on VGG architecture: [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)

- Paper on which this project is based on: [Recognizing Facial Expressions Using Deep Learning](http://cs231n.stanford.edu/reports/2017/pdfs/224.pdf)

- Other references: [Convolutional Neural Network](http://cs231n.github.io/convolutional-networks/)

- Techniques used in training:

  1. Class balancing using Resampling of Dataset

     Reference: [8 Tactics to Combat Imbalanced Classes in Your Machine Learning Dataset](https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/)

  2. Data augmentation

     Reference:[Data augmentation](https://www.youtube.com/watch?v=JI8saFjK84o)

#### 2.Requirements

```shell
pip install -r requirements.txt
```

 

#### 3.Use

- Use train_in_colab.ipynb to train the model in google colab
- Use model_from_weights.py to create model from weights
- Use realtime.py for realtime emotion recognition
- vgg.py is architecture definition using Keras

#### 4. Results

Training:

- Loss : 0.9238
- Accuracy: 0.6496

Validation:

- Loss: 0.8733
- Accuracy: 0.6800

Test:

- Loss: 0.95643
- Accuracy: 0.6461



#### Output

![](/home/bishal/Upwork/Ahamad/EmotionRecognition/Resources/neutral.png) 



