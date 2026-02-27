<h1 align="center">🚗 Vehicle & 🚶 Pedestrian Detection</h1>
<h3 align="center">Real-Time Object Detection using OpenCV Haar Cascades</h3>

<hr/>

<h2>🚀 Project Overview</h2>
<p>
This project implements real-time vehicle and pedestrian detection 
using Haar Cascade classifiers with OpenCV.
</p>

<p>
The system processes video streams or webcam input to detect:
</p>

<ul>
<li>🚗 Cars</li>
<li>🚶 Pedestrians (Full Body Detection)</li>
</ul>

<hr/>

<h2>🧠 Detection Method</h2>

<ul>
<li>Haar Cascade Classifiers</li>
<li>Grayscale frame conversion</li>
<li>Multi-scale object detection</li>
<li>Bounding box visualization</li>
</ul>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
vehicle-and-pedestrian-detection-opencv/
│
├── carDetection.py
├── walkDetection.py
├── haarcascade_car.xml
├── haarcascade_fullbody.xml
├── cars.avi
├── walking.avi
├── README.md
└── requirements.txt
</pre>

<hr/>

<h2>⚙️ How to Run</h2>

<h3>1️⃣ Install Requirements</h3>

<pre>
pip install -r requirements.txt
</pre>

<h3>2️⃣ Run Car Detection</h3>

<pre>
python carDetection.py
</pre>

<h3>3️⃣ Run Pedestrian Detection</h3>

<pre>
python walkDetection.py
</pre>

<hr/>

<h2>🛠 Requirements</h2>

<pre>
opencv-contrib-python
numpy
</pre>

<hr/>

<h2>💡 Engineering Highlights</h2>

<ul>
<li>Real-time video processing</li>
<li>Classical Computer Vision techniques</li>
<li>Object detection with Haar Cascades</li>
<li>Practical use cases in surveillance systems</li>
</ul>

<hr/>

<h2>🔮 Future Improvements</h2>

<ul>
<li>Upgrade to YOLO or SSD for deep learning-based detection</li>
<li>Add FPS counter</li>
<li>Save processed video output</li>
<li>Add confidence threshold tuning</li>
</ul>

<hr/>

<div align="center">
<h3>👨‍💻 Developed by Mostafa Sharqawy</h3>
<p>AI Engineer | Computer Vision | Deep Learning</p>
</div>
