<h1 align="center">
  <br />
  THELMA PROJECT
  <br />

### Thelma: Threat Hunting Enhanced Language Models for Hunt Automation

<p align="justify">Despite advancements in cybersecurity tools and frameworks, threat hunting remains a largely manual and expert-driven process. Traditional systems rely heavily on indicators of compromise (IOCs), which are rigid and easily evaded by sophisticated attackers. 
While artificial intelligence and machine learning have been introduced to aid detection, these models often require large datasets, lack interpretability, and are not flexible enough to adapt to evolving threats. Moreover, existing automated threat hunting tools focus primarily on 
detection and analysis, but fail to address the "last-mile" tasks such as formulating threat hypotheses and crafting customized hunting queries tasks that still demand significant human expertise. The heterogeneous nature of computing environments, along with diverse data formats and query languages, 
further complicates the automation process. As a result, there is a critical need for a solution that can automate these final, labor-intensive steps of the threat hunting process while remaining adaptable, interpretable, and effective in complex environments.</p>
<p align="justify">Thelma (Threat-Hunting Enhanced Language Models for Hunt Automation) is an AI-powered agent framework designed to automate key steps in the threat hunting process (see Figure 1). It uses two large language models (LLMs): one to generate custom threat hunting queries from natural 
language descriptions (LLM A), and another to prioritize which systems to investigate based on current threat status (LLM B). By reading threat playbooks and adapting to different computing environments, Thelma can craft relevant queries and guide security analysts efficiently. 
This automation helps reduce manual effort, speeds up response time, and supports less experienced analysts in detecting complex cyber threats.</p>


<div align="center"><img width="468" height="139" alt="image" src="https://github.com/user-attachments/assets/c7a2267b-a1fa-4f83-a32e-de0b1d1f7284" /></div>

<p align="justify">Thelma showed promising results in automating threat hunting tasks. The first model, LLM A, which generates threat hunting queries, achieved high accuracy, producing correct results in 19 out of 26 cases (about 73% accuracy). It performed best when clear and 
detailed threat descriptions were provided. The second model, LLM B, which prioritizes endpoints for investigation, had low prediction accuracy (around 10%), but maintained a high recall rate (over 60%), meaning it was effective at minimizing missed threats. Overall, Thelma 
effectively automates query generation but needs further refinement in reasoning and environment-based decision-making.</p>
<p align="justify">Thelma demonstrates that large language models can automate key parts of the threat hunting process, especially generating accurate, context-aware queries from natural language. This reduces the manual workload on security analysts and speeds up response times. 
While query generation is effective, the system's reasoning model for prioritizing threats needs improvement. With more training data and richer contextual inputs, Thelma has strong potential to become a valuable tool for scalable, AI-driven cybersecurity operations.</p>

For a comprehensive understanding of Thelma’s design, performance, and evaluation methodology, readers are encouraged to refer to the full research paper published in IEEE.

Source : [Thelma: Threat Hunting Enhanced Language Models for Hunt Automation](https://ieeexplore-ieee-org.ntust.idm.oclc.org/abstract/document/10735642?casa_token=g2ogPvECGaYAAAAA:kSz8UHi1kDHdM7tLl8EvxgJ_H-cg6hqKpAr5PiDbgPvzJAfNSOJF23_GilBaKfvo9GUMNgWz5j8)

[Back to the Top](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/Thelma/README.md#thelma-threat-hunting-enhanced-language-models-for-hunt-automation) | [Back to the Project List](https://github.com/ntust-im-labyrinth/labyrinth/tree/GilvyThelmaProjectM/projects#----projects---colorbluelab-coloryellowy-oung--colororanger-estless-colorgreenin-colorredt-hreat-colororangeh-unting)
