

Here are the explanation of the what it is included in the Supplementary file:


    1. mhist_dataset is a folder containing two subfolders, including the images and their annotations, for the MHIST dataset. All 3152 images are in images.zip file. Annotations are included in annotations.csv. Note that this file includes each image file name and its corresponding majority-vote label and degree of annotator agreement expressed as the number of annotators who marked the image as SSA (e.g., 6 indicates 6/7 agreement with a ground truth of SSA and 2 would indicate 5/7 agreement with a ground truth of HP).

    2.Task1-final.ipynb is a Python notebook showing how the teacher and student models are training in conventional KD framework. Conventional KD for MNIST dataset is implemented here.
    
    3.Task2-final.ipynb is a Python notebook for MHIST dataset with teacher and student models again but using the pre-trained ResNet50V2 and MobileNetV2 architectures.




