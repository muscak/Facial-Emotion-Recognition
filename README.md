# Facial Emotion Recognition

<img src='Images/fer-title.jpeg' align='center' alt='Facial Emotion Recognition'></img>

Recent research suggests that a significant portion, approximately 55%, of emotional communication primarily relies on facial expressions and other visual cues [1]. Hence, developing a model that precisely recognizes facial emotions represents a major advancement in equipping AI-powered machines with emotional intelligence. Automated facial expression recognition systems offer vast potential across diverse applications, spanning from understanding human behavior and identifying mental health conditions to improving virtual assistants for customer-centric businesses. It’s also important for Emotion Recognition for Human-Robot Interaction [2]. Using Deep Learning and AI techniques to create a computer vision mode that can accurately detect facial emotion is an important step towards the development of emotionally intelligent machines powered by AI. CNN has been extensively used in diverse computer vision applications, including FER. At the beginning of the 21st century, several studies in the Facial Expression Recognition (FER) literature found that the CNN is robust to face location changes and scale variations and behaves better than the multilayer perceptron (MLP) in the case of previously unseen face pose variations [3].

The objective of this project involves leveraging Deep Learning and Artificial Intelligence methodologies to develop a computer vision model. This model aims to precisely identify emotions in facial expressions by performing multi-class classification on images of faces, effectively associating each expression with its corresponding emotion.

## Solution Design

### Data Exploration

We have 20,214 images consisting of three different image sets which are train, validation and test sets. Each set contains four different emotions (classes) that are happy, neutral, sad and surprised. You may see some of the example images for each emotion from the training set below. 

<img src='Images/emotions.jpg' align='center' alt='Ramdom images from the training set with happy faces'></img>

|     |Train|Validation|Test|Total|
|----:|:---:|:--------:|:--:|:---:|
|Happy|3,976|1,825|32|5,833|
|Neutral|3,978|1,216|32|5,226|
|Sad|3,982|1,139|32|5,153|
|Surprised|3,173|797|32|4,002|
|**Total**|**15,109**|**4,977**|**128**|**20,214**|

Exact number of images for each set and for each emotion can be seen in Checking Distribution of Classes section.`

Emotion recognition from the facial expressions using CNN

This project has 3 sections:
1. Baseline model which created manually
2. Transfer learning
3. Hyperparameter optimization using Keras Tuner

---
# Bibliography

[1] Mehrabian, A. (2008). Communication without words. Communication theory, 6, 193-200.

[2] Spezialetti, M., Placidi, G., & Rossi, S. (2020). Emotion recognition for human-robot interaction: Recent advances and future perspectives. Frontiers in Robotics and AI, 145.

[3] Li, S., & Deng, W. (2020). Deep facial expression recognition: A survey. IEEE transactions on affective computing, 13(3), 1195-1215.

[4] Dsouza, J. (2020, April). “What is a GPU and do you need one in Deep Learning?”: Towards Data Science. https://towardsdatascience.com/what-is-a-gpu-and-do-you-need-one-in-deep-learning-718b9597aa0d
