# Roadside-Deer-Classification-Project
> Overview
This project develops a computer vision machine learning model to identify animals in roadside images. The initiative aims to reduce roadkill by integrating the model with traffic cameras. A unique feature of this model is its ability to classify animals not only by species but also by gender, such as distinguishing between bucks and does in deer. This added dimension of gender classification serves as a stepping stone to recognize finer distinctions among animals, inspired by easily observable differences like antlers in deer. Such features, although seemingly minor, can be crucial in differentiating species that appear similar, paving the way for more nuanced ecological studies and conservation efforts.

> Project Steps

1. Define Project Objectives and Requirements
- Specify the types of animals and their characteristics (including gender) the model needs to identify.
- Set accuracy and performance metrics for the model.
  
2. Data Collection
- Utilize Open-Source Datasets such as iNaturalist and ImageNet for diverse animal images.
- Annotate images with detailed labels, including species and gender.

3. Data Preprocessing
- Image Filtering: Ensure clarity and appropriate lighting conditions.
- Format Standardization: Normalize image sizes and resolutions.
- Data Augmentation: Enhance the dataset via image modifications.

4. Model Design
- Opt for a Convolutional Neural Network (CNN) framework, with a focus on models like YOLO for real-time object detection.
- Customize the model architecture to align with project requirements.

5. Train the Model
- Train using the prepared dataset and refine parameters for optimal performance.
- Inspiration:
https://universe.roboflow.com/finalroadsideproject/roadside_project
   Draw inspiration from projects like Roadside Deer Classification, aiming to extend capabilities by identifying gender and behavior patterns.

6 Test the database images
- Evaluate performance on a diverse set of images, including challenging scenarios like nighttime and deer near vehicles.

> Results:
The YOLOv5 model demonstrated excellent proficiency in identifying different deer types, achieving a precision of 82.9% for males and 88.8% for females. These results underscore the model's effectiveness in gender differentiation.

> Future Plans
- Upgrade to a more advanced version, such as YOLOv8, to improve motion tracking and address time and configuration limitations encountered previously.
- Focus on enhancing model accuracy in low-light conditions and complex scenarios involving vehicles, as initial tests have shown reduced accuracy in these areas.


