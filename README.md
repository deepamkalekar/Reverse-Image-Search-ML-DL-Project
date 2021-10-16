
# Reverse Image Search Web Application

This project is based on Deep Learning (ResNET50) and Machine Learning. 
It is similar to the google and amazon image search option, where 
you can upload any image and get the recommendation similar
to the given image. In this project we use Myntra and Amazon image dataset 
from kaggle which include watches, shoes, colths. As an update
we can train this model with other datasets also like furniture, cars, etc.

```ResNET50``` ```Convolutional neural network (CNN)```
\
``` K-Nearest Neighbors Algorithm (KNN)``` ```Streamlit```


## Run Locally

Clone the project

```bash
  git clone https://github.com/deepamkalekar/Reverse-Image-Search-ML-DL-Project.git
```

Go to the project directory

```bash
  cd Reverse-Image-Search-ML-DL-Project
```
Download Dataset :- [Product Image Data (16 GB)](https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset)
\
Create folder **``images``** and move all the download images to this folder
\
Create folder **``uploads``** in the same directory for user, whenever user upload a photo it will be saved in this folder

Install dependencies

```bash
  pip install requirements.txt
```
Train Model
```bash
  python app.py
```
Run the Streamlit Web App
```bash
streamlit run main.py
```
  
## Demo
Click On ```Browse File``` and upload image
![preview1](https://github.com/deepamkalekar/Reverse-Image-Search-ML-DL-Project/blob/master/preview1.png)

![preview2](https://github.com/deepamkalekar/Reverse-Image-Search-ML-DL-Project/blob/master/preview2.png)

  
