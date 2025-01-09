## 🎢 Major Deliverables

  * [Report 1 – Security Architecture](#rep1)
  * [Report 2 – Privacy Architecture](#rep2)


### 📹 Report 1 – Security Architecture  <a name = "rep1"></a>

This report aims to apply one of the security threat analysis frameworks learned in the classroom (Process for Attack Simulation and Threat Analysis (PASTA) or OCTAVE) to security threat modeling and analysis of the disaster relief system. Remember, the above frameworks aim to systematically model threats in a system using a risk-analysis approach and ensure that it complies with the system's business goal.

This task's deliverable is a report containing the insights of the security threat analysis framework. Remember that this task consists of modeling the disaster relief system, which requires detailed defining all of its functions, subfunctions, services, and providers. Remember that some technologies (MQTT, Mosquitto broker, etc.) are determined in advance and require you to complement the model, including how this solution is deployed in a real environment. It does not mean you must deploy the final code; however, the architecture must reflect all the required components [**YOU WILL CREATE A MODEL**].

A good starting point for this analysis is to read the material provided by the Federal Emergency Management Agency, which is a federal agency that helps Americans prepare for and recover from disasters. One of its documents is the [Local Disaster Recovery Managers Responsibilities](https://www.fema.gov/emergency-managers/national-preparedness/frameworks/community-recovery-management-toolkit/recovery-planning/local-disaster-recovery-managers-responsibilities).

The deliverable report must have the results of the framework steps and must be written following the IEEE template [Ulrich, Gael D. "Write a good technical report." IEEE Transactions on professional communication 1 (1984): 14-19](https://ieeexplore.ieee.org/abstract/document/6448763?casa_token=KhSLROZLNl0AAAAA:wwaG-hl135A6Ov_irj-cw9ghmWgOLv3jOltyvAQC7dQgvUCutuIds1RdVPQFjAGADLdKeQVD). 

Its report must discourse about these topics:
1.	**Introduction**: Contextualize the work and the disaster relief crises problem and provide technical context.
2.	**System Architecture**: description of the system with high technical detail, including the cloud component.
3.	**Threat Modeling Overview:** summarize the framework; please do not cite phase by phase, but the heart of the process, its benefits, and how it differs from the other approaches.
4.	**Threat Modeling Applied**: artifacts with context. It is a vital part of the work. Pay attention to the correctness. Do not only enumerate and paste diagrams; make context and give the reader a pleasant experience. Be concise and precise in the information provided. Ensure that the relationship between the diagram/artifact and the information provided is clear (what the reason for the diagram is, what it shows, and how to interpret the data).
    - During the mitigation definition, explaining how it reduces or suppresses the risk is crucial.
    - It is essential to show and explain the final architecture after implementing the proposed mitigations.
5.	**Final Remarks**: Analyze the results, cite limitations and challenges, make recommendations, and conclude the work.

The **paper must follow the IEEE template (two columns) and be 20 to 50 pages long**, including all the figures, attachments, etc. In addition, pay attention to these tips:
1.	focus on the main goal or problem you want to discuss.
2.	Spend more time on the problem description and result analysis.
3.	Avoid plagiarism.
4.	The target is to explain complex topics clearly.

To organize the paper, use the structure provided by the [IEEE](https://conferences.ieeeauthorcenter.ieee.org/write-your-paper/structure-your-paper/).

Each group member must also submit the **peer evaluation**, following the directions defined in the course syllabus.


### ⚒️💪 Report 2 – Privacy Architecture  <a name = "rep2"></a>

In the first report, we enumerate and analyze how security threats can impact the disaster relief system, define several controls to reduce or avoid them and update the solution's architecture. This report aims to systematically identify and address potential privacy issues in the system (Privacy Threat Modeling). This process includes analyzing the collection, storage, processing, and sharing of personal data to foresee and mitigate potential privacy violations.

During this activity, you will apply the LINDDUN privacy threat modeling methodology to the UTM system. The LINDDUN privacy threat modeling methodology is a systematic framework developed to address the challenges of ensuring privacy in software systems. Created by experts at KU Leuven, LINDDUN stands out for its structured approach to identifying and mitigating privacy threats throughout a software system's development lifecycle.

It is important to note that this **is not a completely separate report but an additional report**. The idea is not to make a new ad hoc analysis but to include privacy threats in your previous study, improving the system with privacy and design principles. **As in the first report, you must ultimately have an updated version of the system architecture that accomplishes the security and privacy requirements**.

The deliverable report must have the results of the framework steps and must be written following the IEEE template [Ulrich, Gael D. "Write a good technical report." IEEE Transactions on professional communication 1 (1984): 14-19](https://ieeexplore.ieee.org/abstract/document/6448763?casa_token=KhSLROZLNl0AAAAA:wwaG-hl135A6Ov_irj-cw9ghmWgOLv3jOltyvAQC7dQgvUCutuIds1RdVPQFjAGADLdKeQVD). 

Its report must discourse about these topics:
-	**Introduction**: Contextualize the work and the disaster relief crises problem and provide technical context.
-	**System Architecture**: a description of the system architecture developed in the first report, an explanation of its main components, and a description of how it ensures the required security properties of the system.
-	**Privacy Threat Modeling Overview**: give a summarized explanation about the LINDDUN; please do not cite phase by phase, but the heart of the process, its benefits, and how it differs from the other approaches
-	**Privacy Threat Modeling Applied**: artifacts with context. This is a vital part of the work. Please pay attention to its correctness. Do not only enumerate and paste diagrams; create context and give the reader a pleasant experience. Be concise and precise in the information provided. Ensure that the relationship between the diagram/artifact and the information provided is clear (what the reason for the diagram is, what it shows, and how to interpret the data).
      - During the mitigation definition, explaining how it reduces or suppresses the risk is crucial.
      - It is essential to show and explain the final architecture after implementing the proposed mitigations.
-	**Final Remarks**: Analyze the results, cite limitations and challenges, make recommendations, and conclude the work.

The paper must **follow the IEEE template (two columns) and be 20 to 60 pages long**, including all the figures, attachments, etc. In addition, pay attention to these tips:
1.	focus on the main goal or problem you want to discuss.
2.	Spend more time on the problem description and result analysis.
3.	Avoid plagiarism.
4.	The target is to explain complex topics clearly.
To organize the paper, use the structure provided by the [IEEE](https://conferences.ieeeauthorcenter.ieee.org/write-your-paper/structure-your-paper/).

Each group member must also submit the **peer evaluation**, following the directions defined in the course syllabus.