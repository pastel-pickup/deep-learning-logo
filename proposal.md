# Brand Logo Detection in Instagram Images for Improved Targeted Advertisments
Mai Tran

# Question/Need:
# What is the question behind your analysis or model and what practical impact will your work have?
- How to provide more relevant advertisements to users by automatically detecting brand logos in their Instagram images? 
- This new ads targeting algorithm will help improve user retention and increase brand revenues. 

# Who is your client and how will that client benefits from exploring this question or building this model/system?
- My client is the image-based social media network called Instagram, who will benefit from my ads targeting algorithm to increase user retention, to increase ads revenue, and brand revenues. 

# Data Description:
# What dataset(s) do you plan to use, and how will you obtain the data? Please include a link! (The link can be to the dataset you’re downloading, the site you’re scraping, etc.)
- I am using an image dataset called Logos in the Wild created by Fraunhofer IOSB in Karlsruhe, Germany. 
- https://zenodo.org/record/5101018#.Ym87b9rMI2w

# What is an individual sample/unit of analysis in this project? In other words, what does one row or observation of the data represent?
- there are 788 text brands with each brand having at least 2 image logos. Therefore, there are at least around 1,576 data points

# What characteristics/features do you expect to work with? In other words, what are your columns of interest?
- for each logo, there at least 2 images of it

# If modeling, what will you predict as your target?
- For my model, the targe will be a correct text brand classification for an image logo

# Tools:
- Data manipulation and modeling: Pandas, Numpy, and Scikit-learn
- Neural Networks for Image Classification: Keras
- Recommendation Engine: Deep AI Image Similarity API
- Web Application of Recommendation Engine: Streamlit

# How do you intend to meet the tools requirement of the project?
For image classification:
1) Set up a GPU on Google Colab
2) Perform EDA
3) Pre-process image data
4) Use Convolutional Neural Networks and transfer learning to perform image classification
5) Test some pre-trained classification logo models
6) Visualize the results

For recommendation engine:
1) Build a recommendation system based on images using Deep AI Image Similarity API
2) Implement the recommendation system on Streamlit

# Are you planning in advance to need or use additional tools beyond those required?
1) Google Colab
2) Streamlit
3) Deep AI Image Similarity API

# MVP Goal:
# What would a minimum viable product (MVP) look like for this project?
- For the MVP, I plan to have at least a working image classification algorithm and a recommendation engine
