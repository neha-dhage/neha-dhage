## Hi there 👋

<!--
**neha-dhage/neha-dhage** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

##- I am a recent graduate from School of Information at UC Berkeley with Master of Information and Cyber Security (MICS)
##and Certificate in Applied Data Science, with academic research and projects focused on AI security, Adversarial
##Machine Learning, and Policy-driven Governance of emerging technologies. I am a Cybersecurity and Technology risk
##professional with over nine years of experience in enterprise security governance, risk and control and auditing,
##across financial services and technology industries. I am experienced in translating complex technical risks into
##actionable governance and control frameworks and collaborating with cross-functional stakeholders including
##engineers, security teams, regulators, and policy practitioners.

##- My expertise includes -  
##      - AI and Cyber Security, Machine Learning (ML) and Adversarial ML, Natural Language Processing and Deep
##      Learning
##      - AI Risk Governance & Technology Policy, Enterprise Security Governance, Risk and Controls, Risk Assessment
##      and Mitigation.
##      - Cross-functional Collaboration, Stakeholder/Client Relationship Management and Communication.
##      - Collaborative documentation tools, Technical Documentation and Analytical Reporting, Policy and procedure
##      creation.
      
##- My recent education, research and project details - 

##University of California, Berkeley - 

##MASTER OF INFORMATION AND CYBERSECURITY (MICS) AUG 2024 – MAY 2026
##CERTIFICATE OF APPLIED DATA SCIENCE JAN 2025 – AUG 2025

##Coursework –
##o Web Application Security Assessment
##o Cryptography for Cyber and Network Security
##o Operating Systems Security
##o Network Security
##o Software Security
##o Security Operations
##o Privacy Engineering
##o Applied Machine Learning for Cybersecurity
##o Natural Language Processing with Deep Learning
##o Research Design and Applications for Data and Analysis

##Research and Technical projects in Adversarial Machine Learning, Deep Learning, Natural Language
##Processing and Agent Security-

##1) Agent Credential Firewall (CAPSTONE PROJECT - SPRING 2026)

Agent Credential Firewall is a capstone project that explores how organizations can securely manage
and control the use of credentials by autonomous AI agents interacting with enterprise systems. As AI
agents increasingly perform tasks such as sending emails, querying databases, and interacting with
SaaS applications on behalf of users, they operate using delegated credentials that were originally
designed for deterministic software and/or human users. This creates new security risks, including
credential misuse, unauthorized data access, automated data exfiltration and confused-agent risk. This
project implemented a policy-based enforcement layer, referred to as the Agent Credential Firewall,
that evaluates agent actions in real time before they are executed. Using Open Policy Agent (OPA) and
a set of defined security rules, the system analyzed contextual signals such as recipient domains, data
sensitivity, behavioral patterns, and authorization constraints to determine whether an action should
be allowed or denied. Through simulated scenarios and test cases, the project demonstrated how a
credential firewall can mitigate risks introduced by agentic systems and provide a practical framework
for securing AI-driven automation in enterprise environments. The designed structured scenarios and
policy rule sets can serve as instructional case studies for teaching AI security governance and
enterprise risk management.

2) Membership Inference attacks and Differential Privacy (FALL 2025)

This project built and evaluated a machine learning models to test how vulnerable it is to membership
inference attacks and whether differential privacy can meaningfully reduce that risk. First,
convolutional neural network classifiers were trained on standard image classification datasets and a
confidence-based membership inference attack was executed. The attack attempted to determine
whether a given record was part of the training dataset by using maximum SoftMax confidence as the
signal for prediction. Then the models were retrained using Differentially Private Stochastic Gradient
Descent (DP-SGD) with varying privacy budgets and re-ran the same attack to measure whether the
privacy mechanism reduced the attacker’s ability to distinguish members from non-members. Our
results showed that non-private models leaked statistically meaningful membership information, while
models trained with DP-SGD, especially with stronger privacy parameters, reduced attack success to
near-random guessing, albeit with an associated loss in model accuracy.

3) Manipulative Language Detection in LLM-Crafted Phishing Attacks (SUMMER 2025)

This project investigated whether Natural language Processing (NLP) models can effectively detect
manipulative language in text, with a specific focus on phishing emails crafted using large language
models (LLMs). Since phishing attacks exploit psychological vulnerabilities through subtle, persuasive
language, the project focused on identifying manipulation i.e., language intended to influence a
reader against their best interest. Using the MentalManip dataset, which contained thousands of film
dialogues labeled with fine-grained manipulation techniques, we fine-tuned transformer-based
models including BERT and RoBERTa to detect these linguistic patterns. Then, we evaluated whether
the models could generalize to real-world phishing emails, especially those missed by existing filters.
The research examined whether linguistic manipulation detection could strengthen phishing defenses
in cybersecurity context beyond traditional spam detection approaches, and the results showed both
the promise and the limitations of this method: while fine-tuned models performed well on
manipulation detection, generalization to real phishing emails remained challenging due to class
imbalance and format differences between training and target dataset.

4) Fast Gradient Sign Method (FGSM) Adversarial Attack on ResNet-18 model using ImageNet data
and defense techniques Gaussian noise and JPEG compression. (SPRING 2025)

In this project, we evaluated the adversarial robustness of a pre-trained ResNet-18 model using
samples from the ImageNet dataset. We implemented the Fast Gradient Sign Method (FGSM) to
generate adversarial examples by adding carefully crafted perturbations to the input images, aiming to
reduce the model’s classification accuracy. To counteract these attacks, we tested two defense
techniques: Gaussian noise and JPEG compression. Gaussian noise was added as a random
perturbation to obscure adversarial patterns, while JPEG compression aimed to remove
high-frequency components introduced by the attack. We then assessed the model’s accuracy across
clean, adversarial, and defended inputs to determine the effectiveness of each defense strategy in
mitigating the impact of FGSM. This experiment demonstrated the vulnerability of deep learning
models to simple gradient-based attacks and explored the potential of input-level transformations as
lightweight adversarial defenses. The project concluded that ResNet-18 is highly sensitive to carefully
crafted adversarial perturbations, attack success increases with increase in perturbation strengths,
and simple input-transformation defenses can help, with JPEG compression outperforming Gaussian
noise for subtle FGSM attacks.

CITRIS and The Banatao Institute – UC Berkeley - TECH POLICY DESIGN: PLATFORM GOVERNANCE FOR AN AI-DRIVEN WORLD (OCT 2025 – FEB 2026)

This course engaged students from various schools at UC Berkeley with pressing issues in trust and safety,
content moderation, algorithmic transparency, legislative process in California and US and emerging
regulatory trends by applying design-thinking and policy frameworks to real-world challenges. The course
was led by Camille Crittenden (Executive Director, CITRIS), David Evan Harris, (Chancellor’s Scholar – Haas
School of Business), Naomi Schiffman (Oversight Board) and Nichole Rocha (Omidyar Group).
 - Analyzed current legislation, amendments, Opposition and Support artefacts, recent technological
advances and studies and relevant legislative efforts in other US states.
- Developed concrete policy recommendations for legislations in progress and developed policy
recommendations addressing trust, safety, and algorithmic transparency.
- Collaborated with interdisciplinary (Law, Public Policy, Computer and Data Science and Social Science)
teams to analyze technology governance challenges and developed presentations and policy analyses for
academic and policy audiences.
- Program culminated in final presentations to legislative staffers, policymakers and other key stakeholders
at Sacramento in Feb 2026.

 - Relevant Certifications
      Cybersecurity Audit Certificate (CSXA) – (#2024-920143-CSXA) Apr. 2024
      Certified in Cybersecurity (CC) – (#729604) Dec. 2023
      Certified Third-Party Risk Assessor (CTPRA) –#45571 Sep. 2021
      Certified Data Privacy Solutions Engineer (CDPSE) – #2114689 Mar. 2021
      Certified Information Systems Auditor (CISA) – #16135170
 
 - Professional Experience

ISC2 (International Information System Security Certification Consortium). San Ramon, CA
Security Certifications Designer and Review SME Apr 2024 – May2024

Selected by the International Information System Security Certification Consortium (ISC2) to develop and
review globally recognized security certification exams.
Drafted exam questions and answers, reviewed peer submissions for accuracy and quality, and ensured
alignment with industry standards.
Led and participated in roundtable discussions to shape exam content and maintain the integrity of
certification programs for candidates worldwide.

Career Break San Ramon, CA
Period of focused preparation for Graduate school and Security certifications. Sept 2023 – Aug 2024

BANK OF MONTREAL (Formerly Bank of the West). San Ramon, CA
Senior Auditor II, Vice President – Technology Internal Audit Oct 2017 – Sept 2023

- Led and managed enterprise-wide IT and Cyber security audits with a team of four associates and cross functional
teams.
- Performed project management activities and managed the audit plan including timeline, budget, resource
availability, communication and relationship with auditees by building collaborative partnerships with auditees
and senior executives.
- Presented Internal Audit documentation to Federal regulators periodically and managed communication with
regulator resulting in successful Regulatory reviews were successful and without incident.
- Enhanced audit work programs to ensure compliance with standardized audit guidance, and industry best
practices, to create customized testing procedures. This helped to build efficiency within Internal audit team.
- Reviewed audit documentation prepared by staff/team to ensure completeness and accuracy of deliverables.
 - Mentored and trained junior auditors on cybersecurity frameworks and audit methodology, translating
technical concepts into structured training and guidance, resulting in highly trained staff.


ERNST & YOUNG (EY), Sacramento, CA
Senior IT Auditor — Risk Advisory Services Jun 2014 – Aug 2017

- Led IT advisory and attestation projects in accordance with industry audit standards and regulatory requirements for large public and private entities (more than 10,000 employees) in Technology, Healthcare and Retail industry.
- Assessed design and operating effectiveness of IT and application controls, identified key risks and exceptions in controls framework and provided independent opinions on internal control over financial reporting.
- Issued detailed findings, observations and recommendations to clients.
- Issued SOC1/SOC2/SOC3 (SSAE) reports as per SSAE guidance for public companies in the Technology industry.
- Successfully managed multiple concurrent audit projects while working through substantial scope changes and complexity leading to efficient and timely delivery of audit results.
 - Produced structured, technical and written and visual materials explaining complex security systems, risks, and governance frameworks for diverse audiences including regulators, engineers, executives, and policymakers.

SAPIENS (Formerly Adaptik Corporation), Bethlehem, PA
Software Quality Assurance Analyst Aug 2012 – Jun 2014

Managed software and system testing, lifecycle of defects, and response to production issues as the Software
Quality Assurance Analyst for Property and Casualty (P&C) Insurance software solution suite.

COGNIZANT TECHNOLOGY SOLUTIONS, Pune, India
Software Engineer Nov 2009 – Jul 2010

Managed product delivery for Mainframe banking application and acted as liaison between client, offshore, and
onsite teams for solution delivery

TECH MAHINDRA (Formerly Satyam Computer Services), Pune, India
Software Engineer Sep 2006 – Nov 2009

Designed and implemented new solutions for Mainframe banking applications. Led the entire lifecycle of product
development including delivery and support post implementation. Trained new staff on best practices for software
development.

Publication - 

Published research – Braunschweig, B., Dhage, N., Viera, M. J., Seaman, C., Sampath, S., & Koru, A. G. (2012).
Studying volatility predictors in open source software. In Proceedings of the 2012 ACM-IEEE International
Symposium on Empirical Software Engineering and Measurement (pp. 181-190). IEEE.
https://doi.org/10.1145/2372251.2372286

Earlier Education - 
     
      University of Maryland, Baltimore County - MASTER OF SCIENCE (MS), INFORMATION SYSTEMS, MD 2010 - 2012 GPA 3.972

      Relevant coursework –
      - Advanced Database Projects
      - Structural System Analysis and Design
      - Project and Systems Engineering Management
      - Project Management Operations
      - Financial Management
      - Advanced Field Research Methods - (Qualitative Research Methods)
      - Advanced Experimental Design Methods - (Quantitative Research Methods)

      Nagpur University, India BACHELOR OF ENGINEERING (BE), ELECTRICAL ENGINEERING 2002 - 2006
**
