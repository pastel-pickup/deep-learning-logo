# Pet Supply Reccommender
Mai Tran

# Abstract
According to Forbes, 78 percent of pet owners acquired their pets during the COVID-19 pandemic, and online shopping has increased by 43 percent. This deep learning project explored increased online shopping for pet owners on pet supply e-commerce web sites such as Chewy. This pet supply recommender will help personalize the online shopping experience with breed-specific supply recommendations. The best convolutional neural network(CNN) found for this recommender was a Logistic Regression with transfer learning from a pre-trained VGG16 neural network model. The network yielded 86.0% accuracy from a custom built model whose accuracy was 5.4%. 

# Design
1. Collect Data - all image data were downloaded from the website of University of Oxford. Out of 7384 images, 6 images could not be opened, so they were faulty and discarded from analysis. Split-folders was used to split all 7378 images into training, validation, and test datasets with 80/10/10 split. 


2. Data Cleaning - 60% of data are dog images and 40% are cat images. As the bar graph below shows, each pet breed has approximately ~200 images. 

   ![bar_graph_breeds (3)](https://user-images.githubusercontent.com/67651332/178844933-69c557de-4f2b-493d-b4f8-5bc0d22bbe25.png)


3. Performance Metric Selection - Accuracy was chosen for this project because it is a good metric to generally describe how well a model perform across all of 37 equal classes. It is important when all of classes are of equal importance and there is no class imbalance. 


4. Custom Baseline CNN Model With Manual Tuning 
8. Logistic Regression with Pre-Trained VGG16 Transfer Learning


# Data
The image dataset was originally created by Omkar M Parkhi, Andrea Vedaldi, Andrew Zisserman, and C.V. Jawahar of University of Oxford. The dataset is also available on Kaggle to download for commercial/research purposes under a Creative Commons Attribution-ShareAlike 4.0 Internation License. The dataset has a total of 7384 images of cats and dogs representing 37 different breeds or classes. Each breed has approximately 200 images. 

# Algorithms

1. Baseline CNN Model
2. Improved Baseline CNN Model #1
3. Improved Baseline CNN Model #2
4. Pre-Trained VGG16
5. Logistic Regression with Transfer Learning From VGG16

# Tools
- Python (pandas, numpy) for data manipulation
- Google Colab for cloud computing
- Keras/Tensorflow for deep learning
- OpenCV for image processing
- Matplotlib, Seaborn for plotting and visualizations

# Communication

