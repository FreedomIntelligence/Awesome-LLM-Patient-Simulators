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
  - [Virtual Patient Development](#virtual-patient-development)
- [Methodology](#methodology)
  - [Agent Systems](#agent-systems)
  - [NLP Techniques](#nlp-techniques)
  - [Generative Models](#generative-models)
  - [Transformer Architectures](#transformer-architectures)
  - [Prompt Engineering](#prompt-engineering)
- [Applications](#applications)
  - [General Medical Education](#general-medical-education)
  - [Nurse Training](#nurse-training)
  - [Psychiatric Medicine](#psychiatric-medicine)
  - [Clinical Decision Support](#clinical-decision-support)
  - [Patient Communication Simulation](#patient-communication-simulation)
- [Evaluation Methods & Effects](#evaluation-methods--effects)
- [Challenges & Limitations](#challenges--limitations)
  - [Bias & Ethical Considerations](#bias--ethical-considerations)

</div>

---

## <a id="fundamental-research"></a>🔍 Fundamental Research <span style="font-size: 0.8em; color: #666;">📚</span>

<div style="margin: 20px 0;">

#### (1996/1)）Simulator Limitations and Their Effects on Decision-Making  
[Sage](https://journals.sagepub.com/doi/10.1177/154193129604001406)  
*Outlines **core principles of high-fidelity patient simulation** (dynamic case design, structured feedback, and behavioral assessment) that remain foundational for modern LLM-based patient simulation systems in medical education.*

#### (2021/05) Lessons Learned from the Usability Evaluation of a Simulated Patient Dialogue System  
[Springer Link](https://link.springer.com/article/10.1007/s10916-021-01737-4) | [Data](https://pvdial.limsi.fr/data/PG-logs-eval.zip) | [Demo](http://vps-9069f76a.vps.ovh.net)  
*Developed a virtual patient dialogue system for medical students to practice.*

#### (2021/12) The simulated patient method: Design and application in health services research  
[Science Direct](https://linkinghub.elsevier.com/retrieve/pii/S1551741121001625)  
*Explores the design and application of the simulated patient method in health services research, particularly in pharmacy practice.*

#### (2023/03) The Role of ChatGPT, Generative Language Models, and Artificial Intelligence in Medical Education: A Conversation With ChatGPT and a Call for Papers  
[JMIR Med Educ](https://mededu.jmir.org/2023/1/e46885) | [pdf](https://mededu.jmir.org/2023/1/e46885/PDF) | [Call for Papers](https://mededu.jmir.org/announcements/365)  
*Explores the potential application of ChatGPT and other generative language models in medical education, including virtual patient simulation.*

#### (2025/02) From ChatGPT to DeepSeek: Can LLMs Simulate Humanity?  
[arXiv](http://arxiv.org/abs/2502.18210) | [pdf](https://arxiv.org/pdf/2502.18210) | [Data](https://jmir.org/api/download?alt_name=jmir_v27i1e59435_app1.docx&filename=2ff26f0a7b3db530e6e1a74bd2a50323.docx)  
*Analyses LLMs' ability to simulate human behavior, discussing key limitations (e.g., bias, lack of incentives) and future alignment strategies.*

### <a id="virtual-patient-development"></a>🤒 Virtual Patient Development

#### (2007) Virtual Patient Simulation at U.S. and Canadian Medical Schools  
[PudMed](https://www.researchgate.net/publication/6372288_Virtual_Patient_Simulation_at_US_and_Canadian_Medical_Schools)  
*Examines the adoption, implementation, and educational impact of **virtual patient simulations** in **medical schools** across the U.S. and Canada.*

#### (2010/12) Virtual patient simulation: what do students make of it? A focus group study  
[BMC Medical Education](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91)  
*Evaluates the effectiveness of **virtual patient simulations** in **medical education**, finding that they enhance clinical reasoning skills and knowledge retention among students.*

#### (2010) Virtual patient simulation: knowledge gain or knowledge loss?  
[BMC Medical Education](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91)  
*Explores the use of **virtual patient** simulations in **medical education**, demonstrating their effectiveness in improving clinical decision-making and diagnostic skills among learners.*

#### (2015) Effectiveness of patient simulation in nursing education: meta-analysis.  
[Nurse Education Today](https://www.sciencedirect.com/science/article/abs/pii/S0260691714003074)  
*Identify the best available evidence about the effects of **patient simulation** in **nursing education** through a meta-analysis.*

#### (2010) High-fidelity patient simulation: considerations for effective learning.  
[Nurse Education Today](https://www.researchgate.net/publication/47814051_High-fidelity_patient_simulation_Considerations_for_effective_learning)  
*Examines **high-fidelity patient simulation in medical education**, emphasizing key design and implementation factors that optimize learning outcomes*

#### (2015) Effectiveness of patient simulation in nursing education: meta-analysis.  
[Nurse Education Today](https://www.sciencedirect.com/science/article/abs/pii/S0260691714003074)  
*Identify the best available evidence about the effects of **patient simulation** in **nursing education** through a meta-analysis.*

#### (2020/07) Guidelines for the design of a virtual patient for psychiatric interview training  
[Springer Link](https://link.springer.com/article/10.1007/s12193-020-00338-8)  
*Specific guidelines for **designing psychiatric virtual patients** (e.g., symptom plausibility and simulation of resistance behaviors) are provided, and these principles can be directly applied to LLM-driven patient simulation systems, especially in prompt design.*

</div>

---

## <a id="methodology"></a>🛠️ Methodology <span style="font-size: 0.8em; color: #666;">⚙️</span>

<div style="margin: 20px 0;">

### <a id="agent-systems"></a>🤖 Agent Systems

#### (2024/01) Towards Conversational Diagnostic AI  
[arXiv](https://arxiv.org/abs/2401.05654)  
*Introduces **AMIE**, an AI-driven system powered by LLMs that simulates virtual patient-doctor interactions for clinical education, enhancing diagnostic reasoning and medical history-taking skills.*

#### (2024/06) AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator  
[arXiv](http://arxiv.org/abs/2402.09742) | [Project](https://github.com/LibertFan/AI_Hospital)  
*Introduces AI Hospital, a **multi-agent framework** for evaluating large language models in simulated medical interactions.*

#### (2024/06) Towards a Client-Centered Assessment of LLM Therapists by Client Simulation  
[arXiv](https://arxiv.org/abs/2406.12266) | [Project](https://github.com/wangjs9/ClientCAST)  
*Proposes ClientCAST, a novel LLM-based client simulation framework to assess the performance of AI therapists through standardized questionnaires and interaction analysis.*

#### (2024/10) AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow  
[arXiv](https://arxiv.org/abs/2409.18924) | [Code](https://www.catalyzex.com/paper/aipatient-simulating-patients-with-ehrs-and/code) | [Data](https://paperswithcode.com/dataset/mimic-iii)  
*Presents a novel **agentic workflow** combining **EHR** knowledge graphs with Reasoning-RAG architecture.*

#### (2024/12) LLMs Can Simulate Standardized Patients via Agent Coevolution  
[arXiv](http://arxiv.org/abs/2412.11716) | [Project](https://github.com/ZJUMAI/EvoPatient)  
*Introduces the **EvoPatient framework**, which utilizes **multi-agent coevolution** to enable large language models to simulate standardized patients and autonomously improve diagnostic and interaction processes.*

#### (2025/02) Scaffolding Empathy: Training Counselors with Simulated Patients and Utterance-level Performance Visualizations  
[arXiv](http://arxiv.org/abs/2502.18673)  
*Introduces a LLM-based multi-agent system (SimPatient) with dynamic cognitive modeling and real-time feedback to enhance motivational interviewing (MI) training through interactive patient simulations.*

#### (2025/03) Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions
[arXiv](https://arxiv.org/abs/2503.22678)  
*introduce MedAgentSim, an open-source simulated clinical environment with doctor, patient, and measurement agents designed to evaluate and enhance LLM performance in dynamic diagnostic settings.*

### <a id="nlp-techniques"></a>💬 NLP Techniques

#### (2022/11) Artificial intelligence in virtual standardized patients: Combining natural language understanding and rule based dialogue management to improve conversational fidelity  
[Medical Teacher](https://www.tandfonline.com/doi/full/10.1080/0142159X.2022.2130216)  
*Developed a novel hybrid dialogue system using ASR, hybrid AI, and automated speech generation, enabling artificially intelligent VSPs to correctly answer student questions at levels comparable with human SPs.*

#### (2024/05) Automated Generation of High-Quality Medical Simulation Scenarios Through Integration of Semi-Structured Data and Large Language Models  
[arXiv](https://arxiv.org/abs/2404.19713) | [pdf](https://arxiv.org/pdf/2404.19713)  
*Introduces a semi-structured data and LLM-integrated framework to automate the generation of medical simulation scenarios, significantly reducing development time while maintaining clinical and educational relevance.*

#### (2025) RasPatient Pi: A Low-Cost Customizable LLM-Based Virtual Standardized Patient Simulator  
[Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-75147-9_9) | [Project](https://github.com/cgrevisse/raspatientpi)  
*Presents **RasPatient Pi**, a low-cost, customizable virtual standardized patient simulator based on Large Language Models (LLMs).*

### <a id="generative-models"></a>🎨 Generative Models

#### (2024/03) Creating Virtual Patients using Robots and Large Language Models: A Preliminary Study with Medical Students  
[ACM](https://dl.acm.org/doi/10.1145/3610978.3640592)  
*Presents **a virtual patient platform combining the social robot Furhat with LLMs (GPT-3.5-turbo)** to enhance clinical reasoning training, demonstrating improved authenticity and learning effects compared to traditional semi-linear VP systems.*

#### (2024/04) Leveraging Large Language Model as Simulated Patients for Clinical Education  
[arXiv](http://arxiv.org/abs/2404.13066)  
*Introduces **CureFun**, an **integrated framework** that utilizes LLMs as simulated patients for clinical education, enhancing student-patient dialogues, providing real-time evaluations, and improving medical training through realistic, AI-driven interactions.*

#### (2024/04) Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents  
[arXiv](https://arxiv.org/abs/2405.02957)  
*Introduce a simulacrum of hospital called **Agent Hospital** that simulates the entire process of treating illness, in which all patients, nurses, and doctors are LLM-powered autonomous agents.*

#### (2025/03) Augmenting Insufficiently Accruing Oncology Clinical Trials Using Generative Models: Validation Study  
[JMIR](https://www.jmir.org/2025/1/e66821) | [Data](https://jmir.org/api/download?alt_name=jmir_v27i1e66821_app1.pdf&filename=1b8ee696dd8ab5638b213dcf7d139fb8.pdf)  
*Explores the use of generative models to augment oncology clinical trials with insufficient patient accrual, validating their effectiveness in simulating additional patient data to improve trial outcomes.*

### <a id="transformer-architectures"></a>🖼️ Transformer Architectures

#### (2024/08) MedDiT: A Knowledge-Controlled Diffusion Transformer Framework for Dynamic Medical Image Generation in Virtual Simulated Patient  
[arXiv](http://arxiv.org/abs/2408.12236) | [pdf](http://arxiv.org/pdf/2408.12236v1)  
*Introduces MedDiT, a knowledge-controlled diffusion transformer framework designed to dynamically generate medical images for virtual simulated patients.*

### <a id="prompt-engineering"></a>✏️ Prompt Engineering

#### (2024/01) A Generative Pretrained Transformer (GPT)–Powered Chatbot as a Simulated Patient to Practice History Taking: Prospective, Mixed Methods Study  
[JMIR](https://mededu.jmir.org/2024/1/e53961) | [pdf](https://jmir.org/api/download?alt_name=mededu_v10i1e53961_app1.pdf&filename=afea0cccea2a67adc54d26ef18fd7da4.pdf)  
*Employs **a GPT-powered chatbot as a simulated patient**, using meticulously crafted prompts to replicate realistic clinical interactions for medical history-taking practice, demonstrating the **potential of LLMs in standardized patient training.***

#### (2025/01) Application of Large Language Models in Medical Training Evaluation—Using ChatGPT as a Standardized Patient: Multimetric Assessment  
[JMIR](https://www.jmir.org/2025/1/e59435) | [pdf](https://www.jmir.org/2025/1/e59435/PDF)  
*Optimized ChatGPT for medical standardized patient simulation via prompt engineering, enhancing clinical accuracy and realism.*

</div>

---

## <a id="applications"></a>🏥 Applications <span style="font-size: 0.8em; color: #666;">🩺</span>

<div style="margin: 20px 0;">

### <a id="general-medical-education"></a>🩺 General Medical Education

#### (2010) Virtual patient simulation: what do students make of it? A focus group study.  
[BMC Med Educ](https://bmcmededuc.biomedcentral.com/articles/10.1186/1472-6920-10-91)  
*Evaluates **virtual patient simulations in medical training**, concluding that they significantly improve clinical reasoning skills and knowledge application compared to traditional methods.*

#### (2019/06) Using virtual standardized patients to accurately assess information gathering skills in medical students  
[Medical Teacher](https://www.tandfonline.com/doi/full/10.1080/0142159X.2019.1616683)  
*Developed a **virtual standardized patient system** that can understand, respond, categorize, and assess student performance, thus enabling students to practice their **history-taking skills** and receive immediate feedback.*

#### (2023/08) The Role of Large Language Models in Medical Education: Applications and Implications  
[JMIR](https://mededu.jmir.org/2023/1/e50945) | [pdf](https://mededu.jmir.org/2023/1/e50945/PDF)  
*Shows LLMs can simulate patient encounters for medical education but lack nonverbal communication and may exhibit biases.*

#### (2024/01) Virtual Standardized LLM-AI Patients for Clinical Practice  
[Annual Review of CyberTherapy and Telemedicine](https://www.researchgate.net/publication/387328695_ANNUAL_REVIEW_OF_CYBERTHERAPY_AND_TELEMEDICINE_2024#page=172)  
*Explores the use of virtual standardized AI patients powered by LLMs to enhance clinical practice and therapy training.*

#### (2024/04) Enhancing communication and clinical reasoning in medical education: Building virtual patients with generative AI  
[Future Healthcare Journal](https://www.sciencedirect.com/science/article/pii/S2514664524001553?via%3Dihub)  
*Demonstrates the viability of using LLM technology, specifically GPT-3.5 and GPT-4, to create realistic virtual patients.*

#### (2024/04) Utilizing generative conversational artificial intelligence to create simulated patient encounters: a pilot study for anaesthesia training  
[Postgraduate Medical Journal](https://academic.oup.com/pmj/article/100/1182/237/7571383)  
*Explores the use of **generative conversational artificial intelligence** to create simulated patients for medical education, ‘Convai’ was used to simulating a patient, with whom trainee doctors can interact with.*

#### (2024/05) Simulating Diverse Patient Populations Using Patient Vignettes and Large Language Models  
[ACL Anthology](https://aclanthology.org/2024.cl4health-1.3/) | [pdf](https://aclanthology.org/2024.cl4health-1.3.pdf)  
*Demonstrates how LLMs like GPT-4 can simulate diverse patient populations via role-prompted vignettes, enabling cost-effective testing of digital therapeutics and medical training with clinically valid responses.*

#### (2024/07) Roleplay-doh: Enabling Domain-Experts to Create LLM-simulated Patients via Eliciting and Adhering to Principles  
[arXiv](http://arxiv.org/abs/2407.00870) | [Project](https://roleplay-doh.github.io/)  
*Introduces Roleplay-doh, a tool that enables domain experts to collaboratively create realistic AI patient simulations by providing qualitative feedback.*

#### (2024/07) Creating virtual patients using large language models: scalable, global, and low cost  
[PubMed](https://pubmed.ncbi.nlm.nih.gov/38992981/)  
*Presents a low-cost, AI-driven virtual patient (LLM-VP) system using LLMs like GPT-4 for clinical reasoning training, demonstrating scalable implementation and potential to democratize medical education.*

#### (2024/08) A Language Model-Powered Simulated Patient With Automated Feedback for History Taking: Prospective Study  
[JMIR](https://mededu.jmir.org/2024/1/e59213)  
*Presents a language model-powered simulated patient designed to enhance history-taking skills in medical education, providing automated feedback to improve student performance in clinical settings.*

#### (2024/09) Enhancing Medical Interview Skills Through AI-Simulated Patient Interactions: Nonrandomized Controlled Trial  
[JMIR](https://mededu.jmir.org/2024/1/e58753)  
*Demonstrates that AI-simulated patient interactions effectively enhance medical interview skills in a nonrandomized controlled trial, highlighting their potential for clinical training.*

#### (2025/01) Enhancing Patient-Centric Communication: Leveraging LLMs to Simulate Patient Perspectives  
[arXiv](http://arxiv.org/abs/2501.06964)  
*Explores LLM-based patient simulation via **persona prompts**, showing higher accuracy for educated groups but biases against underserved populations.*

#### (2025/03) MedSimAI: Simulation and Formative Feedback Generation to Enhance Deliberate Practice in Medical Education  
[arXiv](http://arxiv.org/abs/2503.05793)  
*Introduces **MedSimAI**, an AI-driven platform designed to enhance medical education by providing realistic simulations and formative feedback.*

### <a id="nurse-training"></a>👩‍⚕️ Nurse Training

#### (2024/06) Evaluation of Large Language Model Generated Dialogues for an AI Based VR Nurse Training Simulator  
[Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-61041-7_13)  
*Evaluates the efficacy of LLM-generated dialogues (GPT-3.5, Bard, ClaudeAI) for VR nurse training simulators*

### <a id="psychiatric-medicine"></a>🧠 Psychiatric Medicine

#### (2022/06 ) Embodied Virtual Patients as a Simulation-Based Framework for Training Clinician-Patient Communication Skills: An Overview of Their Use in Psychiatric and Geriatric Care  
[Frontiers](https://www.frontiersin.org/journals/virtual-reality/articles/10.3389/frvir.2022.827312/full)   
*The application of virtual patients in psychiatric and geriatric care is explored, especially for training doctor-patient communication skills.*

#### (2023/05) LLM-empowered Chatbots for Psychiatrist and Patient Simulation: Application and Evaluation  
[arXiv](https://arxiv.org/pdf/2305.13614) | [pdf](https://arxiv.org/pdf/2305.13614)  
*Demonstrates ChatGPT's feasibility in powering psychiatric patient and doctor chatbots, validated through real clinician-patient evaluations of diagnostic dialogue quality.*

#### (2024/10) PATIENT-Ψ: Using Large Language Models to Simulate Patients for Training Mental Health Professionals  
[arXiv](http://arxiv.org/abs/2405.19660) | [pdf](http://arxiv.org/pdf/2405.19660v3)  
*Introduces PATIENT-Ψ, an LLM-based patient simulation system for training mental health professionals in cognitive behavioral therapy.*

#### (2025/01) PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents  
[arXiv](http://arxiv.org/abs/2501.01594) | [pdf](http://arxiv.org/pdf/2501.01594v1)  
*Presents PSYCHE, a multi-faceted patient simulation framework designed to evaluate psychiatric assessment conversational agents, assessing their performance in realistic patient interactions for mental health evaluations.*

### <a id="clinical-decision-support"></a>⚕️ Clinical Decision Support

#### (2024/11) Large language models improve clinical decision making of medical students through patient simulation and structured feedback: a randomized controlled trial  
[PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/) | [Data](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/#_ad93_)  
*Demonstrates that AI-simulated medical history conversations, particularly when combined with structured feedback, can enhance clinical decision-making skills in medical students.*

### <a id="patient-communication-simulation"></a>💬 Patient Communication Simulation

#### (2025/03) Beyond the Script: Testing LLMs for Authentic Patient Communication Styles in Healthcare
[arXiv](https://arxiv.org/abs/2503.22250)  
*Proposes the use of Large Language Models (LLMs) to simulate authentic patient communication styles and these VPs are evaluated by medical professionals.*


</div>

---

## <a id="evaluation-methods--effects"></a>☑️ Evaluation Methods & Effects <span style="font-size: 0.8em; color: #666;">🚨</span>

<div style="margin: 20px 0;">

#### (2024/11) Analyzing evaluation methods for large language models in the medical field: a scoping review  
[BMC](https://doi.org/10.1186/s12911-024-02709-7)  
*Reviews studies on **LLM evaluations in the medical field** and analyzes the research methods used in these studies.*

#### (2024/02) NPHardEval: Dynamic Benchmark on Reasoning Ability of Large Language Models via Complexity Classes  
[arXiv](https://arxiv.org/abs/2312.14890) | [project](https://github.com/casmlab/NPHardEval)  
*Introduces NPHardEval, a dynamic benchmark grounded in computational complexity classes (P, NP-complete, NP-hard) to rigorously **evaluate LLMs' reasoning abilities**, featuring automated question generation and monthly updates to mitigate overfitting.*

#### (2024/03) NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models  
[arXiv](https://arxiv.org/abs/2403.01777) | [project](https://github.com/lizhouf/NPHardEval4V)  
*Introduces NPHardEval4V, a dynamic **multimodal benchmark designed to evaluate** the pure reasoning abilities of MLLMs by converting NP-hard textual problems into visual-textual inputs, revealing significant gaps between MLLM and LLM reasoning performance.*

#### (2024/07) Assessing the efficacy of ChatGPT as a virtual patient in nursing simulation training: A study on nursing students' experience
[ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S1557308724000337)  
*Assessed ChatGPT's effectiveness in nursing simulation by collecting data of acceptability, accessibility, engagement ratings, and assessing students' virtual patient interaction skills.*

</div>

---

## <a id="challenges--limitations"></a>⚠️ Challenges & Limitations <span style="font-size: 0.8em; color: #666;">🚨</span>

<div style="margin: 20px 0;">

#### (2024/07) A Survey of Large Language Models in Medicine: Progress, Application, and Challenge
  
[arXiv]([https://pmc.ncbi.nlm.nih.gov/articles/PMC11249277/](https://arxiv.org/abs/2311.05112))  
*The applications of LLM in medicine are reviewed, covering the challenges of patient simulation (such as dynamic interaction and realism).*

### <a id="bias--ethical-considerations"></a>🎭 Bias & Ethical Considerations

#### (2024/06) Ethical Considerations in the Use of Artificial Intelligence and Machine Learning in Health Care: A Comprehensive Review  
[PubMed](https://pmc.ncbi.nlm.nih.gov/articles/PMC11249277/)  
*Explored the multifaceted ethical considerations in the use of AI and ML in health care, including privacy and data security, algorithmic bias, transparency, clinical validation, and professional responsibility.*

#### (2024/07) The Role of Humanization and Robustness of Large Language Models in Conversational Artificial Intelligence for Individuals With Depression: A Critical Analysis  
[JMIR](https://www.jmir.org) | [pdf](https://example.com/pdf)  
*Analyzes LLMs' humanization and robustness in depression-focused AI, revealing emotional understanding gaps and proposing enhancement strategies.*

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
