# 📦 Object Detection & Classification using YOLOv8

This project performs object detection and classification using YOLOv8 in Google Colab. It detects multiple objects in an image, generates analytics like class count and confidence scores, and outputs annotated images and CSV reports.

---

## 🧠 Features

- ✅ Multi-object detection using YOLOv8
- ✅ Annotated image output
- ✅ Object class-wise count
- ✅ Confidence score histogram
- ✅ CSV report generation

---

## 🖼️ Example Output

### 🔸 Annotated Image
![output](output.jpg)

### 🔸 Class Count Chart
![class counts](class_counts.png)

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `main.ipynb` | Full Colab notebook |
| `output.jpg` | Annotated result image |
| `detection_report.csv` | Object name & confidence |
| `class_counts.png` | Bar chart of object count |
| `confidence_hist.png` | Histogram of confidence scores |

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload the notebook or open `main.ipynb`
3. Install dependencies:

   ```bash
   pip install ultralytics pandas matplotlib seaborn pillow

