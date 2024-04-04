# Driver-Drowsiness-System
Overview:
This project aims to develop a driver drowsiness detection system to mitigate the high occurrence of accidents caused by drowsy driving. The system utilizes the YOLOv5 model for object detection and classification. The dataset used for training the model was created using OpenCV for image capture and LabelImg for labeling the images as 'awake' and 'drowsy'.

Implementation:
1.Data Collection- Images were continuously captured using OpenCV to build a dataset that captures various states of driver alertness.

2.Data Labeling- The collected images were labeled as either 'awake' or 'drowsy' using LabelImg, ensuring that the model is trained to recognize both states effectively.

3.Model Training- The YOLOv5 model was trained on the labeled dataset to detect signs of drowsiness in real-time video streams.

4.Deployment- The trained model can be deployed in vehicles or integrated with existing safety systems to provide timely alerts to drivers when signs of drowsiness are
