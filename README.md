# Face_Recognition

The model uses the k-nearest neighbors algorithm for recognizing the face of a person in real time. KNN Algorithm can be used for both classification and regression problems , but it is widely used in classification problems in the industry.

We can implement a KNN model by following the below steps:

(a) Load the data.

(b) Initialise the value of k.

(c) For getting the predicted class, iterate from 1 to total number of training data points.

(d) Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method. The other metrics that can be used are Chebyshev, cosine, etc.

(e) Sort the calculated distances in ascending order based on distance values.

(f) Get top k rows from the sorted array.

(g) Get the most frequent class of these rows.

(h) Return the predicted class.

To work with the webcam for the video stream and to generate selfie training data , OPENCV is used.

Tasks implemented during training data phase are :-
(a). Capture Images after reading the video stream.
(b). Detecting faces and show boundary box.
(c). Flattening the largest face Image and save it in a numpy array. 

Real Time Example :-

![f1](https://user-images.githubusercontent.com/41800767/77418459-ec286080-6dec-11ea-92c6-60ec333d1c14.png)
