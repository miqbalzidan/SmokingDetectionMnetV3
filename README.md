# Development of a Computer Vision-Based Smoker Detection System with MobilenetV3 Algorithm 

# Abstract
Cigarette consumption is one of the most
significant global health issues in the world. The World Health
Organization (WHO) estimates that around 1.3 billion people
worldwide use tobacco products. Indonesia also ranks third with
the world's highest number of active smokers. Tobacco is not
only dangerous for those who use it, but it is also dangerous for
those exposed to the smoke. People can smoke indiscriminately
if controls on cigarette use are lax or even not enforced. Various
studies have been developed to overcome the problem of
smoking, including methods of identifying people who smoke.
Different imaging devices are used to detect human activities,
including smoking behavior. With the rapid development of
artificial intelligence and deep learning in recent decades,
including computer vision, various methods have been
developed to detect smoking people. One such method is
MobileNetV3, one of the Convolutional Neural Network (CNN)
architectures. MobileNetV3 was explicitly developed for mobile
applications and embedded systems because of its
computationally lightweight nature. This study aims to create a
computer vision-based smoking detection system using
MobileNetV3. In the system architecture, the dropout layer is
used to overcome the problem of overfitting, so that model
performance increases. The datasets used are from Mendeley
Data and Kaggle, which are a collection of images of smoking
people, a total of 2410 images and 3275 images, respectively.
Through simulation using a dropout configuration of 0.5, the
proportion of the training dataset: validation: training to 80: 10:
10, the model managed to obtain the best performance with an
accuracy value of 92.08%, a loss value of 22.87%, a precision
value of 93.16%, and the recall value is 90.83%. This accuracy
is better than the studies conducted by Junlong Tang et al. with
YOLOv5s, which resulted in an accuracy of 85.6%
#

* Mendeley Dataset available at : https://data.mendeley.com/datasets/7b52hhzs3r/1
* Kaggle Dataset available at : https://www.kaggle.com/datasets/vitaminc/cigarette-smoker-detection
* For each experiment hyperparameters please refer to "experiment notes.txt"
* Developed-model folder contains each model training and test results

