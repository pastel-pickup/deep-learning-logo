# Instagram Brand Logo Detector
Mai Tran

# Minimum Viable Product (MVP)
The goal of this project is to build a brand logo detector in Instagram images using deep learning algorithm. 

My first model was a multi-class image classification using VGG16 CNN with 0.55 accuracy during training and 0.77 accurary during test. There was an error for corrupted images, so the training was not finished completely. Hence, the big discrepancy between the training data accuracy and testing accuracy. 

![training-error-Mai-Tran](https://user-images.githubusercontent.com/67651332/167980977-3546b7a0-9187-42ac-9549-6dc1b4935cf2.png)

![testing-Mai-Tran](https://user-images.githubusercontent.com/67651332/167981000-d5660ba6-baee-410c-bcfa-5b883fea15dd.png)

For the dataset, I used 849 training images, 104 validation images, and 110 test images for a total of 6 classes of logos (aldi, amazon, apple, audi, bmw, canon). 

For next steps, I will:
1) Re-evaluate other performance metrics such as Precision, Recall, and F1 score. 
2) Build a multi-class Logistic Regression image classifier as a baseline model
3) Build a multi-class image classifier with a custom convolutional neural network (CNN)
4) Compare the performance of the Logistic Regression baseline model with the custom CNN model
5) Compare the previous 2 models with the VGG16 model with transfer learning
