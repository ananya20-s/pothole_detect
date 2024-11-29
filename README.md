## Pothole Detection from street images

![image](https://github.com/user-attachments/assets/e7d4f0c5-41e1-4f5a-9ad7-696c1dfe3cfd)


### Description
The objective of this project is to build and train a model that can detect presence of potholes given a street-level image

### Features
Use a pretrained model and fine tune it against the pothole dataset from Roboflow to detect potholes.


### Dataset
The image dataset is sourced from [Roboflow](https://public.roboflow.com/object-detection/pothole) under applicable license. The dataset is split to 70/20/10 train-valid-test images.



### Results
Trained YOLOv11 model against the dataset to detect potholes with a mean Average Precision of around 70%


### Technologies Used
- **Tools:** Python, Google Colab
- **Libraries:** Pandas, Matplotlib, OpenCV, Ultralytics


### Next steps

- Provide examples of more street images to avoid misclassificaion of regular objects found on street like traffic cones, road-repair tools, etc
- Explore the annotation tools available to build a dataset with labels indicating severity of potholes
- Build an Image Segmentation dataset that can correctly identify the areas for repair in the model
- Geotagging the images for easy identification of potholes location
