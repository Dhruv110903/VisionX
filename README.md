<h1 align="center">VisionX</h1>

## :innocent: Motivation
Welcome to my repository! This project leverages the power of machine learning, combining YOLOv5 and DeepSort, to enable real-time object detection through webcam, local video, and various streaming platforms. Our goal is to provide an intuitive and efficient solution for detecting objects accurately, making it accessible for diverse applications. Whether you're exploring computer vision or implementing object tracking in a specific domain, our tool aims to simplify the process and deliver reliable results. Dive in, explore, and contribute to this collaborative effort in advancing real-time object detection capabilities.

## :framed_picture: Demo

https://user-images.githubusercontent.com/37156032/160282244-42f6bd8c-bfc8-47af-8973-d3d199140e44.mp4

## :key: Features

<h3>For detailed insights, do check out my <a href="https://sahilchachra.medium.com/video-analytics-dashboard-for-yolov5-and-deepsort-c5994461cb44">Medium Blog</a></h3>

<ol>
    <li>Choose input source - Local, RTSP or Webcam</li>
    <li>Input class threshold</li>
    <li>Set FPS drop warning threshold</li>
    <li>Option to save inference video</li>
    <li>Input class confidence for drift detection</li>
    <li>Option to save poor performing frames</li>
    <li>Display objects in current frame</li>
    <li>Display total detected objects so far</li>
    <li>Display System stats - Ram, CPU and GPU usage</li>
    <li>Display poor performing class</li>
    <li>Display minimum and maximum FPS recorded during inference</li>
</ol> 

## :dizzy: How to use?
<ol>
    <li>Clone this repo</li>
    <li>Install all the dependencies</li>
    <li>Download deepsort <a href="https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6">checkpoint</a> file and paste it in deep_sort_pytorch/deep_sort/deep/checkpoint</li>
    <li>Run -> streamlit run app.py</li>
</ol>

## :star: Recent changelog
<ol>
    <li>Updated yolov5s weight file name in detect() in app.py</li>
    <li>Added drive link to download DeepSort checkpoint file (45Mb).</li>
</ol>

## :exploding_head: FAQs
<ol>
    <li><a href="https://github.com/SahilChachra/Video-Analytics-Dashboard/issues/5">How to use custom Yolov5 weight or DeepSort checkpoint file?</a></li>
    <li><a href="https://github.com/SahilChachra/Video-Analytics-Dashboard/issues/3">Unable to use webcam</a></li>
    <li><a href="https://github.com/ultralytics/yolov5/issues/6948">AttributeError: 'Upsample' object has no attribute 'recompute_scale_factor'</a></li>
</ol>

## :heart: Extras
Do checkout the Medium article and give this repo a :star:

## Note
The input video should be in same folder where app.py is. If you want to deploy the app in cloud and use it as a webapp then - download the user uploaded video to temporary folder and pass the path and video name to the respective function in app.py . This is Streamlit bug. Check <a href="https://stackoverflow.com/questions/65612750/how-can-i-specify-the-exact-folder-in-streamlit-for-the-uploaded-file-to-be-save">Stackoverflow</a>.
