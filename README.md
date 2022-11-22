# CV_internship

This repo represents the work I did in the final semester of my undergraduate as a Computer Vision intern at a robotics startup. I developed an object detection model using Yolov5 which can identify different classes of wastes(plastics, cardboards, etc) and deployed it on NVIDIA Jetson using TensorRT. I also developed a ResNet classification model to detect the colour of the waste and another classification model to tell if a PET bottle is crushed or not.

### Tools used
- PyTorch
- NVIDIA Jetson Xavier
- Google Colab
- AWS
- TensorRT

### Object Detection
An object detection model was developed using YoLov5 to detect different classes of wastes on a conveyor belt. The below images show the real-time result of the YoLov5 implementation on a NVIDIA Jetson Xavier. The predicted class of waste along with the confidence value of prediction is printed above the respective bounding boxes.

![alt text](https://github.com/mayankbansal82/CV_internship/blob/main/images/frame_6.png)

![alt text](https://github.com/mayankbansal82/CV_internship/blob/main/images/frame_68.png)

### Classification based on colour
Next, a ResNet model was developed to classify wastes based on their colour. Four categories of colours were selected for the wastes to be classified into: Blue, White, Red and Transparent. The predicted colour is written on the image itself. 

![alt text](https://github.com/mayankbansal82/CV_internship/blob/main/images/My%20project-1(2).png)

We can see the combined result of object detection and colour classification in the below GIF

![Alt Text](https://github.com/mayankbansal82/CV_internship/blob/main/images/ezgif.com-gif-maker.gif)

### PET bottle classification
A classification model was created which can distinguish between crushed ans uncrushed PET bottles. The results are shown in the image below.

<img align="left" src="https://github.com/mayankbansal82/CV_internship/blob/main/images/crushed_2.png">

<img align="right" src="https://github.com/mayankbansal82/CV_internship/blob/main/images/uncrushed_1.png">



