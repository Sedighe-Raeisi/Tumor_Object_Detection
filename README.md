# Tumor Object Detection   
In this project I used the MRI image dataset with tumor in the link:    
https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection    
Then I used the https://www.makesense.ai/ to annotate these images. I considered two class of objects: label=0 for tumor and label=1 for brain.   
Then I trained the YOLO-V5 for 40 epochs and batch size=10   
In the following image you van see the prediction for some images:   
![image](https://user-images.githubusercontent.com/67642255/152169986-a924bc13-a2d7-4c85-9ab3-9f474f4046e9.png)   

Here is the confusion matrix:  
![image](https://user-images.githubusercontent.com/67642255/152169624-13962f34-7243-4a3b-84a9-26b8c98fcd4d.png)   

