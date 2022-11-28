<!-- <img src="images/danger.png" width=200> Danger! Work in progress! -->

# Introduction

<table>
  <tr>
    <td> <img src="images/Profile_pic.jpeg" width=300> </td>
    <td>Welcome to my portfolio. This is an eclectic selection of data science projects that I have been working on, some of which I developed in academia, some adapted from studying machine learning, and others just out of interest.
    </td>
  </tr>
</table>


***
# Deep Learning
## Neural Style-Transfer App - [Link](https://github.com/stuarthaze/StyleTransferApp)  
This app was based on an assignment in the Coursera deep learning specialization. It uses a pre-trained VGG-19 convolutional neural network to merge the content of one image with the style of a second image. Gradient descent is used to optimize the pixels of the generated image. 

<img src="images/NeuralArtStyleTransfer.png" width=500> 

The app was built using streamlit and allows the user to modify the hyper parameters such as the ratio of content:style, learning rate and number of training epochs.
 
***
# Statistics
## Sweets selection - [Link](https://stuarthaze.github.io/Quality_Street)

Does this distribution represent an expected outcome of randomly selected sweets?  
<img src="../Quality_Street/Sweet_selection.jpg" height="200">   <img src="images/Simulation_result.png" height="200">

***
# Data Engineering
## Music Database - [Link](https://github.com/stuarthaze/Data_Modelling_Music_DB)  

This is a project that I worked on as part of a Udacity data engineering course. It demonstrates the ETL (extract, load, transform) principle, creating a PostgreSQL database from a collection of json files. The code is written in python using the psycopg2 library which acts as a wrapper for SQL. The database schema is explained in the accompanying README file along with instructions for how to set it up on a local machine.