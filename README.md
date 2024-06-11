# A database containing images of coffee and white beans for seed size detection

The dataset consists of images used for training and testing the YOLO network aimed at detecting coffee beans and white beans. 

# Data
The dataset consists of images used for training and testing the YOLO network aimed at detecting coffee beans and white beans. It includes a total of 100 images, with 50 designated for the training set and the other 50 for the testing set. 
For each image, both in the training and testing sets, a JSON file generated using the Labelme software is attached. These files provide detailed descriptions of the shapes of each bean in the images, allowing for precise training and evaluation of the detection model.

In each photo, as a reference object, a 1 złoty coin with a diameter of d=23 [mm] and an area of P=415.48 [mm²] is placed.

# Results 
In the "results" directory, photos of the detections are stored along with the calculated dimensions of the seeds, including height, width, and the calculated area.



