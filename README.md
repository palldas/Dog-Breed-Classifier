# Dog-Breed-Classifier

The data is sourced from the Kaggle Dog Breed Identification competition: https://www.kaggle.com/c/dog-breed-identification/data. It consists of a collection of 10,000+ labeled images of 120 different dog breeds. This is a multi-class image classification because there are multiple dog breeds (classes). 

**TensorFlow/Deep Learning workflow:**
1. 	Get data ready (download from Kaggle, store, import).
2. 	Prepare the data (preprocessing, the 3 sets, X & y).
3. 	Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
4.	Evaluating a model (making predictions, comparing them with the ground truth labels).
5.	Improve the model through experimentation (start with 1000 images, make sure it works, increase the number of images).

**Transfer Learning** - using a pretrained model and adapting it to your own problem. In this case, I am using a pretrained deep learning model from TensorFlow Hub (MobileNetV2).
