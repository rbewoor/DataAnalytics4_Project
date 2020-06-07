# DataAnalytics4_Project
Masters Coursework for Data Analytics 4 coursework.

References used in the project:
Webiste: https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/
Github: On 05.06.2020, forked from https://github.com/jbrownlee/keras-yolo3 to https://github.com/rbewoor/keras-yolo3
Yolo weights link: link: https://pjreddie.com/media/files/yolov3.weights

Script: my_yolo3_one_file_to_detect_them_all_6.py
Action: Uses pre-trained Yolo v3 model for inference on images. The inference data is stored in a Neo4j database in the form of (:Image)-[:HAS]->(:Object). User provides a folder which contains all the images to process. Note: some images cannot be processed due to resizing issues and will be skipped.
