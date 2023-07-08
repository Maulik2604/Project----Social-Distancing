# Project----Social-Distancing

This project uses Yolo V3 to detect whether people are following social distancing norms.

When we run the social_distance_detector.py file it processes the video with the help of yolo-weights, which were generated by training on coco-dataset. And then saves the output with the name of outut.avi.

A real-time detection will also take place in a pop-up window.

The script takes various arguments which can be understood by runing the script with --help or -h flag.

For testing purpose you can simply use the following command bu first you have to download the yolo-weights file from the below drive link and save it in the yolo-coco directory.

Command to run the model is:-

python detector.py --input pedestrians.mp4 --output output.avi --display 1

(This command needs to be executed on the command prompt)
