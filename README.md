Data Collection:
I spent a lot of time searching for a dataset online but found none that would suit the video and then I decided to make one of my own, I found a 
few videos that were provided online from the students of IIT Hyderabad. As the video was very long I decided to extract frames every 
15 seconds of the video which resulted in a dataset containing 624 images which I then individually labelled on roboflow. As the dataset was very small 
for the task assigned, I decided to use data augmentation on the dataset. The dataset is still small but the detections it produced are pretty surprising
with a fairly good precision and recall but yes the model can still be improved with a bigger and more vast dataset.

I used Yolov5(Pytorch), an advanced object detection model, to train and perform detection on the videos.
