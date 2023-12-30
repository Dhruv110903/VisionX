<h1 align="center">VisionX</h1>

## About
Welcome ! This project leverages the power of machine learning, combining YOLOv5 and DeepSort, to enable real-time object detection through webcam, local video, and various streaming platforms. Our goal is to provide an intuitive and efficient solution for detecting objects accurately, making it accessible for diverse applications. Whether you're exploring computer vision or implementing object tracking in a specific domain, our tool aims to simplify the process and deliver reliable results with the convenience to choose the confidence, drift. Dive in, explore, and contribute to this collaborative effort in advancing real-time object detection capabilities.

## Demo

https://github.com/Dhruv110903/VisionX/assets/93207042/587583b4-1456-48bb-8962-28650dbfedc0

https://github.com/Dhruv110903/VisionX/assets/93207042/3894bd58-56e8-4b21-9cf9-15acaa6d94ab


## :key: Features

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

## How to use
<ol>
    <li>Clone this repository</li>
    <li>Install all the dependencies using the command pip install -r requirements.txt </li>
    <li>Download deepsort using the google drive link<a href="[https://drive.google.com/drive/folders/18_LAtz1yz1yWnD3G4a3fG_NIDSXVQlUT?usp=sharing](https://drive.google.com/drive/folders/18_LAtz1yz1yWnD3G4a3fG_NIDSXVQlUT?usp=sharing)"> Checkpoint </a> file and paste both the files in deep_sort_pytorch/deep_sort/deep/checkpoint</li>
    <li>Run the following command to run in LocalHost-> streamlit run app.py</li>
</ol>

