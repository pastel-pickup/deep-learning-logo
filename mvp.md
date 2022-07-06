# Pet Breed Detector
Mai Tran

# Minimum Viable Product (MVP)
The goal of this project is to build a pet breed detector using deep learning algorithms. 

1) My first model was a multinomial multi-class Logistic Regression but it failed to perform because it would not recognize image data.
2) My second model was a custom neural network model built from scratch, but it failed to perform due to X_train and y_train dimension mismatch that I am still debugging. 
3) My third model was a Logistic Regression trained with transferred VGG16 weights from the ImageNet CNN. This third model produced 87% accuracy as shown below with both image and number confusion matrices. 

![image_confusion_matrix (2)](https://user-images.githubusercontent.com/67651332/177449330-13958bdb-f106-4d8b-8059-85a5dd64ac93.png)

![number_confusion_matrix (1)](https://user-images.githubusercontent.com/67651332/177449349-fa9edfbb-75c8-4e19-9ddf-af39b1f986a9.png)

For next steps, I will:
1) Continue to debug my second custom neural network model built from scratch with a smaller sample for quick turnaround
2) Explore another model that might outperform my third model
