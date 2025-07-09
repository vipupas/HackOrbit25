<h1>🚦 <b><u>AI-Powered Traffic Light Management System</u></b></h1>

HackOrbit 2025 | Team: CodeRonin

<h2>Theme : </h2>

  <h4>Artificial Intelligence and Machine Learning</h4>
<h2>Problem Statement : </h2>

  <h4>Modern cities face severe traffic congestion due to non-adaptive traffic light systems that:</h4>

<h2>Proposed Solution : </h2>

  <h4>An AI-powered dynamic traffic signal system that: </h4>

    Analyzes real-time traffic density using CCTV feeds

    Dynamically adjusts green light durations per lane

    Gives priority to emergency vehicles

    Supports deployment on edge devices (e.g., Raspberry Pi, Jetson Nano) or remote servers
<h2>🧰 Software & Tools</h2>

    Python
    OpenCV
    TensorFlow / PyTorch
    YOLO8 / SSD object detection models

<h2>Proportionally divide time based on density</h2>

<h4>We calculate the share of green time for each road:</h4>
    
    green_time_road_i = (vehicles_on_road_i / total_vehicles_on_all_roads) * total_time

<h2>Test Video Link :</h2>
https://youtu.be/BweLi8P-O88
    
