# 🚀 Workplace Activity Recognition System

## 📌 Project Overview

This project aims to **maximize real-time productivity insights** in the workplace while ensuring **minimal privacy intrusion**. Using **YOLOv8**, the system detects and analyzes workplace activities to improve employee efficiency and optimize operational costs.

## 🎯 Business Problem & Objectives

### 🔴 **Business Problem**
Employee productivity in the workplace is currently below desired levels, impacting overall efficiency and performance.

### 🏆 **Business Objective**
- Maximize real-time productivity insights.

### 🔐 **Business Constraints**
- Minimize privacy intrusion while analyzing activities.

## ✅ Success Criteria

### 📊 **Business Success Criteria**
- Achieve an **employee satisfaction score of at least 85%**.

### 🤖 **Machine Learning Success Criteria**
- Achieve an **accuracy of at least 90%**.

### 💰 **Economic Success Criteria**
- Maximize office employee base to **50%**.
- Minimize operational costs to **less than 20%**.

## 📂 Project Structure

```
📂 workplace-activity-recognition/
 ├── 📂 models/            # Trained models (best.pt, last.pt)
 ├── 📂 configs/           # Config files (args.yaml, data.yaml)
 ├── 📂 results/           # Evaluation metrics and images
 ├── 📂 dataset/           # Dataset images and labels
 ├── 📂 docs/              # Project certificate and documentation
 ├── app.py               # Main application script
 ├── yolov8s.ipynb        # Jupyter Notebook for analysis
 ├── yolov8s.py           # Core script for running YOLOv8
 ├── yolov8s_streamlit.py # Streamlit-based UI (if applicable)
 ├── requirements.txt      # Dependencies
 ├── README.md             # Documentation
```

## 🖼️ Project Certificate

![Project Certificate](docs/Project_Certificate.jpg)

## 🔍 Dataset

The dataset includes labeled images used for training and evaluation. It contains:

- **Training batches** (`train_batch0.jpg`, `train_batch1.jpg`...)
- **Validation labels** (`val_batch0_labels.jpg`, etc.)
- **Labels correlation analysis** (`labels_correlogram.jpg`)

## 🛠️ Tech Stack

- **Python** (OpenCV, NumPy, Pandas, PyTorch, Ultralytics YOLOv8)
- **Streamlit** (for Web UI, if applicable)
- **Matplotlib & Seaborn** (for visualization)
- **Jupyter Notebook / VS Code** (development environment)

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kapperasrisailam2001/Workplace-Activity-Recognition.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd Workplace-Activity-Recognition
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the YOLOv8 model:**
   ```bash
   python yolov8s.py
   ```
5. **(Optional) Run the Streamlit app:**
   ```bash
   streamlit run yolov8s_streamlit.py
   ```

## 📊 Results & Insights

- **Confusion Matrix** (`confusion_matrix.png`)
- **Precision-Recall Curves** (`PR_curve.png`, `P_curve.png`, `R_curve.png`)
- **F1 Score Curve** (`F1_curve.png`)
- **Final Results CSV** (`results.csv`)

## 🤝 Contributing

We welcome contributions! Feel free to fork the repo, submit issues, or create pull requests.

## 📄 License

This project is licensed under the **MIT License**.

## 📬 Contact

For any queries or collaborations, reach out via:
- **GitHub:** [kapperasrisailam2001](https://github.com/kapperasrisailam2001)
- **LinkedIn:** [Kappera Srisailam](https://www.linkedin.com/in/kapperasrisailam/)

---

🌟 **If you find this project helpful, don't forget to give it a star! ⭐**

