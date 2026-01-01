# MRI-Understanding

This is not a project or something. Just a key undenrstanding. For image segmentation mainly brain tumor segmentation Unet architecture has been used for a long days. 
Here we try to understand with the segmentation and classification of tumor type rather than using efficient-net or other types of CNN architecture how Unet will perform on it with a Fully Connected Layer introduced. 
So we used UNet with resnet-34 backbone and trained them. For choosing an optimal value we will stuck into the first analysis. The last analysis looks redundent to us and not an optimal solution as we think that with the threshold values used the result may not perform will with the real world situation. Further tests and research may change this notation. However the differnce is not too large. The decision boundary was not extended too much. 
Here we followed the result with dice loss first only for fun but we choose the result based on categorical crossentropy. Another we used earlystopping for saving the best parameter and we also used Adadelta as optimizer for stabilization issues. We got certain high accuracy,precision and recall score. But we do value the validation loss. We used the minimum validation loss for inconvenience. 
So based on that the model is given. It was an experimental project. 


Code is based on kaggle. Fix your path. The dataset link https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data  
Kaggle Notebook link https://www.kaggle.com/code/ezsharaf/trust-mri-99-16  
Model link kaggle kernels output ezsharaf/trust-mri-99-16 -p /path/to/dest
