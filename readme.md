# TinyML (Tiny Machine Learning) Mask Detection Application

Using Transfer Learning, the model detects whether a person is wearing a mask or not. Used a pre-trained model (MobileNet-V1) trained on the ImageNet dataset and used a modified version of [kaggle mask dataset](https://www.kaggle.com/prasoonkottarathil/face-mask-lite-dataset) to perform transfer learning. 

### Training & Inference

> Model is trained using Tensorflow, the convolutional layers of pre-trained model are freezed and a classification head is added. When working with a small dataset, it is a common practice to take advantage of features learned by a model trained on a larger dataset in the same domain.