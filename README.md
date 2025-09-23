# Code

The link to the experimentation is available at:  
👉 [Experimentation Video](https://streamable.com/l3q21k)

---

# Model

The details about the models used and the prediction API operations are available in the following repository:  
👉 [QoS Prediction API V2](https://github.com/BorhaneddineHamadou/QoS_Pred_API_V2.git)

This repository builds on our previous work in **Automated Machine Learning (AutoML)** and provides:

- An automated pipeline for **feature engineering, model selection, and hyperparameter optimization**  
- **Reproducible QoS prediction models**, continuously adaptable to new datasets and deployment environments  
- Documentation and examples to facilitate **integration with orchestration frameworks** for latency-sensitive applications  

---

# Dataset

The dataset used for our analyses is the **WiFi subset** of the publicly available [Cell vs WiFi dataset](http://web.mit.edu/cell-vs-wifi/downloads.html).  

This dataset was originally collected by **S. Deng, R. Netravali, A. Sivaraman, and H. Balakrishnan** through the [Cell vs WiFi mobile application](https://web.mit.edu/cell-vs-wifi/), which records packet-level traces of a **1 MB TCP upload and a 1 MB TCP download** between a smartphone and a server over both WiFi and cellular networks.

We leverage this dataset to **predict network conditions**, particularly **latency**, a critical parameter for ensuring service quality.  

Key points:  
- The dataset contains **diverse network profiles** (latency, throughput, packet loss, etc.), representing different connectivity scenarios.  
- These profiles make it well-suited for **QoS management** in latency-sensitive services under fluctuating network conditions.  
- It also **aligns with our AutoML framework**, enabling models to be trained and optimized automatically for specific network conditions.  
