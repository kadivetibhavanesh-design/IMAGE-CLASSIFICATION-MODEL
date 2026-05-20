# IMAGE-CLASSIFICATION-MODEL

"COMPANY": CODTECH IT SOLUTIONS

"NAME": KADIVETI BHAVANESH

"INTERN ID": CTIS9380

"DOMAIN": MACHINE LEARNING

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTOSH

# DESCRIPTION OF TASK  : CNN BASED IMAGE CLASSIFICATION MODEL

This project focuses on developing an Image Classification Model using Convolutional Neural Networks (CNN) and TensorFlow. Image classification is a process in which a computer system is trained to identify and classify images into different categories based on their visual features. In this project, a Deep Learning model was trained to recognize handwritten digits using the MNIST dataset.

The MNIST dataset is one of the most widely used benchmark datasets in Machine Learning and Computer Vision. It contains 70,000 grayscale images of handwritten digits from 0 to 9. Each image has a size of 28 × 28 pixels. Out of the total dataset, 60,000 images are used for training the model and 10,000 images are used for testing the model. The dataset is already available in TensorFlow and can be loaded directly without downloading it manually.

The project was implemented using Python programming language with the help of TensorFlow, Keras, and Matplotlib libraries. TensorFlow and Keras were used for creating and training the CNN model, while Matplotlib was used for displaying sample images and prediction outputs.

The first step in this project was loading the MNIST dataset. After loading, preprocessing techniques were applied to improve model performance. The pixel values of the images were normalized by dividing them by 255 so that all values fall between 0 and 1. This normalization process helps the neural network train faster and improves accuracy.

The next step involved reshaping the dataset into the required format for the CNN model. Since CNN models process image data with channels, the images were reshaped into 28 × 28 × 1 dimensions, where “1” represents the grayscale channel.

The Convolutional Neural Network model was then designed using multiple layers. The Conv2D layers were used to extract image features such as edges, curves, textures, and patterns. These layers help the model identify important details from handwritten digit images. MaxPooling layers were added after convolution layers to reduce image dimensions and improve computational efficiency.

After feature extraction, a Flatten layer was used to convert the image matrix into a one-dimensional vector. Dense layers were then used for classification purposes. The final output layer used the Softmax activation function to classify the image into one of the ten digit classes ranging from 0 to 9.

The model was compiled using the Adam optimizer and sparse categorical crossentropy loss function. Accuracy was used as the evaluation metric. The CNN model was trained for multiple epochs using the training dataset. During training, the model continuously learned patterns from thousands of handwritten digit images and improved its prediction capability.

After completing the training process, the model was evaluated on the testing dataset. The CNN model achieved approximately 99% test accuracy, which indicates excellent classification performance. The trained model was also used to predict sample handwritten digit images from the test dataset.

For example, when a handwritten image of digit “7” was provided to the model, it successfully predicted the output label as “7”. This confirms that the CNN model effectively learned image features and classification patterns from the training dataset.

This project demonstrates the practical implementation of Deep Learning and Image Classification techniques using CNN architecture. It also provides understanding about image preprocessing, neural networks, feature extraction, training, prediction, and performance evaluation.

Overall, the project successfully implemented a CNN-based image classification system using TensorFlow and achieved high accuracy on the MNIST dataset. The task highlights the importance of Deep Learning in modern image recognition applications such as face recognition, medical imaging, handwritten text recognition, and object detection systems.

