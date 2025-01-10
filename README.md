# Simple-CNN-Classifier-4567
Simple CNN classification for weather data.

Multi-class Image Classification using Keras on
Weather Dataset
Sivasoruby Kanapathipillai
ICT/18/19/
4567
1) Introduction to the problem
Time and again unfortunate accidents due to inclement weather conditions across the globe
have surfaced. Plane crash , Ship collision, train derailment and car accidents are some of
the tragic incidents that have been a part of the headlines in recent times. This grave
problem of safety and security in adverse conditions has drawn the attention of the society
and numerous studies have been done in past to expose the vulnerability of functioning of
transportation services due to weather conditions.
With the advancement in technology and emergence of a new field, intelligent
transportation, automated determination of weather condition has become more relevant.
Present systems either rely on series of expensive sensors or human assistance to identify
the weather conditions. Researchers have channeled their research in a direction where
computer vision techniques have been used to classify the weather condition using a single
image.
The task of assessing the weather condition from a single image is a straightforward and
easy task for humans. Nevertheless, this task has a higher difficulty level for an autonomous
system and designing a decent classifier of weather that receives single images as an input
would represent an important achievement.
2) Data description
This data has been collected from internet and the images of interest containing Creative
Commons license retrieved from Flickr, Unsplash and Pexels have been used. Different
images are subject to different types of licenses.
The dataset features 5 different classes of weather collected from the above said different
sources, however it's real life data so any system for weather classification must be able
to handle this sort of images. The dataset contains about 1500 labelled images including
the validation images. Images are not of fixed dimensions and the photos are of different
sizes. Each image has only one weather category and are saved in separate folder as of
the labelled class.
Each image have been rated for the weather condition on a scale of 0 to 4:
0 - Cloudy
1 - foggy
2 - rainy
3 - Shine
4 - Sunrise.

Model Designing and Training
i) Data downloading using Kaggle API
ii) Data directory creation
iii) Data splitting
iv) Data augmentation
v) Sequential Model creation
Hyperparameter
30 epochs
50 epochs

Testing approach
Evaluation results
Note: Because of hardware requirements specially in epochs, I used Google colab as IDE
not Jupyter Notebook. That’s why keep the both file as named “Assignment02_4567_final”
Github link: https://github.com/sorubys/Simple-CNN-Classifier-4567.git
Youtube link: https://youtu.be/7eFacU7Io4o
