# Face_Recognition_System

A face Recognition system for 2.5 lakh unique faces using a multi-level KNN clusters and a ResNet-34 model.Recognition involves
pre-processing (face detection & landmark generation + alignment) and then inference using resnet34 model. The KNN structure
involve 4 layers and each layer node have maximum of 9 levels. The final output is a HashMap with keys of type int and value is
array of normalized vector for future recognition purpose.
