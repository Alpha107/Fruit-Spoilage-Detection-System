
# Fruit Spoilage Detection System
#
#

## Abastract

A fruit spoilage detection system is an approach to accurately identify and detect spoilage in various foods through image processing. Manual identification of fresh and rotten fruits are time consuming and prone to errors hampering efficient fruit supply chain management. The following project aims to develop a fruit spoilage detection system via a desktop application using Convolutional Neural Network (CNN) to accurately detect spoilage in various fruits. Vision algorithms, such as OpenCV, have been used to preprocess the image of the fruit. A CNN has been used to extract the features from fruit images, and SoftMax has been used to classify the images as fresh and rotten fruits. To further enhance the system’s accuracy, data augmentation techniques, such as image rotation and flipping, have been employed to increase the diversity of the training dataset. As a proof of concept, the performance of the fruit spoilage detection system was evaluated on a dataset of apples, bananas, oranges, and green grapes. The proposed system is beneficial for a wide range of users including consumers, vendors, and fruit industry professionals thereby promoting fruit safety, minimizing waste, and making informed decisions about the fruits they consume or sell. Our fruit spoilage detection system, leveraging advanced image pre-processing techniques and a robust CNN, has demonstrated good accuracy in identifying and classifying fresh and rotten fruits. 

## Aims 

The primary aim of project is to develop an automated fruit spoilage detection system capable of accurately identifying and categorizing fresh and rotten fruits. 

## Objectives


• To develop a Fruit Spoilage Detection System using computer vision techniques and machine learning algorithms to address the challenges of fruit spoilage.

• To implement a deep learning-based model using CNN architecture.

• To use a dataset comprising a diverse collection of fruits, ensuring comprehensive coverage to facilitate accurate fruit spoilage detection in real time. 

## Scope of the project

The project focuses on creating an automated system capable of detecting fruit spoilage in real-time using CNN. Its major aspect include distinguishing freshness and rottenness of fruit by training the model and integrating it into a real-time environment, and ensuring its reliability and effectiveness. The project seeks to offer a valuable solution for improving food quality control processes by enabling timely detection of spoiled fruits and also ensures consumer safety by preventing them from consuming it.

## Significance

The fruit spoilage detection system is very important in fruit and juice industries. It helps industries to identify fresh and rotten fruits quickly and accurately, so as to avoid using bad fruits for juice production. This reduces losses and ensures that consumers get safe and good quality fruits and juices. The system uses modern technologies like deep learning to make it work accurately. By using these techniques of deep learning, fruit and juice industries can manage their fruit supplies better and improve their revenue. Overall, the system provides significant contribution in fruit and juice industries and makes sure that people consume high quality fruit in day-to-day life.

## System Block Diagram

![1](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/0ff11f5c-a608-42cd-8f88-ea415e531eed)

## Flowchart

![2](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/421a6115-5ebc-4df0-8002-9b9bc5bdf5d0)


## Model Peformance

![3](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/5c69f469-f2e4-4699-9bff-232f3587f21f)
![4](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/60f161cc-0520-428a-a386-603fd6e5524f)
![5](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/883f5c91-3577-484a-8a1f-14b43ac61065)


## Prediction Results

![Screenshot 2024-05-11 211117](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/cc46f849-b6e2-4774-abf5-ea7d40764251)
![Screenshot 2024-05-11 211105](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/94d16144-d25b-4899-afc0-f7f2c2322574)

## Desktop Application
For the application, we used Tkinter that was very common and easy to build desktop application with. In application, we added button to add, capture, recapture and process image. We could use both interated webcam or an external webcam according to our requirement. Using the load button we could load a
image for the system. Using capture and recapture button we could capture new images using our webcam. The process button is enabled only after a image is either loaded or captured. After clicking the process button, the corresponding prediction would be displayed on the application itself. 

## Conclusion

The project has utilized deep learning and computer vision to detect spoilage on fruits like apple, orange, grapes and banana. The ultimate goal of distinguishing freshness and rottenness of fruits has been achieved by the model. For providing higher efficiency and adaptability, we developed a combined generator that integrates multiple pre-processing steps while addressing the limitations of ImageDataGenerator.

We created desktop app using Tkinter for enhanced user interface providing users with seamless interaction experience with fruit spoilage detection. The model successfully identified spoilage patterns in various fruits under diverse scenarios during testing phase. This comprehensive project not only showcased our expertise in machine learning and computer vision but also underscored the practical application of these technologies in addressing real-world challenges.


## Future Enhancement

• This project is an image-based spoilage detection system, but it could be expanded as a real time video-based spoilage detection system.

• To broaden the application, we can add varieties of fruits with proper dataset.

• Infrared scanning and gas sensors can be integrated for spoilage detection of fruits whose state cannot be determined by outer surface.

