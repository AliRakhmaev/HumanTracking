# HumanTracking
Implemantation of the human tracking system on videos using the YOLO3 model with SORT algorithm support 
### Preparation:  
#### First, before you run this, you’ll need to run the download_weights.sh script in the config folder to download the Yolo weights file. 
#### Next, please install these modules to your interpreter (for example Anaconda frameword) or insure that they already installed:
1) OpenCV  
2) PyTorch > 1.0.0
#### Finally, install all dependencies from requirements.txt
### How to use
Typical call looks like this: ```object_tracker.py -v "videos/TownCentreXVID.avi"
There the -v means path to video including the file name and extension (.avi and .mp4 are tested). Here path is "videos/TownCentreXVID.avi" and it is <b>relative</b>.

### Special acknowledgments
To Chris Fotache for his knowledge, advices and great articles. Link: https://towardsdatascience.com/object-detection-and-tracking-in-pytorch-b3cf1a696a98  
To Joseph Redmon and Ali Farhadi for their great model named YOLO. Link: https://pjreddie.com/darknet/yolo/  
To Alex Bewley for his part in developing the SORT algorithm and its implemantation. Link: https://github.com/abewley/sort
