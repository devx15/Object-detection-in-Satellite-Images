# Object-detection-in-Satellite-Images

Object Detection on the Satellite Images

DYSL-AI, DRDO


## •	Introduction:
This report explores the application of YOLOv3 (You Only Look Once version 3) for object detection in satellite imagery. By leveraging YOLOv3, we aim to enhance the efficiency and accuracy of object detection in satellite images, enabling improved analysis and interpretation of remote sensing data. This report provides an overview of the YOLOv3 algorithm, its use in satellite image analysis, and an evaluation of its performance using real-world datasets.

## •	Algorithm for Object Detection using YOLOv3:
1. Pre-trained YOLOv3 weights and configuration should be loaded.
2. Reduce the size and normalize the satellite image.
3. Use the YOLOv3 network to generate feature maps from the preprocessed image.
4. Use non-maximum suppression to get rid of redundant or overlapping detections.
5. Provide a list of the last detected objects along with their bounding boxes and class labels.
6. Show the discovered items on the original satellite image.
Note: The YOLOv3 algorithm and its implementation details can be found in the original paper "YOLOv3: An Incremental Improvement" by Joseph Redmon and Ali Farhadi (2018).



## •	My Contribution:
1.	Dataset Preparation
I contributed significantly to the dataset preparation stage of the project, which was essential to the working of the object detection system employing YOLOv3 on satellite photos. In order to ensure a wide range of geographic regions, resolutions, and weather conditions, I undertook substantial study to gather a comprehensive dataset of satellite photos from multiple sources. I carefully preprocessed the data to ensure consistency, downsizing the photos to a standardized input size, and normalizing the pixel values. My contribution placed a lot of emphasis on the annotation process, where I precisely labelled objects of interest by drawing exact bounding boundaries and assigning suitable class names. All along, quality control checks were in place to ensure dataset integrity and resolve any inconsistent annotations.
2.	Model Optimization
I actively engaged in fine-tuning various model hyperparameters to adapt the architecture specifically to the characteristics of the satellite imagery. I conducted thorough experimentation and analysis to determine optimal values for parameters such as learning rate, batch size, and anchor sizes. By carefully adjusting these hyperparameters, I aimed to strike a balance between model convergence, detection accuracy, and computational efficiency. Additionally, I explored different regularization techniques, such as dropout and weight decay, to mitigate overfitting and improve generalization. Furthermore, I investigated the effects of adjusting the network depth and width to optimize the trade-off between model complexity and performance. Through systematic evaluation and iterative refinement, I contributed to improving the accuracy and efficiency of the YOLOv3 model for object detection in satellite images, ultimately maximizing its potential for real-world applications.
3.	Results Analysis and Documentation
 I played a crucial role in analyzing the object detection results obtained from the YOLOv3 model on the test dataset. I carefully examined the detected objects, their bounding boxes, and class labels in the context of satellite imagery. I documented the findings, insights, and limitations of the object detection system in a comprehensive and clear manner, contributing to the overall report's quality and value.

## •	Limitation/Drawback:
One drawback of the YOLOv3 method for object detection in satellite photos is how well it performs in difficult situations. The algorithm may have trouble with items that are small in size or have poor contrast compared to their surroundings, despite its general accuracy and efficiency. This restriction may result in situations where the system is unable to detect objects or generates unreliable bounding box predictions. As it relies on anchor boxes and non-maximum suppression approaches for localization and suppression of overlapping detections, YOLOv3 may also have trouble recognizing objects that are partially obscured or tightly grouped together. Although efforts have been made to improve the algorithm, these drawbacks show the need for additional study and YOLOv3 fine-tuning, especially in handling complex and challenging scenarios commonly encountered in satellite imagery.

## •	Results:
The results of implementing YOLOv3 for object detection on satellite images were remarkable. Even though it was taught to recognize a single object at a time, it will detect the majority of the same type of objects.

## Resources:
Original Repository: https://github.com/AlexeyAB/darknet

Darknet framework: http://pjreddie.com/darknet/



