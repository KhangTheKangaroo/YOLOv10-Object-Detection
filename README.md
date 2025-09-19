# YOLOv10-Object-Detection #

## Object Detection with YOLOv10

## PLEASE RUN IN GOOGLE COLLAB

- Switch Runtime Type to GPU

![image](https://github.com/KhangTheKangaroo/YOLOv10-Object-Detection/assets/171163677/290a7e67-563c-48e9-9793-4ee6e74114c2)

  
![image](https://github.com/KhangTheKangaroo/YOLOv10-Object-Detection/assets/171163677/cc582590-51a5-40ea-a4d9-097f200d3fa1)

- Run Objection_Detection_py.ipnyb File (Run the code **ONE BY ONE**)
- Download helmet_safe_best.pt
- Run the last cell of code

# Running in Anaconda Environment

- Download Anaconda
- In CMD Prompt (Window Built-in) type: git clone https://github.com/heartexlabs/labelImg.git
- In Anaconda Prompt type (***ONE BY ONE***):
  
          + conda create -n labelImg_env python=3.9 -y
          + conda activae labelImg_env
          + cd <path_to_labelImg_folder>
          + conda install pyqt = 5
          + conda install -c anaconda lxml
          + pyrcc5 -o libs/resources.py resourcs.qrc
  
- Activate environment, type: python LabelImge.py (In Anaconda Prompt)
- In predefined_classes.txt, enter the classes (Basically the classification of "entities" or "objects" in your images/Each class is a separate line)
- Change format to YOLO
- In each of the photo, click "RectBox" and "boxed out" the objections/entities in your classification
- Save and there will be a txt file with coordinates of each object
