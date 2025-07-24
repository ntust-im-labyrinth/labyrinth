<h1 align="center">
  <br />
  Log Mamba
  <br />

  ### 🖥️ LogMamba: Self-Supervised Log Anomaly Detection for APT Hunting

<p align="justify">Infiltration of enterprise and government systems by Advanced Persistent Threats (APTs) often occurs through multi-stage, long-lived, and highly covert operations in real-world environments. Traditional detection methods based on Indicators of Compromise (IoCs) and rule-based approaches frequently fail to deliver timely alerts during the early stages of such attacks. As a result, threat hunting has gained traction in the field of information security for its ability to capture early signals of APT intrusions.
However, a comprehensive threat-hunting workflow must correlate and cross-validate massive volumes of logs and threat intelligence from diverse sources. This dramatically expands the search space and analytical complexity, degrading both efficiency and timeliness.
To overcome this bottleneck, we propose LogMamba: a self-supervised log anomaly detection and APT activity boundary extraction framework centered on Mamba (Selective State Space Model, SSM). Trained exclusively on logs representing normal behavior, LogMamba learns the distribution of long benign sequences. Through a dual-channel Delineation Algorithm that cross-validates alerts from different channels, it automatically extracts the time windows that truly require threat hunting.
This approach sharply narrows the analysis scope, reduces storage and investigation costs, and simultaneously preserves high coverage of APT activities. </p>
<p align="justify"> 
For data preprocessing, LogMamba uses the Drain parser to map raw system logs into fixed templates, which are then serialized into log template keys. This allows the downstream sequence model to effectively learn patterns in normal behavior.</p>

<p align="justify"> The core model, Mamba Anomaly Detection, is trained in a self-supervised manner using only normal logs. Leveraging Mamba’s linear prediction complexity, the model analyzes a fixed-length window of logs to estimate the conditional distribution of the next log template key. If an event falls outside the Top-K predicted keys, it is flagged as anomalous.</p>

<p align="justify"> To define APT activity boundaries, LogMamba applies a Delineation Algorithm. It also introduces two extension parameters to support different use cases: </p>

- α for real-time threat hunting

- β for post-incident digital forensics

<p align="justify">These parameters allow users to control the trade-off between detection coverage and log reduction.</p>

<p align="justify">By adopting the Mamba architecture, LogMamba avoids the gradient explosion/vanishing problems common in RNNs and the high memory and time complexity of Transformer-based models enabling efficient, real-time inference on a single GPU.</p>

<p align="justify">
Experiments across multiple APT attack datasets validate the practical effectiveness of LogMamba. In most scenarios, it achieves high coverage of APT activities while retaining only about 30% of the logs using lightweight extension parameters making it well-suited for real-time threat hunting.</p>

<p align="justify">Two parameter sets are introduced to support different use cases:</p>

- Real-time threat hunting

- Post-incident digital forensics

<p align="justify">Across datasets of varying scales, the extension magnitudes required to reach full APT coverage and the corresponding log retention ratios are systematically quantified. This highlights the trade-off between coverage and log storage/analysis cost.</p>

<p align="justify">Even without labeled anomalies, LogMamba by combining Mamba’s efficient long-sequence modeling with boundary extraction—successfully identifies key time intervals aligned with APT kill chains in a wide range of attack scenarios.</p>


[Back to the Top] | [Back to the Project List](https://github.com/ntust-im-labyrinth/labyrinth/tree/GilvyThelmaProjectM/projects#----projects---colorbluelab-coloryellowy-oung--colororanger-estless-colorgreenin-colorredt-hreat-colororangeh-unting)
