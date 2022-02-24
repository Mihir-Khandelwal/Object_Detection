# Object Detection from Video
- Object is detected from video with the help of some python libraries like semantic_segmentation and pixellib. Here is an code for object detection from video within a span of 10 seconds.
- import pixellib
- from pixellib.semantic import semantic_segmentation
- segment_video = semantic_segmentation()
- segment_video.load_pascalvoc_model("deeplabv3_xception_tf_dim_ordering_tf_kernels.h5")
- segment_video.process_video_pascalvoc("video_path",  overlay = True, frames_per_second= 10, output_video_name="path_to_output_video")
