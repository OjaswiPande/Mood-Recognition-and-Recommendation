# Mood-Recognition-and-Recommendation[Report ML Miniproject (1).pdf](https://github.com/OjaswiPande/Mood-Recognition-and-Recommendation/files/11819008/Report.ML.Miniproject.1.pdf)
Problem Scenario 
Emotions can significantly influence our moods and play a significant 
role in our daily life and affect our decision-making. For example, when we feel happy, we lean toward more energetic, lively music or farcical movies or when we feel sad, we may prefer to listen to slower, more melancholic music or movies with emotional depth. Identifying our emotions can be challenging. 
People often struggle to find the perfect song or movie to match their current emotions. Traditional recommendation systems rely on user history or pre-defined genres, which may not always reflect a user's current mood or emotional state. Additionally, users may not always accurately self-report their emotions, leading to inaccurate recommendations. 
Proposed Solution 
To address this issue, we propose a system that uses face detection technology to accurately identify a user's emotional state in real-time. By analyzing facial expressions, the system can determine if a user is happy, sad, angry, or surprised, among other emotions. Based on this analysis, the system can then recommend songs or movies that align with the user's current emotional state. 
We take takes user’s face as input and recognizes their emotions and recommend music, movies, food, and some activities to do based on their emotions. Our method involves using a convolutional neural network (CNN) to extract facial features and classify user’s emotions. 
Abstract 
This project aims to create a songs and movie recommendation system based on a user's real-time emotional state. The system will use face detection technology to accurately identify a user's emotions and provide recommendations accordingly.
To achieve this, the project will involve training a deep learning model to recognize facial expressions associated with different emotions. The model will then be integrated into a recommendation system that will suggest songs or movies based on the user's current emotional state. 
The proposed system aims to provide a more personalized and accurate recommendation system for users, addressing the limitations of traditional recommendation systems that rely on user history or pre-defined genres. 
# Features: 
- Real time expression detection and song recommendations. 
- Neumorphism UI for website. 
Data set information (link,few data samples, etc) 
We have used a dataset from kaggle. The data consists of 
48 x 48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The training set consists of 28709 examples and the test set consists of 3589 examples. 
We have used csv files that recommend songs,movies,food activities based on the recognized emotions(happy,sad,neutral,disgust,anger,surprise,fear) 
Module-wise Description 
1. numpy - NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 
2. cv2 - OpenCV is an open-source computer vision and machine learning software library, used for image and video processing.It provides a wide range of functions for image processing tasks such as image filtering, segmentation, object detection, and recognition. 
3. PIL - is the Python Imaging Library, which provides powerful tools for opening, manipulating, and saving many different image file formats. The library provides an easy-to-use interface to perform operations like cropping, resizing, filtering, and enhancing images. It also supports advanced image processing techniques such as edge detection, contour detection, and image enhancement. 
4. tensorflow - TensorFlow is an open-source machine learning library developed by Google. It allows developers to build and train machine learning models to perform a variety of tasks, such as image and speech recognition, natural language processing, and
more.One of the key features of TensorFlow is its ability to perform distributed training and inference, allowing developers to train and deploy large-scale machine learning models across multiple devices and machines. 
5. pandastable - PandasTable is a package for interactive display and editing of pandas DataFrames in Jupyter notebook/lab or JupyterHub.The library provides a Table class that can be used to create interactive tables with features like sorting, filtering, and editing of data. 
6. gunicorn-Gunicorn is a widely used WSGI server that offers a simple and efficient way to run Python applications in a production environment. Its modular design allows for flexibility and customization in configuring and managing the server. 
7. threading - The threading module provides a simple way to run multiple threads concurrently. It allows for the creation of threads, synchronization between threads, and communication between threads. Threads are lightweight and allow for more efficient use of system resources than processes. This library is commonly used in applications that need to perform multiple tasks simultaneously, such as web servers or GUI applications. 
8. time - The time module provides various time-related functions. It includes functions for getting the current time, formatting time, measuring time intervals, and handling sleep operations. It is commonly used in applications that need to time operations or delays, such as simulations or waiting for resources to become available. 
9. pandas - Pandas is a library for data manipulation and analysis. It offers data structures and functions needed to work with structured data seamlessly. 
10. keras.models - The models module of Keras provides a high-level API for creating and training deep learning models. It includes various pre-built models, including sequential models, which allow for the creation of deep learning models layer-by-layer. 
11. keras.layers - The layers module of Keras provides a collection of built-in layers that can be used to build neural network models. These layers include dense, convolutional, pooling, and dropout layers, among others. 
12. keras.optimizers - The optimizers module of Keras provides various optimization algorithms that can be used during training to minimize the loss function. The Adam optimizer is one such algorithm that is commonly used in deep learning. 
13. keras.preprocessing.image - The preprocessing module of Keras provides various tools for preprocessing image data. The ImageDataGenerator class is used for generating batches of augmented image data during training. 
Project Components:. 
- haarcascade is for face detection. 
- camera.py is the module for video streaming, frame capturing, prediction and recommendation which are passed to main.py. 
- app.py is the main flask application file.
- index.html in 'templates' directory is the web page for the application. Basic HTML and CSS. - train.py is the script for image processing and training the model.
  Conclusion:- 
The Emotion-Based Music Player is a cutting-edge technology that provides a unique and automated music player experience for its users. Unlike other applications that can be tedious and frustrating, this system offers an improved level of interaction with the user. By using a camera to capture the user's image, the system can detect their current emotion and suggest a music,movies and activities. Our primary goal is to save users time while also providing them recommendation. 
