# Sprint-15-Project

Project Description
It is useful to conduct EDA before rushing into modelling, even while working with sophisticated models like neural networks. So, let's have a look at the data for this project.

Data description
The dataset was obtained from ChaLearn Looking at People. It was prepared for the project and placed in the /datasets/faces/ folder, there you can find

The final_files folder with 7.6k photos
The labels.csv file with labels, with two columns: file_name and real_age
As the number of image files is rather high, it is advisable to avoid reading them all at once, which would be resource consuming, and to read them sequentially with the ImageDataGenerator generator. This method was explained in Chapter 3. Convolutional neural networks, Lesson 7. Data Generators.

Your task
Perform the exploratory data analysis:

Look at the dataset size.
Explore the age distribution in the dataset.
Print 10-15 photos for different ages on the screen to get an overall impression of the dataset.
Paths to the files for analysis: 

'/datasets/faces/labels.csv'
'/datasets/faces/final_files/'
Provide findings on how the specifics of the dataset you discover may affect how the model is trained.

Save the notebook under a meaningful name.
