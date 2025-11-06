# 🧠 Time-Series Anomaly Detection: A Decade Review (2024)

### 📚 Overview  
This repository contains the short-story assignment for **CMPE 255 – Data Mining (Fall 2025)**.  
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

## 🧩 Implementation Plan
Your final submission includes:
1. **📄 Medium Article** – A rewritten short story summarizing the survey, focusing on:
   - Method taxonomy  
   - Model architectures & evaluation metrics  
   - Visualization of key frameworks  
   - Your own insights and future perspectives  
   *(👉 Add your Medium link here)*  
2. **📊 Slides (on SlideShare)** – 8–12 slides highlighting motivation, taxonomy, SOTA methods, and open challenges.  
   *(👉 Add your SlideShare link here)*  
3. **🎥 Video Presentation (10–15 min)** – Recorded walkthrough of the slides.  
   *(👉 Add your video link here)*  

---

## 🧠 Suggested Structure for the Medium Article
1. **Introduction & Motivation**  
   - Why anomaly detection matters; applications in healthcare, industry, and IoT.  
2. **Evolution of Techniques (2014–2024)**  
   - From classical statistics to deep learning to foundation models.  
3. **Taxonomy of Methods**  
   - Reconstruction / Prediction / Hybrid / Graph-based / Streaming.  
4. **Datasets & Evaluation Metrics**  
   - Overview of benchmark datasets and evaluation measures.  
5. **Comparison of SOTA Models**  
   - Highlight top 3–5 frameworks with diagrams.  
6. **Challenges & Future Directions**  
   - Label scarcity, domain generalization, real-time adaptation.

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
