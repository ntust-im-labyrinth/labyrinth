<h1 align="center">
  <br />
  LABYRINTH Projects and Activities
</h1>


<p align="justify"> The LABYRINTH project showcases the innovative research and initiatives led by our lab in the field of cybersecurity and artificial intelligence. Our work focuses on cutting-edge areas such as: </p>

- **Generative AI for Cyber Threat Hunting**  
- **AI-Augmented Security Operations**  
- **Automated Hunt Analytics**  
- **Curriculum Design for Cybersecurity Education**

<p align="justify"> In addition to research and development, we actively engage in sharing our findings with the wider community through conference presentations, academic publications, and other professional events.
This platform highlights the contributions of our professors and lab members while promoting visibility and collaboration across the cybersecurity and AI landscape. </p>


# Table of Contents

1. [Thelma : An Agent Framework for Threat Hunting Automation](https://github.com/ntust-im-labyrinth/labyrinth/tree/GilvyThelmaProjectM/projects#thelma--an-agent-framework-for-threat-hunting-automation)

3. [Investigating the Role of ChatGPT in Cybersecurity Education](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/README.md#investigating-the-role-of-chatgpt-in-cybersecurity-education)
   
4. [Beyond Technical Training: A Cybersecurity Skills Framework for Non-Professionals](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/README.md#beyond-technical-training-a-cybersecurity-skills-framework-for-non-professionals)

   
# Thelma : An Agent Framework for Threat Hunting Automation
[Back to the Top](#table-of-contents)

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


# Investigating the Role of ChatGPT in Cybersecurity Education
[Back to the Top](#table-of-contents)
<p align="justify"> Muhammad Gilvy Langgawan Putra, a PhD student in Information Management at the National Taiwan University of Science and Technology (NTUST) and a member of the Labyrinth Lab, recently presented at The European Conference on Education (ECE) 2024, 
  held in London, United Kingdom.</p>
<div align="center"><img width="468" height="263" alt="image" src="https://github.com/user-attachments/assets/9ce46198-2eae-4e64-9613-394d76d88958" /></div>

<p align="justify">This year’s conference brought together 672 delegates from 84 countries, fostering a rich interdisciplinary exchange over two days of plenary sessions. The event was hosted across prestigious institutions including University College London (UCL), the University of Sussex, and 
SOAS University of London, and organized in partnership with UCL, Birkbeck (University of London), the European Center for Peace and Development (ECPD) of the United Nations University for Peace (UPEACE), and the IAFOR Research Center at Osaka University.</p>

**Presented Study:**
"Exploring Lacunae in ChatGPT-Facilitated Cybersecurity Education: An Investigation into Knowledge Discrepancies and Learning Challenges"


<p align="justify"> In his presentation, Mr. Langgawan Putra shared findings from an innovative study that explored the use of AI-driven chatbots specifically ChatGPT in the context of cybersecurity education, with a focus on the highly specialized domain of threat hunting.
Given the sensitive and technical nature of threat hunting, the study questioned whether AI systems like ChatGPT could provide meaningful assistance in such areas. To investigate this, an experiment was conducted with 35 students who had recently completed a 
cybersecurity course without the aid of ChatGPT. These students were then tasked with evaluating ChatGPT’s responses to 38 domain-specific questions, along with three additional reflective questions.</p>

Key Findings:
- 57.8% of students believed that ChatGPT’s responses aligned well with their existing knowledge.
- 20.6% reported gaining new insights through the interaction with ChatGPT.
- 12.1% found the responses inadequate, and
- 9.6% considered them irrelevant.

<p align="justify">When asked about the advantages and limitations of using ChatGPT, students highlighted its broad knowledge base as a key strength, while its lack of access to real-time or sensitive data was cited as a major drawback.
A particularly insightful part of the study addressed whether access to ChatGPT would diminish the necessity of attending class. The consensus among students was clear: attendance remained essential. They emphasized the importance 
of learning how to use threat-hunting tools effectively skills that are best taught by instructors in a hands-on environment. Furthermore, students recognized that understanding how to formulate precise queries for ChatGPT is a skill in itself, requiring guided instruction.</p>




# Beyond Technical Training: A Cybersecurity Skills Framework for Non-Professionals 
[Back to the Top](#table-of-contents)
