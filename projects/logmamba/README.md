<h1 align="center">
  <br />
  Log Mamba
  <br />

  ### 🖥️ LogMamba: Scalable Self-Supervised Log Anomaly Detection for Threat Hunting

<p align="justify">LogMamba is a lightweight yet powerful framework for detecting anomalies in system logs—specifically designed to uncover stealthy, long-lived intrusions like Advanced Persistent Threats (APTs). By leveraging the efficient and scalable Mamba (Selective State Space Model), LogMamba enables self-supervised anomaly detection without requiring labeled attack data, making it ideal for real-world security operations where early signals are subtle and ground truth is unavailable. </p>
<p align="justify"> 
In traditional security monitoring pipelines, detection often relies on static signatures or rule-based logic, which can miss the early phases of sophisticated attacks. LogMamba takes a different approach: trained solely on benign system behavior, it learns to model the expected patterns of log sequences. When real-world logs deviate from these patterns, the system flags them as anomalous. More importantly, it applies a Dual-Channel Delineation Algorithm to isolate suspicious time windows, significantly narrowing the scope of threat hunting and forensic analysis.</p>

 #### 🚀 What Makes LogMamba Unique?
<p align="justify"> 
⚡ Fast and scalable: Runs real-time on a single GPU</p>
<p align="justify"> 
⚙️ Self-supervised: Trained only on benign logs, no labels required</p>
<p align="justify"> 📏 APT boundary extraction: Automatically narrows search windows</p>
<p align="justify"> 
⚙️ Adjustable parameters for balancing detection and log reduction</p></p>

#### 🧠 How It Works
1. Log Parsing: Raw logs are preprocessed using the Drain parser to map messages to structured templates, which are then tokenized into log keys.
2. Anomaly Detection: A self-supervised Mamba model learns to predict the next log key in a fixed-size window. Events falling outside the Top-K predictions are flagged as anomalous.
3. Boundary Extraction: A dual-channel algorithm evaluates and cross-validates anomaly scores to delineate segments likely to correspond to APT behavior.

<p align="justify"> LogMamba offers an efficient and scalable solution for detecting stealthy APT activity through self-supervised log anomaly detection and boundary extraction. By leveraging the Mamba architecture, it achieves high detection coverage with minimal log retention, making it ideal for both real-time threat hunting and post-incident analysis.</p>

#### 📢 Coming Soon
<p align="justify"> 📄 A detailed research publication with methodology, experiments, and benchmarks will be released soon.</p>

[Back to the Top](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/logmamba/README.md#%EF%B8%8F-logmamba-self-supervised-log-anomaly-detection-for-apt-hunting) | [Back to the Project List](https://github.com/ntust-im-labyrinth/labyrinth/tree/GilvyThelmaProjectM/projects#----projects---colorbluelab-coloryellowy-oung--colororanger-estless-colorgreenin-colorredt-hreat-colororangeh-unting)
