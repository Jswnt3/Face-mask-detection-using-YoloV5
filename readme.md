<h1 align="center">😷 𝗙𝗮𝗰𝗲 𝗠𝗮𝘀𝗸 𝗗𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻 𝘂𝘀𝗶𝗻𝗴 𝗬𝗢𝗟𝗢𝘃𝟱</h1>
<p align="center"><i>Real-Time AI-Powered Mask Compliance System</i></p>


## 📌 Project Overview
During the COVID-19 pandemic, ensuring mask compliance in public places became critical, yet manual monitoring is inefficient and unsafe. This project presents a **deep learning–based real-time face mask detection system** using **YOLOv5**, capable of accurately identifying whether individuals are wearing masks, not wearing masks, or wearing them incorrectly from images and live video streams.



## 🎯 Problem Statement
In crowded public environments, it is difficult for authorities to manually monitor mask usage. This increases the risk of virus transmission and endangers both the public and enforcement personnel.



## ✅ Objectives
- Detect faces in real time and classify them as **With Mask**, **Without Mask**, or **Incorrect Mask**
- Achieve high detection accuracy with low latency
- Minimize human involvement in compliance monitoring
- Provide a scalable and deployable AI-based solution



## 🏗️ System Architecture

```
Input Sources
├── Image Files
├── Video Files
└── Live Camera Feed
    │
    ▼
Image Capture & Preprocessing
├── Frame Extraction
├── Image Resizing
└── Normalization
    │
    ▼
YOLOv5 Deep Learning Model
├── Feature Extraction
├── Object Detection
└── Confidence Scoring
    │
    ▼
Face Detection & Mask Classification
├── With Mask
├── Without Mask
└── Incorrect Mask
    │
    ▼
Bounding Box Generation
├── Face Localization
└── Label Rendering
    │
    ▼
Detection Logs
└── SQL Database
    ├── Timestamp
    ├── Detection Class
    └── Source ID
```

## 🧠 Technology Stack
- **Programming Language:** Python, HTML5, CSS3, JavaScript
- **Deep Learning Framework:** PyTorch
- **Model:** YOLOv5 (One-stage Object Detector)
- **Libraries:** OpenCV, NumPy, Pandas
- **Database:** SQL (for structured detection logs)
- **Tools:** Git, GitHub, Visual Studio Code



## ❓ Why YOLOv5 and Not Other Models?

### Why YOLOv5?
YOLOv5 was chosen because it offers an optimal balance between **real-time inference speed** and **high detection accuracy**, making it well-suited for live face mask detection in public environments.

### Why not other models?
- **Faster R-CNN:** Provides high accuracy but is computationally expensive and unsuitable for real-time detection  
- **SSD:** Faster than R-CNN but less accurate when detecting small objects such as faces  
- **YOLOv3 / YOLOv4:** Older architectures with slower inference and fewer optimizations  
- **Traditional CNN classifiers:** Require separate face detection and classification stages, increasing system latency  

### Key Advantages of YOLOv5
- Single-stage, end-to-end object detection  
- Fast inference suitable for real-time video streams  
- Strong performance on small objects  
- Easy deployment with active community support  




## ⚙️ Key Features
- Real-time face mask detection
- Supports images, videos, and live camera streams
- Handles different mask types and lighting conditions
- Accurate detection in single-person and crowd scenarios
- Modular and scalable system design



## 🚀 Installation & Execution

git clone https://github.com/Jswnt3/Face-mask-detection-using-YoloV5.git  
cd Face-mask-detection-using-YOLOv5  
pip install -r requirements.txt  
python detect.py  



## 📊 Results & Performance
- High precision and recall achieved at optimal training epochs
- Reliable detection in real-world scenarios
- Suitable for deployment in public surveillance systems

*(Precision, Recall, and mAP analysis included in project report)*



## 🔮 Future Enhancements
- Improve accuracy using larger and more diverse datasets
- Deploy as a web or mobile application
- Integrate alert and notification systems
- Cloud deployment for large-scale monitoring
- Edge-device optimization (Raspberry Pi, CCTV systems)


## ⚖️ Ethical Considerations
- Ensures privacy by avoiding identity recognition
- Designed for public safety, not surveillance misuse
- Can be configured to comply with regional privacy regulations



## 👨‍💻 Author
**Jaswanth Mudapaka**  
B.Tech – Computer Science & Engineering  
LinkedIn - https://www.linkedin.com/in/jaswanth-mudapaka/



⭐ If you find this project useful, please consider giving it a star.
