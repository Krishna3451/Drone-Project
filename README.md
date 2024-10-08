# Brain Tumor Detection with YOLOv8n

## Project Summary
This project is designed to detect brain tumors from MRI images using the YOLOv8n (You Only Look Once) object detection model. The goal is to offer a quick and accurate tool for identifying tumors in MRI scans, supporting early diagnosis and potential treatment decisions. Trained on a dataset of 19,000 images, the model performs with high precision and accuracy. A user-friendly interface enables users to upload images and detect tumors in real time.

---

## 🎥 Project Demo
Explore the full project video for a demonstration of its functionalities. [Here](URL)


---

## Motivation
This project is part of an innovative assignment for the Drone Lab at Scaler School of Technology, focusing on applying technology to real-world problems. Detecting brain tumors is a critical task due to the life-threatening implications if not identified early. Manual analysis of MRI images is time-intensive and subject to human error, so this project leverages deep learning to aid radiologists with faster, more accurate diagnoses.

---

## Data Source
The dataset for this project, sourced from Kaggle, consists of 19,000 MRI brain images annotated for tumor detection.

- **Image Format:** JPEG
- **Annotations:** Provided in YOLO format (bounding boxes for tumor regions)
- **Dataset Split:**
  - **Training Set:** Used to train the model.
  - **Validation Set:** For model fine-tuning during training.
  - **Test Set:** For evaluating final performance metrics.

---

## Environment Setup

1. **Python Installation**
   - This project uses Python 3.x. Ensure that Python is installed.

2. **Required Libraries**
   - Install necessary libraries for data management, model training, and UI creation:
     ```bash
     pip install ultralytics opencv-python matplotlib pandas ipywidgets notebook
     ```
     - **Ultralytics:** For YOLOv8 model training and inference.
     - **OpenCV:** For image processing and displaying results.
     - **Matplotlib:** For plotting graphs and visualizations.
     - **Pandas:** For data structuring.
     - **Ipywidgets:** For interactive file upload widgets.

3. **Setting Up Jupyter Notebook**
   - Jupyter Notebook was used for model training and visualization.
     ```bash
     pip install notebook
     ```

---

## Model Training and Performance

### Model Choice: YOLOv8n
YOLOv8n was chosen for its balance of speed and accuracy, ideal for real-time tumor detection in MRI images.

### Training Process
The model was trained on 19,000 MRI images, optimized for high performance.

### Evaluation Metrics
After training, the model’s accuracy was evaluated using several metrics:

| Metric     | Value  |
|------------|--------|
| Accuracy   | 0.839  |
| Precision  | 1.000  |
| Recall     | 0.839  |
| F1 Score   | 0.913  |


