# Object Detection from Video
- Object is detected from video with the help of some python libraries like semantic_segmentation and pixellib. Here is an code for object detection from video within a span of 10 seconds.
- You can view the code saved as video.py in this repository only.
- First two lines we have imported the necessary libraries.
- Next, we have imported in the class for performing semantic segmentation and created an instance of the class.
- Line 4, we have loaded the xception model trained on pascal voc dataset to perform semantic segmentation.
- Lastly, we have called the function to perform necessary semantic segmentation. "video_path", here we need to give the path of our video to be segmented, frames_per_second = 10, means we set the number of frames per second for the saved video file, the output video file will contain 10 frames per second. "path_to_output_video", here we need to specify the path to the output video, by default it will save it in the current working directory.

# Object Detection from Image
- Object is detected from image with the help of some python libraries like imageai.Detection and os. Here is an code for object detection from image.
