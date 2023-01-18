# Object-Detection-APK
Mobile App Object detection to detect mask and no-mask faces 
The code in YOLOv5_for_Object_Detection.ipynb was taken from the following video https://youtu.be/ROn1_O2zEtk Also the steps used.

Steps Performed:

1- Train yolov5 model

2- Convert yolov5 (.pt model) into a tensorflow model(.pb file)

3- Convert tensorflow model (.pb model) to tflite model.

4- Download and install Android Studio

5- Build and run your Object detection App.

THE DATASET
The dataset we can use two ways: we can use the code that is in the .ipynb file or we can download the dataset that is in the repository. 
It is important to mention that for training the model we have change the name of the file that has the dataset to the name 'dataset'.
Also, we have to take the dataset.yaml and paste in the folder yolov5/data.
