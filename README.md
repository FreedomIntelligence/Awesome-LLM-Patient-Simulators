# Awesome-LLM-Patient-Simulators <span style="font-size: 0.8em; color: #555;">✨</span>

[![Awesome LLM Patient Simulators](https://img.shields.io/static/v1?label=&message=Awesome+LLM+Patient+Simulators&color=1e88e5&style=flat-square&logo=awesomelists)](https://github.com/FreedomIntelligence/Awesome-LLM-Patient-Simulators)
[![Last Commit](https://img.shields.io/github/last-commit/FreedomIntelligence/Awesome-LLM-Patient-Simulators?color=4caf50&style=flat-square)](https://github.com/FreedomIntelligence/Awesome-LLM-Patient-Simulators/commits/main)
[![GitHub Stars](https://img.shields.io/github/stars/FreedomIntelligence/Awesome-LLM-Patient-Simulators?style=social&color=ff4081)](https://github.com/FreedomIntelligence/Awesome-LLM-Patient-Simulators)

<div style="font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif; line-height: 1.6; color: #333; max-width: 900px; margin: 0 auto; padding: 0 20px;">

This repository provides a curated collection of research papers on **Large Language Models (LLMs)** for patient simulation in healthcare, covering:

- 🏥 Virtual patient interactions  
- 🎓 Clinical training applications  
- 🔍 Diagnostic reasoning systems  
- 🧠 Mental health simulations  

</div>

## Table of Contents <span style="font-size: 0.8em; color: #666;">📋</span>

<div style="background-color: #f5f7fa; padding: 15px; border-radius: 8px; margin: 15px 0; font-size: 0.95em;">

- [Fundamental Research](#fundamental-research)
  - [Virtual Patient Development (Historical Context)](#virtual-patient-development-historical-context)
- [Methodology](#methodology)
  - [Agent Systems & Simulation Environments](#agent-systems--simulation-environments)
  - [NLP & Dialogue Systems](#nlp--dialogue-systems)
  - [Generative Models & Data Integration](#generative-models--data-integration)
  - [Prompt Engineering & Chatbots](#prompt-engineering--chatbots)
  - [Frameworks, Platforms & Workflows](#frameworks-platforms--workflows)
- [Applications](#applications)
  - [General Medical Education](#general-medical-education)
  - [Nurse Training](#nurse-training)
  - [Psychiatric Medicine](#psychiatric-medicine)
  - [Clinical Decision Support](#clinical-decision-support)
  - [Patient Communication Simulation](#patient-communication-simulation)
- [Evaluation Methods & Effects](#evaluation-methods--effects)
- [Challenges & Limitations](#challenges--limitations)
  - [Bias & Ethical Considerations](#bias--ethical-considerations)
- [Datasets](#datasets)

</div>

---

## <a id="fundamental-research"></a>🔍 Fundamental Research <span style="font-size: 0.8em; color: #666;">📚</span>

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Published in                                                                    | Focus Area                                            | Description| Data/Demo|
| :--------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ | :---------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Simulator Limitations and Their Effects on Decision-Making](https://journals.sagepub.com/doi/10.1177/154193129604001406)                              | [Sage](https://journals.sagepub.com/doi/10.1177/154193129604001406) 1996/10   | High-Fidelity Simulation Principles                 | Outlines **core principles of high-fidelity patient simulation** (dynamic case design, structured feedback, and behavioral assessment) that remain foundational for modern LLM-based patient simulation systems in medical education.                            | -|
| [Lessons Learned from the Usability Evaluation of a Simulated Patient Dialogue System](https://link.springer.com/article/10.1007/s10916-021-01737-4) | [Springer Link](https://link.springer.com/article/10.1007/s10916-021-01737-4) 2021/05 | Virtual Patient Dialogue System Usability           | Developed a virtual patient dialogue system for medical students to practice.                                                                                     | [Data](https://pvdial.limsi.fr/data/PG-logs-eval.zip) \| [Demo](http://vps-9069f76a.vps.ovh.net)                                                    |
| [The simulated patient method: Design and application in health services research](https://linkinghub.elsevier.com/retrieve/pii/S1551741121001625)      | [Science Direct](https://linkinghub.elsevier.com/retrieve/pii/S1551741121001625) 2021/12 | Simulated Patient Method Design (Health Services) | Explores the design and application of the simulated patient method in health services research, particularly in pharmacy practice.                           | -|
| [Patient-Drama: A Literature Review of Simulated Patient Experiences in Medical Education and Training](https://digitalcommons.lesley.edu/cgi/viewcontent.cgi?article=1581&context=expressive_theses)                        | [Lesley](https://digitalcommons.lesley.edu/expressive_theses/572/) 2022/04                               | Simulated Patient Experience                     | Examines **simulated patient experiences** through the lens of **drama therapy**. Four specific types of simulated patient experiences are examined- peer role play, peer simulation, standardized patient experiences, and clinical scenario drama.              | -|
| [The Role of ChatGPT, Generative Language Models, and Artificial Intelligence in Medical Education](https://mededu.jmir.org/2023/1/e46885)             | [JMIR Med Educ](https://mededu.jmir.org/2023/1/e46885) 2023/03                   | LLMs in Medical Education                             | Explores the potential application of ChatGPT and other generative language models in medical education, including virtual patient simulation.                | -|
| [From ChatGPT to DeepSeek: Can LLMs Simulate Humanity?](https://arxiv.org/pdf/2502.18210)                        | [arXiv](http://arxiv.org/abs/2502.18210) 2025/02                               | LLM Human Simulation Capabilities                     | Analyses LLMs' ability to simulate human behavior, discussing key limitations (e.g., bias, lack of incentives) and future alignment strategies.              | [Data(Appendix)](https://jmir.org/api/download?alt_name=jmir_v27i1e59435_app1.docx&filename=2ff26f0a7b3db530e6e1a74bd2a50323.docx)             | -|


### <a id="virtual-patient-development-historical-context"></a>🤒 Virtual Patient Development (Historical Context)

| Paper| Published in| Focus Area                                 | Description|
| :-------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------- | :----------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Virtual Patient Simulation at U.S. and Canadian Medical Schools](https://www.researchgate.net/publication/6372288_Virtual_Patient_Simulation_at_US_and_Canadian_Medical_Schools) | [ResearchGate (Orig. Acad Med)](https://www.researchgate.net/publication/6372288_Virtual_Patient_Simulation_at_US_and_Canadian_Medical_Schools) 2007 | VP Adoption in Medical Schools             | Examines the adoption, implementation, and educational impact of **virtual patient simulations** in **medical schools** across the U.S. and Canada.          |
| [High-fidelity patient simulation: considerations for effective learning.](https://www.researchgate.net/publication/47814051_High-fidelity_patient_simulation_Considerations_for_effective_learning) | [ResearchGate (Orig. J Contin Educ Health Prof)](https://www.researchgate.net/publication/47814051_High-fidelity_patient_simulation_Considerations_for_effective_learning) 2010/09 | High-Fidelity Simulation Design            | Examines **high-fidelity patient simulation in medical education**, emphasizing key design and implementation factors that optimize learning outcomes.       |
| [Virtual patient simulation: knowledge gain or knowledge loss?](https://pubmed.ncbi.nlm.nih.gov/20653378/)                                             | [BMC Medical Education](https://pubmed.ncbi.nlm.nih.gov/20653378/) 2010/09                                     | VP Effectiveness (Clinical Skills)         | Explores the use of **virtual patient** simulations in **medical education**, demonstrating their effectiveness in improving clinical decision-making skills.  |
| [Virtual patient simulation: what do students make of it? A focus group study](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91)   | [BMC Medical Education](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91) 2010/12         | VP Effectiveness (Student Perspective)     | Evaluates the effectiveness of **virtual patient simulations** in **medical education**, finding that they enhance clinical reasoning skills among students. |
| [Effectiveness of patient simulation in nursing education: meta-analysis.](https://www.sciencedirect.com/science/article/abs/pii/S0260691714003074)      | [Nurse Education Today](https://www.sciencedirect.com/science/article/abs/pii/S0260691714003074) 2015/01      | VP Effectiveness (Nursing Meta-Analysis) | Identify the best available evidence about the effects of **patient simulation** in **nursing education** through a meta-analysis.                           |
| [Guidelines for the design of a virtual patient for psychiatric interview training](https://link.springer.com/article/10.1007/s12193-020-00338-8)       | [Springer Link](https://link.springer.com/article/10.1007/s12193-020-00338-8) 2020/07                          | VP Design Guidelines (Psychiatry)        | Specific guidelines for **designing psychiatric virtual patients**... can be directly applied to LLM-driven patient simulation systems...                      |

</div>

---

## <a id="methodology"></a>🛠️ Methodology <span style="font-size: 0.8em; color: #666;">⚙️</span>

This section categorizes papers based on their core methodological contribution to LLM-based patient simulation.

### <a id="agent-systems--simulation-environments"></a>🤖 Agent Systems & Simulation Environments

Focus on systems using multiple interacting agents or complex agent behaviors.

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Submitted in                                                              | Description| Method                                                                                        | Code/Project/Data|
| :------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Towards Conversational Diagnostic AI](https://arxiv.org/pdf/2401.05654.pdf)                                                     | [arXiv](https://arxiv.org/abs/2401.05654) 2024/01                         | Introduces **AMIE**, an AI-driven system powered by LLMs that simulates virtual patient-doctor interactions for clinical education...                                            | LLM, **Agent (Implicit)**, Dialogue System                                                    | [Resource](https://github.com/Shivanshu-Gupta/web-scrapers/blob/master/medical_ner/medicinenet-diseases.json?utm_source=catalyzex.com)                                                                       |
| [Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents](https://arxiv.org/pdf/2405.02957.pdf)                   | [arXiv](https://arxiv.org/abs/2405.02957) 2024/05                         | Introduce a simulacrum of hospital called **Agent Hospital** that simulates the entire process of treating illness... all patients, nurses, and doctors are LLM-powered autonomous agents. | LLM, **Agent System**, Simulation Environment                                                 | [Dataset_MedQA](https://paperswithcode.com/dataset/medqa-usmle)|
| [AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator](https://arxiv.org/pdf/2402.09742.pdf) | [arXiv](http://arxiv.org/abs/2402.09742) 2024/06 (Revised)               | Introduces AI Hospital, a **multi-agent framework** for evaluating large language models in simulated medical interactions.                                                       | LLM, **Agent System**, Benchmark, Evaluation Framework                                        | [Project](https://github.com/LibertFan/AI_Hospital) \| [Dataset_MVME](https://paperswithcode.com/dataset/mvme) \| [Dataset_MedQA](https://paperswithcode.com/dataset/medqa-usmle) \| [Dataset_PubMedQA](https://paperswithcode.com/dataset/pubmedqa) \| [Dataset_MedMCQA](https://paperswithcode.com/dataset/medmcqa)                       |
| [Towards a Client-Centered Assessment of LLM Therapists by Client Simulation](https://arxiv.org/pdf/2406.12266.pdf)               | [arXiv](https://arxiv.org/abs/2406.12266) 2024/06                         | Proposes ClientCAST, a novel LLM-based client simulation framework to assess the performance of AI therapists...                                                              | LLM, **Agent (Client Simulation)**, Evaluation Framework                                      | [Project](https://github.com/wangjs9/ClientCAST) \| [Dataset_AnnoMI](https://paperswithcode.com/dataset/annomi)|
| [AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow](https://arxiv.org/pdf/2409.18924.pdf)  | [arXiv](https://arxiv.org/abs/2409.18924) 2024/10                         | Presents a novel **agentic workflow** combining **EHR** knowledge graphs with Reasoning-RAG architecture.                                                                 | LLM, **Agent System**, RAG, Knowledge Graph, EHR Integration                                  | [Code](https://www.catalyzex.com/paper/aipatient-simulating-patients-with-ehrs-and/code) \| [Data (MIMIC-III)](https://paperswithcode.com/dataset/mimic-iii)                                                        |
| [LLMs Can Simulate Standardized Patients via Agent Coevolution](https://arxiv.org/pdf/2412.11716.pdf)  | [arXiv](http://arxiv.org/abs/2412.11716) 2024/12                         | Introduces the **EvoPatient framework**, which utilizes **multi-agent coevolution** to enable LLMs to simulate standardized patients...                                            | LLM, **Agent System**, **Coevolution**                                                        | [Project](https://github.com/ZJUMAI/EvoPatient)|
| [Scaffolding Empathy: Training Counselors with Simulated Patients and Utterance-level Performance Visualizations](https://arxiv.org/pdf/2502.18673.pdf)  | [arXiv](http://arxiv.org/abs/2502.18673) 2025/02                         | Introduces a LLM-based multi-agent system (SimPatient) with dynamic cognitive modeling and real-time feedback to enhance motivational interviewing (MI) training...        | LLM, **Agent System**, Cognitive Modeling, Feedback Visualization                             | -|
| [Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions](https://arxiv.org/pdf/2503.22678.pdf)  | [arXiv](https://arxiv.org/abs/2503.22678) 2025/03                         | introduce **MedAgentSim**, an open-source simulated clinical environment with doctor, patient, and measurement agents designed to evaluate... LLM performance...               | LLM, **Agent System**, Simulation Environment, Evaluation                                     | [Dataset_MedQA](https://paperswithcode.com/dataset/medqa-usmle)|

</div>

### <a id="nlp--dialogue-systems"></a>🗣️ NLP & Dialogue Systems

Focus on natural language processing techniques and the architecture of dialogue systems, including hybrid approaches.

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Submitted in                                                                                      | Description| Method                                                                 | Code/Project/Data |
| :------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------- | :---------------- |
| [Artificial intelligence in virtual standardized patients: Combining natural language understanding and rule based dialogue management...](https://www.tandfonline.com/doi/pdf/10.1080/0142159X.2022.2130216) | [Medical Teacher](https://www.tandfonline.com/doi/full/10.1080/0142159X.2022.2130216) 2022/11 | Developed **a novel hybrid dialogue system** using **ASR, hybrid AI, and automated speech generation**, enabling artificially intelligent **VSPs**...                 | **NLP**, **Dialogue System**, Rule-based AI, ASR, Speech Generation    | -                 |

</div>

### <a id="generative-models--data-integration"></a>🧬 Generative Models & Data Integration

Focus on the use of generative models for tasks like data augmentation, image generation, or integrating structured data.

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Submitted in                                                                                            | Description| Method                                                                                         | Code/Project/Data                                                                                             |
| :------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| [Automated Generation of High-Quality Medical Simulation Scenarios Through Integration of Semi-Structured Data and Large Language Models](https://arxiv.org/pdf/2404.19713.pdf) | [arXiv](https://arxiv.org/abs/2404.19713) 2024/05                                                      | Introduces a semi-structured data and LLM-integrated framework to automate the generation of medical simulation scenarios...                                                    | LLM, **Structured Data Integration**, RAG (Implicit), Scenario Generation                    | -|
| [MedDiT: A Knowledge-Controlled Diffusion Transformer Framework for Dynamic Medical Image Generation in Virtual Simulated Patient](http://arxiv.org/pdf/2408.12236v1)  | [arXiv](http://arxiv.org/abs/2408.12236) 2024/08                                                      | Introduces MedDiT, a knowledge-controlled diffusion transformer framework designed to dynamically generate medical images for virtual simulated patients.               | **Transformer**, **Diffusion Models**, **Generative Models**, Knowledge Control, Image Generation | -|
| [Augmenting Insufficiently Accruing Oncology Clinical Trials Using Generative Models: Validation Study](https://www.jmir.org/2025/1/e66821/PDF)  | [JMIR](https://www.jmir.org/2025/1/e66821) 2025/03                                                      | Explores the use of generative models to augment oncology clinical trials with insufficient patient accrual, validating their effectiveness in simulating additional patient data to improve trial outcomes.                      | **Generative Models**, Data Augmentation                                                     | [Data (Appendix)](https://jmir.org/api/download?alt_name=jmir_v27i1e66821_app1.pdf&filename=1b8ee696dd8ab5638b213dcf7d139fb8.pdf) |

</div>

### <a id="prompt-engineering--chatbots"></a>💬 Prompt Engineering & Chatbots

Focus on the direct application of LLMs via carefully crafted prompts or chatbot interfaces as the primary contribution.

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Submitted in                                                                                            | Description| Method                                        | Code/Project/Data                                                                                             |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| [A Generative Pretrained Transformer (GPT)–Powered Chatbot as a Simulated Patient to Practice History Taking...](https://mededu.jmir.org/2024/1/e53961/PDF) | [JMIR](https://mededu.jmir.org/2024/1/e53961) 2024/01                                                  | Employs **a GPT-powered chatbot as a simulated patient**, using meticulously crafted prompts to replicate realistic clinical interactions...                          | LLM, **Prompt Engineering**, **Chatbot**      | [Data(Appendix)](https://jmir.org/api/download?alt_name=mededu_v10i1e53961_app1.pdf&filename=afea0cccea2a67adc54d26ef18fd7da4.pdf) |
| [Application of Large Language Models in Medical Training Evaluation—Using ChatGPT as a Standardized Patient...](https://www.jmir.org/2025/1/e59435/PDF)  | [JMIR](https://www.jmir.org/2025/1/e59435) 2025/01                                                      | Optimized ChatGPT for medical standardized patient simulation via prompt engineering, enhancing clinical accuracy and realism.                                          | LLM, **Prompt Engineering**, Evaluation       | [Data(Appendix)](https://jmir.org/api/download?alt_name=jmir_v27i1e59435_app1.docx&filename=2ff26f0a7b3db530e6e1a74bd2a50323.docx) |

</div>

### <a id="frameworks-platforms--workflows"></a>🏗️ Frameworks, Platforms & Workflows

Focus on integrated systems, platforms, specific workflows, or hardware integrations for patient simulation.

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Submitted in                                                                               | Description| Method                                                              | Code/Project/Data                                            |
| :----------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------ | :----------------------------------------------------------- |
| [Creating Virtual Patients using Robots and Large Language Models: A Preliminary Study with Medical Students](https://dl.acm.org/doi/pdf/10.1145/3610978.3640592) | [ACM](https://dl.acm.org/doi/10.1145/3610978.3640592) 2024/03                                | Presents **a virtual patient platform combining the social robot Furhat with LLMs (GPT-3.5-turbo)** to enhance clinical reasoning training...                             | LLM, Generative Models, **Robotics Integration**, Dialogue System | -                                                            |
| [Leveraging Large Language Model as Simulated Patients for Clinical Education](https://arxiv.org/pdf/2404.13066.pdf)      | [arXiv](http://arxiv.org/abs/2404.13066) 2024/04                                           | Introduces **CureFun**, an **integrated framework** that utilizes LLMs as simulated patients for clinical education, enhancing student-patient dialogues...                            | LLM, **Framework**, Evaluation                                    | -                                                            |
| [RasPatient Pi: A Low-Cost Customizable LLM-Based Virtual Standardized Patient Simulator](https://link.springer.com/chapter/10.1007/978-3-031-75147-9_9) | [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-75147-9_9) 2025 (*Year inferred*) | Presents **RasPatient Pi**, a low-cost, customizable virtual standardized patient simulator based on Large Language Models (LLMs).                                    | LLM, **Hardware Integration (Raspberry Pi)**, **Framework**       | [Project](https://github.com/cgrevisse/raspatientpi)         |

</div>

---
## <a id="applications"></a>🏥 Applications <span style="font-size: 0.8em; color: #666;">🩺</span>

<div style="margin: 20px 0;">

### <a id="general-medical-education"></a>🩺 General Medical Education

<div style="overflow-x: auto;">

| Paper| Published in| Description| Key Feature/System| Code/Project/Data|
| :----------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| [Virtual patient simulation: what do students make of it? A focus group study.](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91)         | [BMC Med Educ](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91) 2010                        | Evaluates **virtual patient simulations in medical training**, concluding that they significantly improve clinical reasoning skills...                                            | Virtual Patient Simulation                                                                                             | -|
| [Using virtual standardized patients to accurately assess information gathering skills in medical students](https://www.tandfonline.com/doi/full/10.1080/0142159X.2019.1616683) | [Medical Teacher](https://www.tandfonline.com/doi/full/10.1080/0142159X.2019.1616683) 2019/06                  | Developed a **virtual standardized patient system** that can understand, respond, categorize, and assess student performance... enabling students to practice **history-taking**... | Virtual Standardized Patient (VSP) System, Automated Assessment                                                        | -|
| [The Role of Large Language Models in Medical Education: Applications and Implications](https://mededu.jmir.org/2023/1/e50945/PDF)                              | [JMIR](https://mededu.jmir.org/2023/1/e50945) 2023/08                                                             | Shows LLMs can simulate patient encounters for medical education but lack nonverbal communication and may exhibit biases.                                                     | LLM for Patient Encounters                                                                                             | -|
| [Virtual Standardized LLM-AI Patients for Clinical Practice](https://www.researchgate.net/publication/387328695_ANNUAL_REVIEW_OF_CYBERTHERAPY_AND_TELEMEDICINE_2024#page=172) | [Annual Review of CyberTherapy and Telemedicine](https://www.researchgate.net/publication/387328695... ) 2024/01 | Explores the use of virtual standardized AI patients powered by LLMs to enhance clinical practice and therapy training.                                                     | LLM-AI Patients| -|
| [Enhancing communication and clinical reasoning in medical education: Building virtual patients with generative AI](https://www.sciencedirect.com/science/article/pii/S2514664524001553?via%3Dihub) | [Future Healthcare Journal](https://www.sciencedirect.com/science/article/pii/S2514664524001553?via%3Dihub) 2024/04 | Demonstrates the viability of using LLM technology, specifically GPT-3.5 and GPT-4, to create realistic virtual patients.                                                     | Generative AI (GPT-3.5, GPT-4) for VP Creation                                                                         | -|
| [Utilizing generative conversational artificial intelligence to create simulated patient encounters... anaesthesia training](https://academic.oup.com/pmj/article/100/1182/237/7571383) | [Postgraduate Medical Journal](https://academic.oup.com/pmj/article/100/1182/237/7571383) 2024/04                  | Explores the use of **generative conversational artificial intelligence** to create simulated patients for medical education, ‘Convai’ was used...                             | Generative Conversational AI (Convai)                                                                                  | -|
| [Simulating Diverse Patient Populations Using Patient Vignettes and Large Language Models](https://aclanthology.org/2024.cl4health-1.3.pdf)                    | [ACL Anthology](https://aclanthology.org/2024.cl4health-1.3/) 2024/05                                             | Demonstrates how LLMs like GPT-4 can simulate diverse patient populations via role-prompted vignettes, enabling cost-effective testing...                                     | LLM (GPT-4), Patient Vignettes, Role-Prompting                                                                         | -|
| [Roleplay-doh: Enabling Domain-Experts to Create LLM-simulated Patients via Eliciting and Adhering to Principles](https://arxiv.org/pdf/2407.00870.pdf)        | [arXiv](http://arxiv.org/abs/2407.00870) 2024/07                                                                 | Introduces Roleplay-doh, a tool that enables domain experts to collaboratively create realistic AI patient simulations by providing qualitative feedback.                     | Roleplay-doh Tool, Collaborative Creation, Qualitative Feedback                                                        | [Project](https://roleplay-doh.github.io/)                                                                                    |
| [Creating virtual patients using large language models: scalable, global, and low cost](https://pubmed.ncbi.nlm.nih.gov/38992981/)                             | [PubMed (Cureus)](https://pubmed.ncbi.nlm.nih.gov/38992981/) 2024/07                                             | Presents a low-cost, AI-driven virtual patient (LLM-VP) system using LLMs like GPT-4 for clinical reasoning training...                                                   | LLM-VP System (GPT-4 based)                                                                                            | -|
| [A Language Model-Powered Simulated Patient With Automated Feedback for History Taking: Prospective Study](https://mededu.jmir.org/2024/1/e59213)              | [JMIR](https://mededu.jmir.org/2024/1/e59213) 2024/08                                                             | Presents a language model-powered simulated patient designed to enhance history-taking skills... providing automated feedback...                                                | LLM Simulated Patient, Automated Feedback                                                                              | -|
| [Enhancing Medical Interview Skills Through AI-Simulated Patient Interactions: Nonrandomized Controlled Trial](https://mededu.jmir.org/2024/1/e58753)          | [JMIR](https://mededu.jmir.org/2024/1/e58753) 2024/09                                                             | Demonstrates that AI-simulated patient interactions effectively enhance medical interview skills in a nonrandomized controlled trial...                                         | AI-Simulated Patient Interactions                                                                                      | -|
| [Enhancing Patient-Centric Communication: Leveraging LLMs to Simulate Patient Perspectives](https://arxiv.org/pdf/2501.06964.pdf) (*Note: Link uses original ID 2501*) | [arXiv](http://arxiv.org/abs/2501.06964) 2025/01                                                                 | Explores LLM-based patient simulation via **persona prompts**, showing higher accuracy for educated groups but biases against underserved populations.                      | LLM, Persona Prompts                                                                                                   | -|
| [MedSimAI: Simulation and Formative Feedback Generation to Enhance Deliberate Practice in Medical Education](https://arxiv.org/pdf/2503.05793.pdf) (*Note: Link uses original ID 2503*) | [arXiv](http://arxiv.org/abs/2503.05793) 2025/03                                                                 | Introduces **MedSimAI**, an AI-driven platform designed to enhance medical education by providing realistic simulations and formative feedback.                            | MedSimAI Platform, Simulation, Formative Feedback                                                                      | -|

</div>

### <a id="nurse-training"></a>👩‍⚕️ Nurse Training

<div style="overflow-x: auto;">

| Paper| Published in                                                                                  | Description                                                                                                   | Key Feature/System                  |
| :-------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------ | :---------------------------------- |
| [Evaluation of Large Language Model Generated Dialogues for an AI Based VR Nurse Training Simulator](https://link.springer.com/chapter/10.1007/978-3-031-61041-7_13) | [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-61041-7_13) 2024/06 | Evaluates the efficacy of LLM-generated dialogues (GPT-3.5, Bard, ClaudeAI) for VR nurse training simulators | LLM (GPT-3.5, Bard, ClaudeAI), VR |

</div>

### <a id="psychiatric-medicine"></a>🧠 Psychiatric Medicine

<div style="overflow-x: auto;">

| Paper| Published in                                                                                           | Description| Key Feature/System                                    | Code/Project/Data                                        |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------- | :------------------------------------------------------- |
| [Embodied Virtual Patients as a Simulation-Based Framework for Training Clinician-Patient Communication Skills... Psychiatric and Geriatric Care](https://www.frontiersin.org/articles/10.3389/frvir.2022.827312/full) | [Frontiers](https://www.frontiersin.org/journals/virtual-reality/articles/10.3389/frvir.2022.827312/full) 2022/06 | The application of virtual patients in psychiatric and geriatric care is explored, especially for training doctor-patient communication skills.                           | Embodied Virtual Patients                             | -                                                        |
| [LLM-empowered Chatbots for Psychiatrist and Patient Simulation: Application and Evaluation](https://arxiv.org/pdf/2305.13614)                                       | [arXiv](https://arxiv.org/pdf/2305.13614) 2023/05                                                      | Demonstrates ChatGPT's feasibility in powering psychiatric patient and doctor chatbots, validated through real clinician-patient evaluations...                               | LLM (ChatGPT), Chatbots (Patient & Doctor Simulation) | -                                                        |
| [PATIENT-Ψ: Using Large Language Models to Simulate Patients for Training Mental Health Professionals](https://arxiv.org/pdf/2405.19660v3)                           | [arXiv](http://arxiv.org/abs/2405.19660) 2024/10 (Revised)                                           | Introduces PATIENT-Ψ, an LLM-based patient simulation system for training mental health professionals in cognitive behavioral therapy.                                      | PATIENT-Ψ System, LLM, CBT Training                   | -                                                        |
| [PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents](https://arxiv.org/pdf/2501.01594v1) (*Note: Link uses original ID 2501*) | [arXiv](http://arxiv.org/abs/2501.01594) 2025/01                                                      | Presents PSYCHE, a multi-faceted patient simulation framework designed to evaluate psychiatric assessment conversational agents...                                            | PSYCHE Framework, Evaluation Framework                | -                                                        |

</div>

### <a id="clinical-decision-support"></a>⚕️ Clinical Decision Support

<div style="overflow-x: auto;">

| Paper| Published in                                                                    | Description| Key Feature/System                                  | Data/Appendix                                                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------- | :-------------------------------------------------------------------------------------------------- |
| [Large language models improve clinical decision making of medical students through patient simulation and structured feedback: a randomized controlled trial](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/) | [PubMed Central (BMJ HCI)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/) 2024/11 | Demonstrates that AI-simulated medical history conversations, particularly when combined with structured feedback, can enhance clinical decision-making skills in medical students. | LLM Patient Simulation, Structured Feedback       | [Data(Appendix)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/#_ad93_)                         |

</div>

### <a id="patient-communication-simulation"></a>💬 Patient Communication Simulation

<div style="overflow-x: auto;">

| Paper| Published in                                                        | Description| Key Feature/System                          |
| :---------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------ |
| [Beyond the Script: Testing LLMs for Authentic Patient Communication Styles in Healthcare](https://arxiv.org/pdf/2503.22250.pdf) (*Note: Link uses original ID 2503*) | [arXiv](https://arxiv.org/abs/2503.22250) 2025/03                 | Proposes the use of Large Language Models (LLMs) to simulate authentic patient communication styles and these VPs are evaluated by medical professionals.                      | LLM, Authentic Communication Style Simulation |
| [Modeling Challenging Patient Interactions: LLMs for Medical Communication Training](https://arxiv.org/pdf/2503.22250.pdf) (*Note: Link uses original ID 2503*) | [arXiv](https://arxiv.org/abs/2503.22250) 2025/03                 | Proposes the use of Large Language Models (LLMs) to simulate authentic patient communication styles, specifically personas derived from the Satir model... multilingual applicability. | LLM, Persona Simulation (Satir), Multilingual |

</div>

</div>

---

v## <a id="evaluation-methods--effects"></a>☑️ Evaluation Methods & Effects <span style="font-size: 0.8em; color: #666;">🚨</span>

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Published in                                                                                       | Focus                                            | Description| Project/Benchmark                                                    |
| :--------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- | :----------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------- |
| [Analyzing evaluation methods for large language models in the medical field: a scoping review](https://doi.org/10.1186/s12911-024-02709-7)       | [BMC Med Inform Decis Mak](https://doi.org/10.1186/s12911-024-02709-7) 2024/11                    | LLM Evaluation Review (Medical)                  | Reviews studies on **LLM evaluations in the medical field** and analyzes the research methods used in these studies.                                                                | -                                                                    |
| [NPHardEval: Dynamic Benchmark on Reasoning Ability of Large Language Models via Complexity Classes](https://arxiv.org/pdf/2312.14890.pdf)         | [arXiv](https://arxiv.org/abs/2312.14890) 2024/02 (Revised)                                        | LLM Reasoning Benchmark                          | Introduces NPHardEval, a dynamic benchmark grounded in computational complexity classes... to rigorously **evaluate LLMs' reasoning abilities**...                                   | [NPHardEval Project](https://github.com/casmlab/NPHardEval)         |
| [NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models](https://arxiv.org/pdf/2403.01777.pdf)                            | [arXiv](https://arxiv.org/abs/2403.01777) 2024/03                                                 | Multimodal LLM Reasoning Benchmark               | Introduces NPHardEval4V, a dynamic **multimodal benchmark designed to evaluate** the pure reasoning abilities of MLLMs... revealing significant gaps between MLLM and LLM reasoning... | [NPHardEval4V Project](https://github.com/lizhouf/NPHardEval4V)     |
| [Assessing the efficacy of ChatGPT as a virtual patient in nursing simulation training...](https://www.sciencedirect.com/science/article/abs/pii/S1557308724000337) | [ScienceDirect (Nurse Educ Pract)](https://www.sciencedirect.com/science/article/abs/pii/S1557308724000337) 2024/07 | ChatGPT Effectiveness Assessment (Nursing) | Assessed ChatGPT's effectiveness in nursing simulation by collecting data of acceptability, accessibility, engagement ratings, and assessing students' interaction skills.           | -                                                                    |

</div>

---

## <a id="challenges--limitations"></a>⚠️ Challenges & Limitations <span style="font-size: 0.8em; color: #666;">🚨</span>

<div style="margin: 20px 0; overflow-x: auto;">

| Paper| Published in                                       | Focus Area                 | Description|
| :-------------------------------------------------------------------------------------------------------------- | :------------------------------------------------- | :------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [A Survey of Large Language Models in Medicine: Progress, Application, and Challenge](https://arxiv.org/pdf/2311.05112.pdf) | [arXiv](https://arxiv.org/abs/2311.05112) 2024/07 (Revised) | LLM in Medicine Survey     | The applications of LLM in medicine are reviewed, covering the challenges of patient simulation (such as dynamic interaction and realism).                           |

### <a id="bias--ethical-considerations"></a>🎭 Bias & Ethical Considerations

| Paper| Published in                                                                 | Focus Area                       | Description|
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------- | :------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Ethical Considerations in the Use of Artificial Intelligence and Machine Learning in Health Care: A Comprehensive Review](https://pmc.ncbi.nlm.nih.gov/articles/PMC11249277/)      | [PubMed Central (Cureus)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11249277/) 2024/06 | AI/ML Ethics in Healthcare     | Explored the multifaceted ethical considerations in the use of AI and ML in health care, including privacy, algorithmic bias, transparency, validation, and professional responsibility.          |
| [The Role of Humanization and Robustness of Large Language Models in Conversational Artificial Intelligence for Individuals With Depression...](https://www.jmir.org) (*Note: Specific paper link needed*) | [JMIR](https://www.jmir.org) 2024/07 (*Tentative*)                           | LLM Humanization/Robustness (Depression AI) | Analyzes LLMs' humanization and robustness in depression-focused AI, revealing emotional understanding gaps and proposing enhancement strategies. (*Note: PDF link was example.com*) |

</div>

---

## <a id="datasets"></a>📊 Datasets <span style="font-size: 0.8em; color: #666;">💾</span>

<div style="margin: 20px 0; overflow-x: auto;">

This section lists datasets and project repositories mentioned in the papers that are either generated by the simulation process or used for evaluation and grounding. Note that project repositories may contain various resources including code, configuration files, and potentially simulation data or logs. Appendices often contain supplementary information like prompts or evaluation rubrics rather than reusable datasets.

### Simulation Dialogue, Configuration & Resources

| Dataset/Resource         | Paper Year | Language | Data Type            | Project/Code| Link                                                              |
| :----------------------- | :--------- | :------- | :------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------- |
| PG-logs-eval             | 2021/05    | French   | Dialogue Logs        | -| [Link](https://pvdial.limsi.fr/data/PG-logs-eval.zip)             |
| medicinenet-diseases.json| 2024/01    | English  | Disease List         | [Code Repo](https://github.com/Shivanshu-Gupta/web-scrapers/blob/master/medical_ner/medicinenet-diseases.json?utm_source=catalyzex.com) | [Link](https://github.com/Shivanshu-Gupta/web-scrapers/blob/master/medical_ner/medicinenet-diseases.json?utm_source=catalyzex.com) |
| ClientCAST Framework     | 2024/06    | English  | Simulation Framework | [Project](https://github.com/wangjs9/ClientCAST)                                                                                        | [Project Link](https://github.com/wangjs9/ClientCAST)             |
| EvoPatient Framework     | 2023/12    | English  | Simulation Framework | [Project](https://github.com/ZJUMAI/EvoPatient)                                                                                         | [Project Link](https://github.com/ZJUMAI/EvoPatient)              |
| RasPatient Pi            | 2025 (*Year inferred*) | English  | Simulation Framework | [Project](https://github.com/cgrevisse/raspatientpi)                                                                                    | [Project Link](https://github.com/cgrevisse/raspatientpi)         |
| Roleplay-doh Tool        | 2024/07    | English  | Simulation Tool      | [Project](https://roleplay-doh.github.io/)                                                                                              | [Project Link](https://roleplay-doh.github.io/)                   |
| AIPatient Workflow       | 2024/10    | English  | Agentic Workflow     | [Code](https://www.catalyzex.com/paper/aipatient-simulating-patients-with-ehrs-and/code)                                                  | [Code Link](https://www.catalyzex.com/paper/aipatient-simulating-patients-with-ehrs-and/code) |

### Evaluation & Grounding Datasets

| Dataset      | Task Type                  | Language   | Access     | Used In Paper (Year)      | Link                                                          | Project (if applicable)                                 |
| :----------- | :------------------------- | :--------- | :--------- | :------------------------ | :------------------------------------------------------------ | :------------------------------------------------------ |
| MIMIC-III    | EHR Data                   | English    | Restricted | 2024/10 (AIPatient)       | [Link](https://paperswithcode.com/dataset/mimic-iii)          | -                                                       |
| MedQA (USMLE)| Medical QA                 | English    | Public     | 2024/05, 2024/06, 2025/03 | [Link](https://paperswithcode.com/dataset/medqa-usmle)        | [AI Hospital](https://github.com/LibertFan/AI_Hospital) |
| MVME         | Medical Vision/Language    | Multimodal | Public     | 2024/06 (AI Hospital)     | [Link](https://paperswithcode.com/dataset/mvme)               | [AI Hospital](https://github.com/LibertFan/AI_Hospital) |
| PubMedQA     | Biomedical QA              | English    | Public     | 2024/06 (AI Hospital)     | [Link](https://paperswithcode.com/dataset/pubmedqa)           | [AI Hospital](https://github.com/LibertFan/AI_Hospital) |
| MedMCQA      | Medical QA (India)         | English    | Public     | 2024/06 (AI Hospital)     | [Link](https://paperswithcode.com/dataset/medmcqa)            | [AI Hospital](https://github.com/LibertFan/AI_Hospital) |
| AnnoMI       | Motivational Interviewing  | English    | Public     | 2024/06 (ClientCAST)      | [Link](https://paperswithcode.com/dataset/annomi)             | [ClientCAST](https://github.com/wangjs9/ClientCAST)     |
| NPHardEval   | LLM Reasoning Benchmark    | English    | Public     | 2024/02                   | [Project Link](https://github.com/casmlab/NPHardEval)         | [NPHardEval](https://github.com/casmlab/NPHardEval)     |
| NPHardEval4V | MLLM Reasoning Benchmark   | Multimodal | Public     | 2024/03                   | [Project Link](https://github.com/lizhouf/NPHardEval4V)       | [NPHardEval4V](https://github.com/lizhouf/NPHardEval4V) |

</div>

---

## ⭐ Star History <span style="font-size: 0.8em; color: #666;">📈</span>

<div style="text-align: center; margin: 30px 0;">

<a href="https://star-history.com/#FreedomIntelligence/Awesome-LLM-Patient-Simulators&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=FreedomIntelligence/Awesome-LLM-Patient-Simulators&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=FreedomIntelligence/Awesome-LLM-Patient-Simulators&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=FreedomIntelligence/Awesome-LLM-Patient-Simulators&type=Date" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);" />
  </picture>
</a>

</div>
