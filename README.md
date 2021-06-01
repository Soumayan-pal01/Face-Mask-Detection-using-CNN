# Face-Mask-Detection-using-CNN

This a Face Mask Detection project that uses Caffe framework to take real time video stream as input to detect human faces present in the frame and convert them into blobs using OpenCV. The prototxt file deploys the Caffe model to detect faces. This face detection model is combined with a mask detection CNN model that has been trained by finetuning the 2 topmost neural layers of the MobileNetv2 model using the concept of transfer learning. MobileNetV2 is a very light weight and efficient model.
This model has the capability to detect different types of masks with a certain confidence displayed actively on the detected face.
The demonstration video is provided for a better understanding of the model.


<img src = "plot_v2.png" width="200"> 
