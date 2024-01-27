# Road_detection_using_Semantic_segmentation
Identification of drivable path using Semantic segmentation

--------READ ME---------------

THE CODE FILES ARE ALL IN .ipynb FORMAT. 

----DESCRIPTION----

--> The file U-net loss curves has training curves and trained model (U-net with Resnet 18 encoder)
--> The file U-net outputs has the model deployed on our own test data and outputs for U-net model.
--> The file DeepLabv3 contains model trained, deployed and tested on test data (DeepLabv3)
--> .pth files contain the saved models, that can be imported into the code

----DATA-----

--> Training data is taken from Cityscapes dataset and extracted in the colab notebook file. 
Here's the link-- https://www.cityscapes-dataset.com/downloads/

Download the following :
1. gtCoarse.zip (1.3GB) [md5]
2. leftImg8bit_trainvaltest.zip (11GB) [md5]


----GENERAL INSTRUCTIONS----

--> The model is being trained in the colab notebook, it might take several hours to finish training. Hence we included outputs from the already run cells in the .ipynb files as well as report pdf.

--> If Nvidia GPU is absent, run the code on colab with runtime gpu.
