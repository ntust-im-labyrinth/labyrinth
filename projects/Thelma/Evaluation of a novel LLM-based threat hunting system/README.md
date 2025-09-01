<h1 align="center">
  <br />
  Design, Implementation, and Evaluation of a Novel LLM-based Threat Hunting System
  <br />

  ### 

<p align="justify"> The rise of Advanced Persistent Threats (APTs) continues to challenge defenders in modern enterprise environments. As organizations expand their digital ecosystems, their infrastructures become more interconnected, exposing larger attack surfaces and creating opportunities for sophisticated adversaries. Unlike traditional intrusions, APTs leverage techniques such as social engineering, zero-day exploitation, and stealthy lateral movement methods that are designed to bypass legacy security controls like firewalls and intrusion detection systems (IDS). Their lack of clear Indicators of Compromise (IoCs) enables attackers to persist undetected, often until significant damage has already occurred. </p>

<p align="justify"> To counter this, the security community has shifted toward threat hunting—a proactive discipline focused on developing hypotheses and analyzing adversary Tactics, Techniques, and Procedures (TTPs). However, the conventional hunting process is heavily human-driven: analysts must manually interpret data, craft queries, and validate results. This dependency makes the practice resource-intensive, difficult to scale, and highly reliant on scarce expert talent.  </p>
 
<p align="justify">Recent advancements in Large Language Models (LLMs) present an opportunity to transform this paradigm. By reasoning over natural language and generating structured outputs, LLMs can bridge the gap between unstructured playbooks and actionable hunting queries. previous work Thelma Framework  , demonstrated the potential of LLMs to automate hypothesis generation and task prioritization. Yet, these approaches remained largely conceptual, lacking system-level implementations or rigorous validation. </p>

<p align="justify"> This Project moves beyond theory by delivering a fully functional LLM-powered threat hunting agent. The system automates critical processes—including script generation, validation and self-repair, task prioritization, and analyst feedback integration—significantly reducing human overhead while improving operational scalability. Furthermore, it explores the use of multi-agent architectures to distribute workloads, assessing how different allocation and prioritization strategies affect detection effectiveness. </p>

<p align="justify"> The system itself adopts a modular design to ensure extensibility and security. Its architecture consists of four layers: </p>

-  <b>Data Collection Layer</b> – aggregates structured knowledge from threat hunting playbooks and past hunting scripts.
-  <b>User Interaction Layer</b> – provides analysts with a graphical interface that supports endpoint management, hypothesis creation, and execution monitoring
- <b> Memory Layer</b> – acts as a secure intermediary, divided into short-term and long-term modules: short-term memory handles immediate tasks and temporary data, while long-term memory stores validated scripts, co-occurrence matrices, and reusable knowledge assets
-  <b>LLM Agent Layer</b> – serves as the intelligence core, featuring modules for script generation, co-occurrence analysis, validation/repair, and adaptive self-adjustment.

<p align="justify"> To address performance and scalability, the architecture supports multi-agent collaboration, enabling parallel task execution and improved efficiency in large-scale environments. This positions the system as a step forward in operationalizing AI-driven threat hunting, where automation augments human expertise rather than replacing it.</p>

[Back to the Top](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/Thelma/Evaluation%20of%20a%20novel%20LLM-based%20threat%20hunting%20system/README.md#----design-implementation-and-evaluation-of-a-novel-llm-based-threat-hunting-system--) | [Back to Thelma Project](https://github.com/ntust-im-labyrinth/labyrinth/blob/GilvyThelmaProjectM/projects/Thelma/README.md#----thelma-project--)
 ### 
