# smartCam


## Abstract: 
Using techniques of artificial intelligence and computer vision in the field of transportation to increase driving safety ,reduce car accidents,build efficient driver assistance systems like traffic sign detection and automate the car identification system.


## Introduction, Objective & Scope: 
Larger portion of vehicles nowadays are equipped with dash cameras, which continuously record and store traffic. Also there are multiple cctv cameras placed along highways and other paths which are used by government and private organizations to monitor traffic activities, illegal activities etc. Also the self driving vehicles like of Tesla use camera and few other sensors for automating driving and parking. This helps in prevention of accidents, better utilization of resources, automation and could lead to monetary gains. We we use dash camera videos, relevant cctv footages and images to implement our model/algorithm.   

## Our objective is to implement:
1. ### Lane Detection-
Lane detection is a well-researched area of computer vision with applications in autonomous vehicles and driver support systems.Road lane detection can serve as a virtual assistance for drivers and can reduce car accidents. Our model would be accurate enough to detect the central line and the accurate left and right boundaries of the lane.

2. ### Sign Detection-
Automatic traffic sign detection and recognition is an. important part of an advanced driver assistance system. Traffic symbols have several distinguishing features that may be used for their detection and identification.

3. ### Human Detection- 
Human sensing (also called human detection or human presence detection) encompasses a range of technologies for detecting the presence of a human body in an area of space, typically without the intentional participation of the detected person.

4. ### Number Plate Detection- 
An exponential increase in number of vehicles necessitates the use of automated systems to maintain vehicle information. The information is highly required for both management of traffic as well as reduction of crime. Number plate recognition is an effective way for automatic vehicle identification.

5. ### Vehicle Detection

6. ### Traffic Light Detection

7. ### Anticipating Accidents

8. ### Semantic Video Segmentation


## Techniques we have identified for our implementation are: 

*  ### Canny Edge Detection- 
The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images.

*  ### Hough Transform Line Detection-  
The Hough transform is a technique which can be used to isolate features of a particular shape within an image.

*  ### Color Selection-  
The easiest way to detect and segment an object from an image is the color based methods . The object and the background should have a significant color difference in order to successfully  segment objects using color based methods.

*   ### Local binary patterns (LBP)-   
It is a type of visual descriptor used for classification in computer vision.visual descriptors or image descriptors are descriptions of the visual features of the contents in images, videos, or algorithms or applications that produce such descriptions. They describe elementary characteristics such as the shape, the color, the texture or the motion, among others.

*   ### HAAR-detection-   
Object Detection using Haar feature-based cascade classifiers is an effective object detection method.It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

*  ### Single Shot MultiBox Detector-
Used for detecting objects in images using a single deep neural network.

*  ### Non-maxima suppression algorithm-Non-maximum suppression (NMS)-
It has been widely used in several key aspects of computer vision and is an integral part of many proposed approaches in detection, might it be edge, corner or object detection





## Libraries/framework we have identified for our project are: 

* [OpenCV](https://opencv.org) 
* [Matplotlib](https://matplotlib.org/)
* [Numpy](http://www.numpy.org)
* [Openalpr](http://www.openalpr.com)
* [LibAV](https://www.libav.org) 
* [Python Image Library (PIL)](http://www.pythonware.com/products/pil/)
* [Imutils](https://github.com/jrosebr1/imutils)


## Challenges:
1.	### Lane detection
* One major challenge in lane detection is the detection of lane in curved road. Detection of straight is easier as compared to curved lanes.
* Bad environmental conditions like fog, haze , and dust can degrade the image quality and can thus decrease the accuracy of the model/algorithm.
* Lane boundaries are often not clearly visible. This might be due to poor road conditions, poor painting of the lane marking, shadow from a tree or any other objects

2.	### Number plate detection
* Read license plates that are different at the front and the back because of towed trailers, campers, etc
* Dirt on the plate 
* Poor lightning and low contrast
* Blurry images due to motion blur

3.	 ### Sign detection
* Sign detection during night and dark environment.





## Bibliography:

* A learning approach towards detection and tracking of lane markings;Raghuraman Gopalan, Member, IEEE, Tsai Hong, Michael Shneier, and Rama Chellappa, Fellow, IEEE, Published in: IEEE Transactions on Intelligent Transportation Systems ( Volume: 13, Issue: 3, Sept. 2012 )

* Research on lane detection technology based on openCV; Zu Yang, Zhang Ling,Published in: 3rd International Conference on Mechanical Engineering and Intelligent Systems (ICMEIS 2015)

* A Vision Based Lane Detection and Tracking Algorithm in Automatic Drive; Wenhong Zhu ;  Fuqiang Liu ;  Xinhong Wang ;  Shanshan Zhang, Published in: Computational Intelligence and Industrial Application, 2008. PACIIA '08

* DeepLanes: End-To-End Lane Position Estimation using Deep Neural Networks; Alexandru Gurghian, Tejaswi Koduri, Smita V. Bailur, Kyle J. Carey, Vidya N. Murali, Published in: Computer Vision and Pattern Recognition Workshops (CVPRW), 2016 IEEE Conference

*  Learning to Predict Where Humans Look; T. Judd, K. Ehinger, F. Durand, A. Torralba, Published in: International Conference on Computer Vision (ICCV) 2009

*  Small codes and large databases for recognition. Torralba, Fergus, Weiss, Published in: Computer Vision and Pattern Recognition, 2008. CVPR 2008. IEEE Conference

* Describing Objects by their Attributes. Farhadi, Endres, Hoiem, Forsyth, Published in: Computer Vision and Pattern Recognition, 2009. CVPR 2009. IEEE Conference

