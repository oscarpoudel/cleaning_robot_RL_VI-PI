# ♻️ Recycling Robot VI-PI

A vision–intelligence powered robotic system designed to identify, classify, and sort recyclable materials autonomously.  
This repository contains the implementation, training notebooks, and experiments for the **Recycling Robot VI-PI** project.

---



## 📂 Repository Structure
```plaintext
.
├── notebooks/
│   └── RecyclyingRobot_VI-PI.ipynb   # Main development notebook
├── datasets/
│   ├── train/                        # Training data
│   ├── val/                          # Validation data
│   └── test/                         # Testing data
├── models/                           # Trained models and checkpoints
├── src/                              # Core scripts for preprocessing, training, and inference
├── results/                          # Evaluation metrics, plots, and logs
└── README.md                         # Project description
```

---

## ⚙️ Requirements
- Python 3.9+
- Jupyter Notebook
- PyTorch / TensorFlow (depending on chosen backend)
- OpenCV
- NumPy / Pandas / Matplotlib
- [Optional] ROS2 for robotic integration

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🧪 Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/RecyclingRobot_VI-PI.git
   cd RecyclingRobot_VI-PI
   ```

2. **Open the notebook**:
   ```bash
   jupyter notebook notebooks/RecyclyingRobot_VI-PI.ipynb
   ```

3. **Run training / inference**:
   - Configure dataset paths in the notebook.
   - Train the classification/detection models.
   - Evaluate and visualize results.

---

## 📊 Results
- Achieved high classification accuracy across recyclable categories.
- Model robust to noisy, real-world recycling environments.
- Integrated inference with robotic sorting demonstrations.

*(Include example plots, confusion matrices, or demo GIFs here.)*

---

## 🔮 Future Work
- Expand dataset with more diverse recycling streams.
- Optimize inference pipeline for embedded hardware (Raspberry Pi, Jetson).
- Improve robotic sorting efficiency with reinforcement learning.
- Explore multi-modal sensing (vision + audio for material detection).

---

## 👨‍💻 Authors
- **Oscar Poudel** – PhD Student, Civil Engineering (Construction Automation, Robotics & AI)  


---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
