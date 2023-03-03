
# Car Plate Detection (Iran's Format)

This project has been done only to try yolov7.

In this project, yoloV7 is used to detect car license plates (Persian numbers). Its dataset was taken from the kaggle website, which contains 844 car images. Using Roboflow, the images have been segmented along with their labels. Also, the number of images has been increased to 2026 by augmentation. 70% of them are used for training, 20% for validation and 10% for testing.
Batch = 16, epoch = 40 and the weight of Yolov7 have been considered. As you can see in the result file, the mAP is 99% and the precision is 96.5%.


dataset: https://www.kaggle.com/datasets/amirhoseinahmadnejad/car-license-plate-detection-iran

Roboflow: https://app.roboflow.com/



