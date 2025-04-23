# Parking Space Detection
This project focuses on building an efficient and optimized model for detecting and counting parking spaces in the given image.
This project aims to detect and classify parking space availability using object detection techniques powered by YOLOv8. It utilizes the PKLot dataset and is designed for potential real-time application in smart parking systems.

## 📌 Project Overview

Managing parking space efficiently is a growing concern in urban environments. This project addresses that by using a deep learning-based computer vision approach to detect:

- Occupied parking spaces
- Vacant parking spaces

The system is trained on the PKLot dataset and evaluated for accuracy and speed, laying the groundwork for real-time deployment in smart city infrastructures.

## 🧠 Key Features

- YOLOv8-based object detection for parking occupancy
- Automated labeling and bounding box annotation
- Real-time detection capability (extendable)
- Performance analysis and optimization
- Implemented and tested

## 📂 Dataset

**[PKLot Dataset](https://web.inf.ufpr.br/vri/databases/parking-lot-database/)**  
- Contains over 12,000 labeled images from three different parking lots  
- Includes variations in weather, lighting, and camera angles  
- Each image is annotated with slot-wise labels (occupied / empty)

## 🛠️ Tech Stack

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Matplotlib, NumPy, Pandas

## 🧪 Project Workflow

1. **Data Preparation**
   - Download and organize PKLot dataset
   - Annotate and convert labels to YOLO format
2. **Model Training**
   - Configure YOLOv8 settings
   - Train on labeled dataset using Google Colab
3. **Evaluation**
   - Assess model performance (precision, recall, mAP)
   - Visualize predictions
4. **Analysis**
   - Detect and count vacant vs occupied slots
   - Explore optimization and real-time use cases

## 📊 Results

- High accuracy on varied conditions (day/night, rain/sun)
- Responsive bounding box predictions
- Room for extension into real-time CCTV-based parking management

## 🔍 Future Improvements

- Integrate real-time video feed for live detection
- Expand to multi-level parking environments
- Deploy as a web/mobile app for public use

## 📸 Sample Output

![image](https://github.com/user-attachments/assets/11119f30-a2fb-4602-9851-25710cf64e94)

Detected Parking Spaces:

space-empty: 25

space-occupied: 15

---

## 📄 License

**Copyright © 2025 Praveen Kumar**

All rights reserved.

This project and its associated files may not be copied, modified, distributed or used for any commercial purpose without explicit permission from the author.
Redistribution, modification, or commercial use of this code is strictly prohibited.
Permission to use this code for personal or academic research purposes is granted only with prior written consent from the author.


---

> Developed as part of a research initiative to explore deep learning solutions for smart city automation.

