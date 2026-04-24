# [BHeri GPT](https://abhishekraje2004.github.io/BHeriGPT/)
## A Large-Scale Movement Dataset of Daily Activities in the Indian Context
### **Abstract**

 We present BHeriGPT, a high-fidelity movement dataset of daily activities performed by Indians. The dataset consists of 16 subjects performing various activities, including domestic chores, exercises, and yoga postures. We provide pose estimation metrics extracted from state-of-the-art pose estimation models like motionagformer, mhformer, poseformerv2, and mediapipe on this dataset, evaluated across 4 camera viewing angles, along with segment length errors relative to the ground truth. We also provide the SMPL- style representation for our dataset processed obtained using the motion-capture system as support for this work We believe this dataset can have a significant impact in the fields of robotics, computer vision, and personalized rehabilitation technology by providing biomechanically grounded human movement sequences. 

### **Data Format**

We process the high frequency sampled motiom capture data consisting of 43 optical markers using [moshpp](https://github.com/nghorbani/moshpp) to obtain the [SMPL-H](https://mano.is.tue.mpg.de/) models consisting of 52 joints as a .npz file. We perform a common subject wise shape estimation using mosh followed by a framewise pose estimation for each activity in the dataset. The data is subsampled to $50$ Hz to retatin a compact data represntation. Kindly refer to the [AMASS](https://github.com/nghorbani/amass) for details regarding visualzing these smpl figures.




<img src="static/images/S17_Vrikshasana_Trial1_stageii.gif" width="200">  <img src="static/images/S14_ForwardLungeRight_Trial1_stageii.gif" width="200">  <img src="static/images/S4_Parshvakonasana_Trial2_stageii.gif" width="200"> <img src="static/images/S1_Point1_Trial14_stageii.gif" width="200"> 


