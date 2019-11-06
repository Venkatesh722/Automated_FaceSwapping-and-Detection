# Automated_FaceSwapping-and-Detection
We swapped faces of two different images and the resultant image(swapped image) is detected if the image is swapped or not

#Photos swapping of two differnet images

1.Open the photos_face_swapping.py and set the path of images of your laptop.
2.For running this code we need some libraries to install in python such as opencv , dlib and numpy.
3.For detecing the landmarks of images we need to download the "shape_predictor_68_face_landmarks.dat" which you can download from internet and put this file in current working directory.

#Generating the dataset from a set of non-swapped-images

1.Open the generate_dataset.py and the set the path to dataset in the code and run the code this will generate the swapped images.

#Training the model using swapped images and non-swapped images

1.Run the code train.py and put the images in train (swapped and non-swapped) and also in test.
2.This will generate the trained models into the current working directory.

#Test the model or predict the model

1.Open predict.py and give the path of the image which you want to check whether the image is swapped or not.
2.Result will show whether the image is original or swapped .If the image is swapped then it will show the swapped area around the image.






