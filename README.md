# 255
SJSUID - 016699683
Bonus Work 1
train one model (tensorflow or pytorch) and deploy the model by selecting one of the following features: 1) use Intel’s OpenVINO Links to an external site.for inference, 2) deploy to Nvidia DeepStream Links to an external site., 3) deploy to NVIDIA Triton Inference Server Links to an external site., 4) deploy via Torch Serve Links to an external site., 5) deploy to TF Serving Links to an external site., 6) inference via Torchscript Links to an external site., 6) Serving with REST APIs (e.g., Python Flask or Nodejs), 7) inference via Mobile device (Android or iOS) with acceleration
Compare the inference performance improvement (e.g., speed improvement over the original TF/Pytorch inference) of your selected feature.
Add the changes and comparison to the readme (GitHub readme or a separate document), submit the code link (github) to Canavs.

Selected Option : Option 1 : OpenVINO

Experiment : Multiclass classification

Dataset Used : Flower dataset in the tensorflow which more than three thousan color images with each belongs to atleast one of the class.

OpenVINO: First we will train the model in tensorflow and then we will optimize4 it using OpenVINO and the run inference and compare performances.

Inferring the results with visualization:
1.
https://drive.google.com/file/d/1Hg8hIiaCZ-QR3cx2cE8Y-0S-S6c9Jig9/view?usp=share_link
 
It’s bar graph representing the various time by the model to predict the class labels in normal tensor flow environment vs that in OpenVINO envirnoment

2.
https://drive.google.com/file/d/1rHveiCKATxXyBP8BjdFF-b8rni8UGb9F/view?usp=share_link
 
Line graph representing the relationship between various time by the model to predict the class labels in normal tensor flow environment vs that in OpenVINO environment

Drive link for Notebook and addition information : 

https://drive.google.com/drive/folders/1CHXQaqV2wTr98h97ZxDn6pwOg5_wpbe3?usp=share_link

Github link: https://github.com/surendrabodapati/255/edit/main/README.md 

Reference :  referenced OpenVINO official website
![image](https://user-images.githubusercontent.com/52579540/203496420-ea126dd6-7a2e-4f08-9cf5-fad074b70c3b.png)

