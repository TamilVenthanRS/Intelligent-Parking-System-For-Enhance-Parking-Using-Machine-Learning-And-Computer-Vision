## Intelligent Parking System For Enhance Parking Using Machine Learning And Computer Vision
This project seeks to tackle these challenges by developing an intelligent parking system empowered by computer vision and machine learning technologies. One of the primary issues this system addresses is the lack of real-time visibility into parking space occupancy. Existing methods may fail to provide up-to-date information, leading to frustration and wasted time for drivers searching for available spots.

## About
The project named “Intelligent Parking System For Enhance Parking Using Machine Learning And Computer Vision” presents a sophisticated solution for efficient parking space management through the integration of computer vision and machine learning techniques. Traditional parking systems often struggle with the challenges of accurately detecting and monitoring available parking spots in large parking lots or structures. Furthermore, we discuss the limitations of traditional parking management systems, such as manual spot checking and inefficient resource allocation, underscoring the importance of automated solutions in addressing these challenges. By embracing advanced technologies, our system aims to streamline parking operations, alleviate congestion, and enhance overall urban mobility.
In response, our system employs computer vision algorithms to analyze live video feeds, enabling real-time detection of vacant parking spaces. Leveraging machine learning models, specifically Support Vector Classifier (SVC), our system accurately predicts the occupancy status of each parking spot based on visual cues extracted from the video stream. 
The proposed system offers several advantages, including robustness against varying lighting conditions and occlusions, thereby ensuring reliable performance in diverse environments. Additionally, by optimizing feature extraction and model selection, our solution achieves a balance between accuracy and computational efficiency, making it suitable for practical deployment. Overall, this project contributes to the advancement of smart parking management systems by providing a scalable, automated solution capable of enhancing parking space utilization and user experience.

## Features
-Model deployment
-Real-time Processing
-Environmental Adaptability
-Image Acquisition


## Requirements
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* Deep Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV, and Mediapipe for deep learning tasks.

## System Architecture

![Simple Basic Flowchart Diagram (4)](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/67c661b1-0b9a-4d8d-b9a6-526abf158f4c)


## Output

#### Output1 - Real time classification Bounding box over the parking spots
![Screenshot 2024-03-20 200002](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/cbeac210-6a56-4004-80f0-2427216ba940)

The above image is the real time detection and classification of vehicles in parking lots.Where the occupied is represented through red bounding box over the particular lot and for unoccupied green bounding box.



#### Output2 - Real time pakring spot availablity updation
![Screenshot 2024-03-20 200025](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/aa609ead-8532-481a-8b79-2acdd35b9504)

The available lots means the lot which has green bounding box are counted over the total available lots and visualized.


#### Output3 - Before the action takes place
![Screenshot 2024-03-20 200057](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/b3858726-0671-499a-8b0f-db88c3298425)

The above image is the real time detection and classification of vehicles in parking lots.Where the occupied is represented through red bounding box over the particular lot and for unoccupied green bounding box. Now we will focus on how the classification model classifies and alters the lot counting in real time. In the above image the current slots available are 124 as u can see over there. Now let's focus on the car highlighted in the above image, which will come off from the lot and after the action occurs the counting will be changed immediately. 

#### Output4 - After the action takes place
![Screenshot 2024-03-20 200123](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/941fee59-05ec-4b2e-8656-764d879a1944)

See the color of the bounding box changes immediately from red to green as  the car comes out of the parking lot . And the counting of the lots which are left over is  updated. 
#### Output5 - The Final Output screen 
![Screenshot 2024-03-20 163348](https://github.com/TamilVenthanRS/Intelligent-Parking-System-For-Enhance-Parking-Using-Machine-Learning-And-Computer-Vision/assets/75235477/1be5d381-96d2-4660-8452-256b4c1103f8)

Detection Accuracy: 96.3%


## Results and Impact
This project aims to revolutionize traditional parking management through the integration of computer vision technology and machine learning algorithms. With the ever-increasing challenges of urbanization and the scarcity of parking spaces, the need for efficient and automated parking solutions has become paramount. Leveraging advanced image processing techniques, the system can accurately detect and monitor available parking spaces within large parking lots or structures. At the core of the system lies a Support Vector Classifier (SVC) model trained to recognize the occupancy status of individual parking spots. By analyzing real-time video feeds, the model swiftly determines whether a parking spot is vacant or occupied. This classification is achieved through the extraction of relevant features from parking spot images, enabling the system to make rapid decisions with high accuracy. Furthermore, the project incorporates innovative methods for optimizing performance and efficiency. Through the utilization of techniques such as image resizing, batch processing, and parallelization, the system can handle large volumes of data swiftly and effectively. These optimizations not only enhance the speed of processing but also contribute to reducing computational overhead. By implementing this cutting-edge parking system, urban environments can benefit from improved traffic flow, reduced congestion, and enhanced parking space utilization. With its potential to streamline parking management operations and enhance the overall urban mobility experience, the project represents a significant step towards creating smarter and more sustainable cities.

## Articles published / References
1.  Intelligent Parking Lot Management: A Computer Vision ApproachWickramanayake, W. T. S., et al. "ParkMate: An Image Processing Based Automated Car Parking System." 2022 International Conference on Communication, Computing and Internet of Things (IC3IoT). IEEE, 2022.

2. Matsuda, Akihiro, et al. "A system for real-time on-street parking detection and visualization on an edge device." 2021 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops). IEEE, 2021.

3. Kaarthik, K., A. Sridevi, and C. Vivek. "Image processing based intelligent parking system." 2017 IEEE International Conference on Electrical, Instrumentation and Communication Engineering (ICEICE). IEEE, 2017.

4.	Al-Kharusi, Hilal, and Ibrahim Al-Bahadly. "Intelligent parking management system based on image processing." World Journal of Engineering and Technology 2014 (2014).
