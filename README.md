## Introduction

This project aims to perform land segmentation using a UNet neural network architecture. The UNet architecture is a convolutional neural network (CNN) commonly used for image segmentation tasks.

## Overview

The project consists of the following components:

1. **UNet Model**: The UNet model is implemented using TensorFlow/Keras and trained on a dataset of earth terrain height and segmentation map images.

2. **Web Application**: The trained UNet model is deployed on a Flask web application, allowing users to upload their own images for land segmentation.

## Dataset

The dataset used for training the UNet model is available on Kaggle. You can access the dataset using the following link: [Earth Terrain Height and Segmentation Map Images](https://www.kaggle.com/datasets/tpapp157/earth-terrain-height-and-segmentation-map-images)

The dataset contains a collection of earth terrain height and segmentation map images, which are used for training and evaluation.

## Useage

To use the web application for land segmentation, follow these steps:

1. Clone the repository to your local machine:
   ```git clone https://github.com/iSathyam31/GeoSift.git```

2. Run the Flask application:
   ```python app.py```   

3. Access the web application in your browser .

4. Upload an image for land segmentation and view the segmented result.   

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the contributors of the UNet architecture and the authors of the dataset used in this project.
