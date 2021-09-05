## Face-Mask Detector
Real time face-mask detection using Machine Learning and OpenCV

## About Project
Today it has become mandatory for all the citizens to wear a face mask to protect themselves . This application can be helpful for all the shop owners, offices, banks or any public place because if anyone is not wearing a mask then he or she must not be allowed in that area. So, to take care of this problem we don’t need any guard or person who keeps a watch on people. We can integrate a camera which continuously clicks pictures of humans and detect from there faces whether they are wearing a face mask or not.

**The model is capable of predicting multiple faces with or without masks at the same time**

## Required to Learn for the Project
**Image Processing**

 Steps to perform image Processing:

     :Load images using Python or any other Programming

     :Convert images into aaray

     :After convertion of the images we can perform any algorithm on array we have

![image processing](https://github.com/CodeWithMir/important-image-for-project/blob/main/face%20detection.gif)
  
**OpenCV**

OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Being a BSD-licensed product, OpenCV makes it easy for businesses to utilize and modify the code.

The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms. These algorithms can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects, extract 3D models of objects, produce 3D point clouds from stereo cameras, stitch images together to produce a high resolution image of an entire scene, find similar images from an image database, remove red eyes from images taken using flash, follow eye movements, recognize scenery and establish markers to overlay it with augmented reality, etc. OpenCV has more than 47 thousand people of user community and estimated number of downloads exceeding 18 million. The library is used extensively in companies, research groups and by governmental bodies.
       
Featueres of OpenCV :
   
    :Face Detection
    :Geometric Transformations
    :Images Thresholding
    :Smoothing images
    :Canny Edge Detection
    :Background Removals
    :Image Segmentation
    etc...
    
![object-detection](https://github.com/CodeWithMir/important-image-for-project/blob/main/object-detection.gif)





 **How Computer see Images** 


 ![object-detection](https://github.com/CodeWithMir/important-image-for-project/blob/main/facebookcv.jpg)

 A computer sees an image as 0s and 1s. Pixel is the smallest unit in an image.

![A digital image](https://github.com/CodeWithMir/important-image-for-project/blob/main/A-digital-image-is-a-2D-array-of-pixels-Each-pixel-is-characterised-by-its-x-y.png)

    A digital image is a 2D array of pixels. Each pixel is characterised by its (x, y) coordinates and its value. [1]
When we take a digital image, it is stored as a combination of pixels. Each pixel contains a different number of channels. If it a grayscale image, it has only one pixel, whereas if it is a coloured image, it contains three channels: red, green and blue.

![A digital image](https://github.com/CodeWithMir/important-image-for-project/blob/main/1_Tlw0sUv7AJnwAbsPChS2Sg.jpeg)

    A digital image represented as pixels and channels. [2]

As shown in the above representation of a digital coloured image, each channel of each pixel has a value between 0 and 255. Each of these values represented in binary before a computer can understand the image.

## Required applications

**Anaconda Installers**

click the given link and download 
[Anaconda_Installers](https://www.anaconda.com/products/individual#Downloads) 

**Jupyter Notebook**

*already install under Anaconda Installers 


## How to use
**Install all the libraries and modules required**

                          
                        **Open Jupyter Notebook**
                        1. !pip install opencv-Python
                        2. !pip install matplotlib
                        3. !pip install sklearn
                        4. !pip install numpy
                        *****note that in case of showing in jupyter notebook 
                        that the libraries Requirement already satisfied: then 
                        the libraries already install  
**Create DataSet**
   
1st Download the "haarcascade_frontalface_default" file or [click here](https://github.com/CodeWithMir/Face-mask-detection/blob/main/haarcascade_frontalface_default.xml)
and copy the path of the file and pest in Creat_Dataset program instaed of my path "Documents/projects/face mask detection/haarcascade_frontalface_default.xml"
after open the jupyter notebook

2nd Download the Creat_DtaSet file from the repositoary or [click here](https://github.com/CodeWithMir/Face-mask-detection/blob/main/Creat_DtaSet%20(1).ipynb)
    
    1. Now open Jupyter Notebook 

    2. Copy & pest the Creat_DtaSet program

    3. Run the 1st In[1]
    
    4. A camera will open in a new tab (in case off not opening the camera change the program in 5th line of the in[1])
       when camera is not opening change the 5th line 
       **capture = cv2.VideoCapture(0) to capture = cv2.VideoCapture(1)**
    
    5. Before run the program ready with no mask face for 1st data model
       after taking 200 set of image the program will automatically break 
    
    
    6. Then run the 1st In[2] to save the data name as without_mask.npy 

    7. Now run the 1st In[1] again

    8. Now ready with a mask face before run the program 

    9. After automatically break  run the 2nd In[2] to save the data name as witho_mask.npy 
          


## Now Run the Final Code

Download the final project of face mask detection.ipynb file from repositoary or [click here](https://github.com/CodeWithMir/Face-mask-detection/blob/main/final%20project%20of%20face%20mask%20detection.ipynb)

    Run the code the project is ready 

 **For any problem during run the program cobtact me or [click here](https://www.linkedin.com/in/mir-jasimuddin-4a35131a0/)**

##            Thank You 
      
