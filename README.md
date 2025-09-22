#Code

The link of the experimentation is available at:

https://streamable.com/l3q21k

#Model

The details about the models used and the prediction API operations are available in the following repository:

https://github.com/BorhaneddineHamadou/QoS_Pred_API_V2.git

It regroups our previous works result on Automated Machine Learning, which provide an automated pipeline for feature engineering, model selection, and hyperparameter optimization. This ensures that the QoS prediction models are not only reproducible but also continuously adaptable to new datasets and deployment environments. The repository also includes documentation and examples to facilitate integration with orchestration frameworks for latency-sensitive applications.

#Dataset

The dataset we used for our analyses is the WiFi subset of the publicly available Cell vs WiFi dataset (http://web.mit.edu/cell-vs-wifi/downloads.html). This dataset was originally collected by S. Deng, R. Netravali, A. Sivaraman, H. Balakrishnan. through their Cell vs WiFi mobile application (https://web.mit.edu/cell-vs-wifi/), which records packet-level traces of a 1 MB TCP upload and a 1 MB TCP download between a smartphone and a server over both WiFi and cellular networks.

We leverage this dataset to predict network conditions, particularly latency, which is a critical parameter for ensuring service quality. The dataset contains a variety of network profiles that capture different connectivity scenarios and network metrics (latency, throughput, packet loss, etc.) , making it especially suitable for our approach to QoS management for latency-sensitive services in environments with fluctuating network conditions. It also aligns with our AutoML framework by providing diverse profiles that can be exploited to train models adapted to specific network conditions through an automated model training and hyperparameter optimization process.
