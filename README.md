# Rail Track Defect Detection

This project detects railway track defects using **YOLOv8** for object detection and **Streamlit** for web-based visualization.

## 🔧 Components

- `notebook_colab_training.ipynb`: Colab notebook used to train the YOLOv8 model.
- `best.pt`: Trained YOLOv8 weights for inference.
- `main.py`: Streamlit app for detecting and displaying defects.
- `images/`: Contains result/evaluation plots (e.g., precision-recall curves).

## 🧠 Model

- YOLOv8 trained on a custom railway track defect dataset.
- Evaluated using precision, recall, F1-score.

## 🚀 Running the App

```bash
streamlit run main.py
