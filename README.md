# YOLOv4-Grocery-Product-Detector

The task allotted to me was to build an object detction model which can detect items kept on shelves in a grocery or a supermarket.

I have build this moidel using YOLOv4 algorithm, which is based on the darknet. Implementing an YOLO Algorithm is highly complex and very time consuming. I will walk you through the approach I have followed to create this model.

## **Dataset**

The dataset used for this task can be downloaded via following link:
https://github.com/gulvarol/grocerydataset

This dataset contains images of cigarette packs of different brands kept on various shelves. It also contains annotations of those images in a text file.

I have used the **ShelfImages** folder for the training and testing of this model. I splitted the images of this folder in two different sub-folders, having names **train**, containing 283 images and **test**, containing 71 images. I have then zipped the **ShelfImages** folder and uploaded it in my google drive in a **yolov4** folder.

Link to my **yolov4** in my google drive is given below:
https://drive.google.com/drive/folders/1HkjUN-JPATAL7v4VFbb-NwHFPW0uQsqe?usp=sharing
