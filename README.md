# Vehicle-Detection-Counting-Yolo11

## 📌 Project Overview
This project implements a vehicle detection and counting system using YOLOv11 object detection and tracking. The system processes video footage, detects vehicles (cars, buses, trucks, motorcycles, bicycles, and trains), tracks them across frames, and counts the number of vehicles crossing a predefined virtual line.

## 📌 Demo
![](https://github.com/Anas436/Vehicle-Detection-Counting-Yolo11/blob/main/output/output1.png)

<hr>

![](https://github.com/Anas436/Vehicle-Detection-Counting-Yolo11/blob/main/output/output2.png)

<hr>

![](https://github.com/Anas436/Vehicle-Detection-Counting-Yolo11/blob/main/output/Output3.png)

<hr>

![](https://github.com/Anas436/Vehicle-Detection-Counting-Yolo11/blob/main/output/Output4.png)

## 🛠️ Features
- **Real-time vehicle detection** using YOLOv11 model
- **Multi-object tracking** with persistent ID assignment
- **Vehicle counting** across a virtual detection line
- **Class-specific counting** (separate counts for cars, buses, trucks, etc.)
- **Visualization** of bounding boxes, tracking IDs, and vehicle counts
- **Output video generation** with detection overlay

## 🏗️ Architecture
1. **Mount Google Drive** for data storage and retrieval
2. **Install Ultralytics YOLO** framework
3. **Load YOLOv11 pre-trained model**
4. **Process video frames** for detection and tracking
5. **Count vehicles** crossing a predefined virtual line
6. **Generate output video** with visual annotations

## 📁 Project Structure
```
VEHICLE-DETECTION-COUNTING-YOL011/
│
├── input/                     # Directory for input data (e.g., images, videos)
├── output/                    # Directory for output results (e.g., processed videos, counts)
├── .gitignore                 # Git ignore file
├── LICENSE                    # License file for the project
├── README.md                  # Project documentation
└── VehicleDetectionCounting.ipynb  # Jupyter Notebook for the project
```

## 🔧 Dependencies
- `ultralytics` (YOLOv11)
- `opencv-python`
- `google-colab` patches
- `collections`, `time`

## 🚀 Usage
1. Mount Google Drive to access video data
2. Install required dependencies
3. Load the YOLOv11 model
4. Set up video capture and output paths
5. Process video frames with vehicle detection and tracking
6. Generate counted vehicles output video

## 📈 Output
- Real-time display of detected vehicles with tracking IDs
- Class-wise vehicle counts displayed on video frames
- Final counted vehicles saved to `output folder`

## 🎯 Applications
- Traffic monitoring and analysis
- Vehicle counting for traffic flow studies
- Parking lot occupancy monitoring
- Highway traffic analytics
- Smart city infrastructure planning

## ⚙️ Configuration
- Virtual detection line coordinates can be adjusted
- Confidence thresholds customizable via YOLO parameters
- Specific vehicle classes filterable for counting
- Output visualization customizable (colors, text, line position)

## 📝 Notes
- Project designed for Google Colab with GPU acceleration
- Requires pre-trained YOLOv11 model (`yolo11l.pt`)
- Output video saved to Google Drive for easy access
- System tracks vehicles persistently across frames to avoid double counting

---

