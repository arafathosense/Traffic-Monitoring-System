# Traffic Monitoring System

An AI-powered Traffic Monitoring System designed to detect, analyze, and manage urban traffic using real-time computer vision and deep learning techniques.

Traffic congestion is a major issue in modern cities such as **China**, **Dhaka**, **New York City**, **Mumbai**,  and **Jakarta**. This system provides an intelligent solution to monitor vehicle movement, analyze traffic density, and support smarter urban planning decisions.


## 🚦 Project Overview

The Traffic Monitoring System uses **YOLOv8n**, a state-of-the-art deep learning model, to detect and classify:

* Cars
* Buses
* Trucks
* Motorcycles
* Bicycles
* Pedestrians
* Person

The system processes video streams in real time, detects objects, counts vehicles and pedestrians, and visualizes results directly on the screen.

<img width="1103" height="620" alt="image" src="https://github.com/user-attachments/assets/5b86a48b-f2d6-4f9d-bbfa-d7c975230b6d" />

## 🔍 Key Features

### 1. Real-Time Object Detection

* Accurate vehicle and pedestrian detection
* Bounding boxes with labels
* Smooth visual tracking

### 2. Custom Zone-Based Monitoring

* Define traffic zones (intersections, crossings, lanes)
* Count objects passing through selected areas
* Analyze area-specific traffic density

### 3. Traffic Analytics

* Vehicle counting
* Pedestrian counting
* Traffic flow estimation
* Processed video saving for later study

### 4. Smart City Integration

The system can be integrated with adaptive traffic signals and urban traffic control systems to improve traffic flow and safety.


## 🌍 Applications

### Urban Traffic Management

* Identify peak traffic hours
* Optimize signal timing
* Reduce congestion
* Improve road safety

### Accident Risk Assessment

* Detect high-density areas
* Monitor pedestrian-vehicle interaction
* Support preventive safety measures

### Environmental Impact Reduction

* Decrease fuel consumption
* Lower emissions
* Improve air quality through congestion control


## 🤖 Deployment Options

The system can run on standard computers or embedded platforms such as:

* **Raspberry Pi**
* **NVIDIA Jetson**

This enables flexible real-time deployment in various traffic environments.

## 🧠 Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### Step 2: Install Dependencies

```bash
pip install opencv-python
pip install numpy
pip install ultralytics
pip install matplotlib
pip install pillow
pip install tqdm
```

### Step 3: Run the Program

```bash
python main.py
```

The system will start processing the video and display real-time monitoring results.


## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Ultralytics YOLOv8
* Matplotlib
* Pillow
* tqdm

## 📌 Conclusion

The Traffic Monitoring System is a practical AI-driven solution for modern transportation challenges. By combining deep learning and real-time video analysis, it enables smarter traffic management, improved safety, and data-driven urban development.


## 📄 License

This project is developed for educational and research purposes. You are free to fork, modify, and extend it.

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Image Computing, Image Processing, Machine Learning, Deep Learning, Computer Vision**
