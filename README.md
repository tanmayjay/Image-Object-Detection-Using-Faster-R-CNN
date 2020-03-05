# Image-Object-Detection-Using-Faster-R-CNN
This project has beeen using based on some documentations code. The original authors are mentioned in the referenced papers.
It can detect multiple objects in an image and identify the image class.

For training we took the “Google Open Image Dataset with Bounding Boxes V4”. In the dataset there are bounding box annotations, image urls for the source of the images, and class descriptions. We selected 8 classes for our training and filtered randomly 1000 images per class. Then we stored the corresponding images by crawling the given urls on the web. We divided the images in 80:20 ratio for training and testing considering each classes and the extracted those images using their annotation information. After all the training dataset is containing 26253 data for 6395 sample images, and the test data is containing 6532 data for 1598 sample images. Thus the preprocessing of the dataset is done.

The full project with the model file can be found in the link below:
https://bit.ly/2xds5ye
