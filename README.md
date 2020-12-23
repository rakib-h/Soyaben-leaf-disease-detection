# Soyaben-leaf-disease-detection
Soybean leaf disease is the most common disease(Bacterial Diseases) in our country for planting soybeans. Farmer loss their most valuable asset and didn't generate money as well as they expected when the plant got affected. From there, I decided I want to do something for them to solve this. I collect 13k affected images from the field and work with these images for preprocessing and data annotation and model building. Sounds good to see when it give me good accuracy.

###### I used 1 classes to predict for Bacterial Diseases named as 'disease'

#### Requiremnts

- Protobuf 3.0.0
- Python-tk
- Pillow 1.0
- lxml
- tf Slim (which is included in the "tensorflow/models/research/" checkout)
- Matplotlib
- Tensorflow
- Cython
- contextlib2
- fasterRCNN

#### Tensorflow-model
The TensorFlow Model Garden is a repository with a number of different implementations of state-of-the-art (SOTA) models and modeling solutions for TensorFlow users. We aim to demonstrate the best practices for modeling so that TensorFlow users can take full advantage of TensorFlow for their research and product development. For, more info click the following link: [Tensorflow Model](https://github.com/tensorflow/models/tree/master/research/object_detection).

## Fresh soyabean leaf
<img src="sample images/fresh.jpeg" width="800" height="400">
## Affected leaf
<img src="sample images/affected1.jpeg" width="800" height="400"> <img src="sample images/affected2.jpeg" width="800" height="400">

## Predicted output
<img src="output_Images/soyabean_disease.jpg" width="1100" height="700">
