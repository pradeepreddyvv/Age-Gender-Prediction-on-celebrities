# Identification-of-Age-Gender-celebrity-ID
## Visual-Identification-of-Age-Gender-and-celebrity-ID-using-celebrities-faces.
#
### Used WIKI images for Identification.
https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/
#
### Used only wiki_crop(only faces) images you can get the images dataset from the below link.
https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/wiki_crop.tar
#
### I had used a facedetection Dlib to crop the faces from wiki_crop images.
#### Available here to dowload - http://dlib.net/files/mmod_human_face_detector.dat.bz2
#### One can also do this by using some python code(without using dlib)
## These are some screenshots to get some idea about the project.
### This is how the face will be detected from "wiki only faces" dataset and we store only these cropped face by detecting the face from wiki_crop image dataset.
![Screenshot 2021-05-18 125856](https://user-images.githubusercontent.com/51847492/118610361-4f3b3a80-b7d9-11eb-9fa9-0f255b5fde23.jpg)
#
![Screenshot 2021-05-18 131312](https://user-images.githubusercontent.com/51847492/118611953-f53b7480-b7da-11eb-9eee-303c411e6c78.jpg)
#
![Screenshot 2021-05-18 131355](https://user-images.githubusercontent.com/51847492/118611973-f9679200-b7da-11eb-9fd4-ea07c0b1c64d.jpg)
#
### This is how the images will be splited for tarining and testing

![Screenshot 2021-05-18 125928](https://user-images.githubusercontent.com/51847492/118610394-595d3900-b7d9-11eb-9e34-65c8c973deda.jpg)
#
### These are the remaining images after droping corrupted one's(images).
![Screenshot 2021-05-18 130019](https://user-images.githubusercontent.com/51847492/118610426-5f531a00-b7d9-11eb-940b-cb7e713e5c3d.jpg)

### Now we analysis the faces by tarining the model.
### The piple line will look like this
![image](https://user-images.githubusercontent.com/51847492/118615458-63ce0180-b7de-11eb-83dc-69d3137460f6.png)
#
### I had used a Age & Gender classifier for Age & Gender prediction.
### Can train the model from scrach or you can use a pre-trained model .h5 file for prediction.
#
#### Download from here(the pre-trained models using model_weights)
##### Face - https://drive.google.com/file/d/1UcdMczPQJen4bcodGG5KyyaRAKe_L6lG/view?usp=sharing
##### Age - https://drive.google.com/file/d/1YCox_4kJ-BYeXq27uUbasu--yz28zUMV/view?usp=sharing
##### Gender - https://drive.google.com/file/d/1wUXRVlbsni2FN9-jkS_f4UTUrm1bRLyk/view?usp=sharing
#
### Use thses for whole project to predict


