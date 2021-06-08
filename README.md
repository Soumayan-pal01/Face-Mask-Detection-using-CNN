# Face-Mask-Detection-using-CNN

This a Face Mask Detection project that uses Caffe framework to take real time video stream as input to detect human faces present in the frame and convert them into blobs using OpenCV. The prototxt file deploys the Caffe model to detect faces. This face detection model is combined with a mask detection CNN model that has been trained by finetuning the 2 topmost neural layers of the MobileNetv2 model using the concept of transfer learning. MobileNetV2 is a very light weight and efficient model.
This model has the capability to detect different types of masks with a certain confidence displayed actively on the detected face.
The demonstration video is provided for a better understanding of the model.


<img src = "https://github.com/Soumayan-pal01/Face-Mask-Detection-using-CNN/blob/main/Graphs/plot_v2.png" width="500"> 

The Haar Cascades approach was found to be inefficient as the model was unable to detect the dark contoured mask. It also failed to detect the face when the angle of face with respect to the camera exceeded from 0 degree(straight) in either sides.
