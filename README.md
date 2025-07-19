# Animal-detection-using-YOLO
Real-time object detection using YOLOv5/YOLOv8 on Open Images Dataset (OIDv6)

This project implements real-time object detection using **YOLOv5** and **YOLOv8** models on the [Open Images Dataset v6 (OIDv6)](https://storage.googleapis.com/openimages/web/index.html). The goal was to detect 5 animal classes: **Cat, Dog, Fish, Tiger, and Lion**.

##  Highlights

- Used **Ultralytics YOLOv5 & YOLOv8**
- Trained on annotated subset of **OIDv6**
- Achieved high precision:
  - 🐶 Dog: 0.92
  - 🐱 Cat: 0.90
  - 🐯 Tiger: 0.94
- Applied data augmentation & hyperparameter tuning
- Addressed underwater imagery and occlusion in fish class

##  Files

- `main.ipynb`: Full training + evaluation notebook
- `Report.pdf`: Detailed report with results and analysis

##  Tech Stack

- Python, PyTorch, YOLOv5, YOLOv8
- OpenCV, Pandas, NumPy, Matplotlib
- Google Colab / Jupyter

## 🚀 How to Run

```bash
# Clone repo
git clone https://github.com/AayushThakar/Animal-detection-using-YOLO.git

# Open notebook
Open main.ipynb in Jupyter or Google Colab
