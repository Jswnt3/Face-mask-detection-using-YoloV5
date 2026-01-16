# Face Mask Detection Using YOLOv5 😷

## 📌 Project Overview
During the COVID-19 pandemic, ensuring mask compliance in public places became critical, yet manual monitoring is inefficient and unsafe. This project presents a **deep learning–based real-time face mask detection system** using **YOLOv5**, capable of accurately identifying whether individuals are wearing masks, not wearing masks, or wearing them incorrectly from images and live video streams.

---

## 🎯 Problem Statement
In crowded public environments, it is difficult for authorities to manually monitor mask usage. This increases the risk of virus transmission and endangers both the public and enforcement personnel.

---

## ✅ Objectives
- Detect faces in real time and classify them as **With Mask**, **Without Mask**, or **Incorrect Mask**
- Achieve high detection accuracy with low latency
- Minimize human involvement in compliance monitoring
- Provide a scalable and deployable AI-based solution

---

## 🏗️ System Architecture
Input (Image / Video / Camera)
        -
        v
Image Capture & Preprocessing
        -
        v
YOLOv5 Deep Learning Model
        -
        v
Face Detection + Mask Classification
        -
        v
Bounding Boxes with Labels
        -
        v
Detection Logs stored in SQL Database

---

## 🧠 Technology Stack
- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Model:** YOLOv5 (One-stage Object Detector)
- **Libraries:** OpenCV, NumPy, Pandas
- **Database:** SQL (for structured detection logs)
- **Tools:** Git, GitHub, Visual Studio Code

---

## ❓ Why YOLOv5?
- Real-time object detection capability
- High accuracy with optimized inference speed
- Single-stage detection makes it suitable for live video feeds
- Efficient handling of multiple faces in crowded scenes

---

## ❓ Why SQL Instead of NoSQL?
SQL was chosen because:
- Detection results follow a **structured schema** (timestamp, class label, camera ID)
- Strong **data consistency and integrity** are required
- Enables easy querying for reports, audits, and analytics
- Suitable for compliance tracking and historical analysis

---

## ⚙️ Key Features
- Real-time face mask detection
- Supports images, videos, and live camera streams
- Handles different mask types and lighting conditions
- Accurate detection in single-person and crowd scenarios
- Modular and scalable system design

---

## 🚀 Installation & Execution

git clone [https://github.com/Jswnt3/Face-mask-detection-using-YoloV5.git]  
cd Face-mask-detection-using-YOLOv5  
pip install -r requirements.txt  
python detect.py  

---

## 📊 Results & Performance
- High precision and recall achieved at optimal training epochs
- Reliable detection in real-world scenarios
- Suitable for deployment in public surveillance systems

*(Precision, Recall, and mAP analysis included in project report)*

---

## 🔮 Future Enhancements
- Improve accuracy using larger and more diverse datasets
- Deploy as a web or mobile application
- Integrate alert and notification systems
- Cloud deployment for large-scale monitoring
- Edge-device optimization (Raspberry Pi, CCTV systems)

---

## ⚖️ Ethical Considerations
- Ensures privacy by avoiding identity recognition
- Designed for public safety, not surveillance misuse
- Can be configured to comply with regional privacy regulations

---

## 🤝 Contribution
Contributions are welcome.  
Fork the repository and submit a pull request for enhancements or fixes.

---

## 👨‍💻 Author
**Jaswanth Mudapaka**  
B.Tech – Computer Science & Engineering

---

⭐ If you find this project useful, please consider giving it a star.
