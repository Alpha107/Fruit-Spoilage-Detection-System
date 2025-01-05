
# Fruit Spoilage Detection System
#
#
This project is a computer vision system that detects spoilage in fruits using Convolutional Neural Networks (CNNs). It was developed as a minor project for the Computer Engineering course.

## Contributers
• Aavash Adhikari(077BCT001)

• Abashesh Ranabhat(077BCT003)
 
• Krisham Rai(077BCT015)

• Sumnima Giri(077BCT035)

## Dataset
We trained the model on four fruits type i.e. Apple, Banana, Orange and Grapes. The dataset used for training the models was collected from two sources:

### Manual Collection: 
A custom dataset of fruit images was collected by the team, capturing various stages of spoilage.

### Kaggle Dataset: 
Additional fruit images were obtained from relevant datasets on Kaggle.

https://www.kaggle.com/datasets/moltean/fruits

https://www.kaggle.com/discussions/getting-started/358325

## Model Development
During the development phase, multiple CNN models were built and evaluated. The team experimented with different architectures, hyperparameters, and training strategies to optimize the model's performance. In total, 8-10 models were developed, and the best-performing model was selected for final testing and demonstration.

After rigorous experimentation and evaluation, the following model was chosen as the best-performing model for fruit spoilage detection.

### Important Work:

As the ImageDataGenerator function is only able to use a single pre-processing function among many done for the best feature extraction possible. This would make our work of doing multiple pre-processing meaning less. So we build a custom ImageDataGenerator named combined_generaotr. This will now allow the model to use all the data extracted by every pre-processing function we have used.This increased the overall peformance and result of our model significantly while distinguishing the fruits.

### Model Architecture: 

![14](https://github.com/Alpha107/Fruit-Spoilage-Detection-System/assets/115240879/682fb560-3cdc-46c9-9ea1-dcf1f48da1c9)

### Training Details:
[Include information about the training process, such as the number of epochs, batch size, optimizer, loss function, and any other relevant details.]
For the final teting and demonstrating model we carried out 15 epochs of 60 batch size. For the Convolution, Pooling, Flattening and Full Connection Layer we used ReLu activation and for the Output Layer we used SoftMax activation. We used Adam Optimizer with the learning rate of 0.001 for the model compiling. In the full connection layer we added the dropout of 0.1 for the model stability.

### Performance Metrics: 

• Accuracy:- 97.8223% 

• Precision:- 96.167%

• Recall:- 96.00%

• F1-Score:- 98.00%
