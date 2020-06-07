# DataAnalytics4_Project
1) Masters program coursework for Data Analytics 4 module.

2) Topic assigned: Yolo

3) Anaconda environment setup notes:
Create Python 3.7 environment (e.g. conda create -n ce3da42 python=3.7)
conda install jupyter
conda install pandas
conda install neo4j
conda instlall pytz
conda create -n ce3da42 python=3.7
conda install keras
-- The environment packages are in the EnvPackagesList.txt file for reference (output of command "conda env export > environment.yml")

4) References used in the project:
Webiste: https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/
Github: On 05.06.2020, forked from https://github.com/jbrownlee/keras-yolo3 to https://github.com/rbewoor/keras-yolo3
Yolo weights link: link: https://pjreddie.com/media/files/yolov3.weights

5) Script: my_yolo3_one_file_to_detect_them_all_6.py
Action: Uses pre-trained Yolo v3 model for inference on images. The inference data is stored in a Neo4j database in the form of (:Image)-[:HAS]->(:Object). User provides a folder which contains all the images to process. Note: some images cannot be processed due to resizing issues and will be skipped.

