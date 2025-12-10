# 🧠 Time-Series Anomaly Detection: A Decade Review (2024)

## 📚 Overview  
The topic is based on the 2024 arXiv survey paper:  
**“Dive into Time-Series Anomaly Detection: A Decade Review.”**  
This paper systematically reviews anomaly detection techniques for time-series data, covering classical statistical approaches to modern deep learning and foundation models.

---

## 🧭 Motivation  
Anomaly detection in time-series data is critical in many real-world applications, such as:
- 🏥 **Healthcare** – detecting abnormal heart rates or EEG signals  
- 🏭 **Industrial Monitoring** – identifying sensor or machine faults  
- 💳 **Finance** – detecting fraud in transaction streams  

With the rise of deep learning and large-scale foundation models, new architectures like **Transformers**, **Autoencoders**, and **Graph Neural Networks** have become dominant in the last decade.

---

## 🔍 Key Contributions (from the 2024 Survey)
The paper organizes research progress from 2014 to 2024 into a unified taxonomy:

| Category | Description |
|-----------|-------------|
| **Reconstruction-based methods** | Use Autoencoders or VAEs to reconstruct normal signals and detect anomalies based on reconstruction errors. |
| **Prediction-based methods** | Forecast next values (RNN, LSTM, Transformer) and flag large deviations. |
| **Hybrid methods** | Combine reconstruction and prediction to improve robustness. |
| **Graph-based / Multivariate models** | Capture dependencies across correlated sensor signals. |
| **Online and Streaming detection** | Real-time detection for dynamic environments. |

**Evaluation Metrics:** Precision, Recall, F1, ROC-AUC, PR-AUC  
**Common Datasets:** Yahoo, KPI, NASA, UCR, NAB, SWaT  

---

## 🧩 Link
1. 📄 [Medium Article](https://medium.com/@s9070292108/dive-into-time-series-anomaly-detection-a-friendly-guide-757b9cc58cf7?postPublishedType=initial)
2. 📊 [Slides](https://docs.google.com/presentation/d/1RURt9BK_-6hakFmFSqW7MPvqX-vPicFTh9VBf3NXRYc/edit?slide=id.g3af2a87c816_0_6#slide=id.g3af2a87c816_0_6)

---

## 📎 References
1. [**Dive into Time-Series Anomaly Detection: A Decade Review (2024)**](https://arxiv.org/pdf/2412.20512)  
2. [**Online Model-based Multivariate Time-Series Anomaly Detection: Taxonomy, Survey, Research Challenges, and Future Directions (2024)**](https://arxiv.org/pdf/2408.03747)  
3. Benchmark datasets and repositories: Yahoo, NAB, SWaT, UCR Archive.

---

## 🧑‍💻 Author
**Yu Hsuan Lee**  
M.S. in Software Engineering, San José State University  
Course: CMPE 255 – Data Mining (Prof. Vijay Eranti)  
Semester: Fall 2025  
