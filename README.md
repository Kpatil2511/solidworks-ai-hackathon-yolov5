\# SolidWorks AI Hackathon – Object Detection using YOLOv5



\## 📌 Overview

This project was developed as part of the \*\*SolidWorks AI Hackathon\*\*.

The objective is to detect and count mechanical parts in images:

\- Bolt

\- Locating Pin

\- Nut

\- Washer



A YOLOv5-based object detection pipeline was implemented to generate predictions

for the test dataset, which were submitted as a CSV file for evaluation.



---



\## 🧠 Approach

\- Converted annotations into \*\*YOLO format\*\*

\- Organized dataset into training and validation splits

\- Trained a \*\*YOLOv5s\*\* model on the provided dataset

\- Evaluated performance using standard object detection metrics

\- Generated final predictions and converted detections into a submission CSV



---



\## 🗂️ Project Structure



solidworks-ai-hackathon-yolov5

│

├── notebooks

│ └── csv\_to\_yolo.ipynb

│

├── yolov5

│ ├── train.py

│ └── detect.py

│

├── dataset

│ └── data.yaml

│

├── results

│ ├── confusion\_matrix.png

│ ├── pr\_curve.png

│ ├── p\_curve.png

│ ├── r\_curve.png

│ └── results.png

│

└── submission

└── submission.csv





---



\## 📊 Training \& Evaluation

\- Model: YOLOv5s

\- Image size: 640×640

\- Batch size: 16

\- Epochs: 50

\- Optimizer and hyperparameters: YOLOv5 default

\- Metrics analyzed:

&nbsp; - Precision–Recall Curve

&nbsp; - F1 Curve

&nbsp; - Confusion Matrix



---



\## 🧪 Validation

\- Visual verification of bounding boxes

\- Count-based evaluation as per competition rules

\- Public leaderboard score: \*\*0.9978\*\*



---



\## 📦 Submission Format

CSV format: image-name, bolt, locating-pin, nut, washer





Each row contains the \*\*exact count of detected parts per image\*\*.



---



\## ⚠️ Notes

\- Training data and weights are excluded as per competition rules

\- Only inference scripts, notebooks, results, and submission files are included



---



\## 👤 Author

\*\*Kanhaiya Patil\*\*  

JSPM's Rajarshi Shahu College Of Engineering,Pune

B.Tech Computer Engineering  





