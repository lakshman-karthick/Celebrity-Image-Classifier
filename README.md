
# Celebrity Image Classifier

- A Web Application to classify the famous personalities by click and drop the photograph. 
- Classifiers’ task is to take an input and to output a class label (extract the image features and predict the category).

- Machines don’t analyze a picture as a whole. They only analyze a picture through pixel patterns or vectors. 

- They will then categorize and assign labels to the elements they detect and classify them depending on the different rules that have been set up when configuring the algorithm.

## Justification:

- Various methods can be used for image classification , but to bring the best result out of it , we had tried these following features . In this project, OpenCV haarcascade was used to detect face and two eyes. 

- Wavelet transform was used to extract these features from the images. Finally after processing and cleaning the data, it was given as input to models. 

- Various models were tried using GridSearchCV and Support Vector machine(SVM) was found to give the best results.

## Dataset Description:

#### Details about the dataset:
• 100 images of each celebrities is downloaded from Google.

• Data cleaning of images is done using OpenCV Haarcascade where the face and the eyes of
the celebrity is detected and cropped.

• The images where face and eyes are not visible properly will be removed from the dataset.
OpenCV Haarcascade:

• Object Detection using Haar feature-based cascade classifiers is an effective object detection
method

• It is a machine learning based approach where a cascade function is trained from a lot of
positive and negative images. It is then used to detect objects in other images.

• They are just like our convolutional kernel. Each feature is a single value obtained by
subtracting sum of pixels under the white rectangle from sum of pixels under the black
rectangle.

• Convolution is using a ‘kernel’ to extract certain ‘features’ from an input image

## Algorithm:


    model	                  best_score	
	svm	                   0.918322	
	random_forest	           0.865342	
	logistic_regression	   0.902869




