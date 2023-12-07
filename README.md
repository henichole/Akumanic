# Roadside-Deer-Classification-Project
Overview
This project aims to develop a machine learning model for computer vision that identifies animals in roadside images. The goal is to label and magnify animals in the images, categorizing them by species. This initiative is targeted at reducing roadkill by integrating the model with traffic cameras.

Project Steps

>1. Define Project Objectives and Requirements
1.	Specify the types of animals the model needs to identify.
2.	Set accuracy and performance metrics for the model.

>2. Data Collection
1.	Open-Source Datasets: iNaturalist, ImageNet, etc., provide a wealth of animal images for training.
2.	Data Labeling: Annotate each image with the category of the animal it contains.

>3. Data Preprocessing
1.	Image Filtering: Ensure images meet quality standards (clarity, lighting conditions, etc.).
2.	Format Standardization: Normalize image sizes and resolutions.
3.	Data Augmentation: Expand the dataset by altering images (rotating, flipping, etc.).

>4. Model Design
1.	Choose a Framework: I’m thinking to use CNN (Convolutional Neural Networks) or similar.
2.	Design Architecture: Tailor the model's structure to meet project needs.
3.  Convolutional Neural Network (CNN) based model is usually a good choice. Specifically, models like YOLO (You Only Look Once) are highly effective for real-time object detection, which makes them suitable for this project.

>5. Train the Model
1.	Train the model using the prepared dataset.
2.	Adjust parameters to optimize performance.
3.	Inspiration:
https://universe.roboflow.com/finalroadsideproject/roadside_project
   This is a well developed project on classifying the roadside deer, however, the project could be improved by further identifying the gender (buck or doe), standing position (standing, eating, etc). 

>6 Test the database images
1. Overall Good performance
2. To conclude, the YOLOv5 model has shown remarkable capability in detecting and differentiating between types of deer. These results not only validate the effectiveness of our model but also open avenues for its application in wildlife monitoring and ecological studies.
If I have more time in the future: I would use the more updated version (YOLOV8 – failed this time due to time and configuration limitations) to tract the motions of the deer as well.

Results:
“Breaking it down, the model‘s performance on different deer types was noteworthy. For males, it achieved a precision of 82.9% and for females, an even higher precision of 88.8%. This demonstrates the model's ability to differentiate between various deer types effectively."




