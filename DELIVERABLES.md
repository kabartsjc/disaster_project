## 🎢 Major Deliverables

  * [Report 1 – Security Architecture](#rep1)
  * [Step 2 – Reply to your peers (5%)](#ice_reply)
* [Collaboration (80%)](#collaboration)
  * [Step 1 – Project Setup (10%)](#col_set)
  * [Step 2 – Client & Edge Stage (10%)](#col_cli)
  * [Step 3 – Cloud Stage (10%)](#col_cloud)
  * [Step 4 – Final Presentation (50%)](#col_ppt)
* [Reflection (10%)](#reflection)


### 📹 Report 1 – Security Architecture  <a name = "rep1"></a>

This report aims to apply one of the security threat analysis frameworks learned in the classroom (Process for Attack Simulation and Threat Analysis (PASTA) or OCTAVE) to security threat modeling and analysis of the disaster relief system. Remember, the above frameworks aim to systematically model threats in a system using a risk-analysis approach and ensure that it complies with the system's business goal.

This task's deliverable is a report containing the insights of the security threat analysis framework. Remember that this task consists of modeling the disaster relief system, which requires detailed defining all of its functions, subfunctions, services, and providers. Remember that some technologies (MQTT, Mosquitto broker, etc.) are determined in advance and require you to complement the model, including how this solution is deployed in a real environment. It does not mean you must deploy the final code; however, the architecture must reflect all the required components [**YOU WILL CREATE A MODEL**].

A good starting point for this analysis is to read the material provided by the Federal Emergency Management Agency, which is a federal agency that helps Americans prepare for and recover from disasters. One of its documents is the [Local Disaster Recovery Managers Responsibilities](https://www.fema.gov/emergency-managers/national-preparedness/frameworks/community-recovery-management-toolkit/recovery-planning/local-disaster-recovery-managers-responsibilities).

The deliverable report must have the results of the framework steps and must be written following the IEEE template [Ulrich, Gael D. "Write a good technical report." IEEE Transactions on professional communication 1 (1984): 14-19](https://ieeexplore.ieee.org/abstract/document/6448763?casa_token=KhSLROZLNl0AAAAA:wwaG-hl135A6Ov_irj-cw9ghmWgOLv3jOltyvAQC7dQgvUCutuIds1RdVPQFjAGADLdKeQVD). 

Its report must discourse about these topics:
*	Introduction: Contextualize the work and the disaster relief crises problem and provide technical context.
*	System Architecture: description of the system with high technical detail, including the cloud component.
*	Threat Modeling Overview (summarize the framework; please do not cite phase by phase, but the heart of the process, its benefits, and how it differs from the other approaches).
*	Threat Modeling Applied: artifacts with context. It is a vital part of the work. Pay attention to the correctness. Do not only enumerate and paste diagrams; make context and give the reader a pleasant experience. Be concise and precise in the information provided. Ensure that the relationship between the diagram/artifact and the information provided is clear (what the reason for the diagram is, what it shows, and how to interpret the data).
  * During the mitigation definition, explaining how it reduces or suppresses the risk is crucial.
  * It is essential to show and explain the final architecture after implementing the proposed mitigations.
*	Final Remarks: Analyze the results, cite limitations and challenges, make recommendations, and conclude the work.

The **paper must follow the IEEE template (two columns) and be 20 to 50 pages long**, including all the figures, attachments, etc. In addition, pay attention to these tips:
1.	focus on the main goal or problem you want to discuss.
2.	Spend more time on the problem description and result analysis.
3.	Avoid plagiarism.
4.	The target is to explain complex topics clearly.

To organize the paper, use the structure provided by the [IEEE](https://conferences.ieeeauthorcenter.ieee.org/write-your-paper/structure-your-paper/).

Each group member must also submit the **peer evaluation**, following the directions defined in the course syllabus.


### 💬💬 Step 2 – Reply to your peers  <a name = "ice_reply"></a>

Once you have posted your message, reply to at least two other students (**from the other country**) that you don't know, and comment on what you find interesting about their post. The follow-up posts should consist of one well-crafted paragraph, including an introductory sentence and finishing a section with a concluding statement or question.
-	Did you find something interesting in your peer's post? Do you observe any differences or similarities with your peers? Do you have any advice for them?
-	After someone comments on your post, reply or react to the observations received.

**You can be as creative as you want; we only ask you to keep an attitude of respect and be careful with any content that might be considered offensive.**

#### Rubric
- **(100 points):** You respond to at least two of your colleagues. You track the comments they add to your post.
- **(80 points):** You respond to only one colleague. You track the comments they add to your post.
- **(50 points):** You responded to only one colleague; however, you did not track the comments they added to your post.
- **(0 points):** You did not respond to any colleague.


## ⚒️💪 Collaboration <a name = "collaboration"></a>

The **Multicultural Collaborative Activity** is the main scenario of the model, and as its name indicates, it consists of at least one collaborative activity carried out in multicultural teams; that is, students from both institutions work together to meet a common goal. Teachers decide the type of activity to be carried out (project, case analysis, problem-solving, etc.), with the delivery of a final product (essay, report, video, presentation, etc.) mandatory.

### 👷‍♂️ Step 1 – Project Setup  <a name = "col_set"></a>

During this activity, the students will identify the technical and non-technical requirements of the project using user stories, write the requirement documents, and set the project in GitHub (defining the artifacts). You can use these support materials to learn how to do:
- [GitHub Project Management Tutorial - Setup GitHub Projects & Automations](https://www.youtube.com/watch?v=ff5cBkPg-bQ)
- [GitHub Project Management: How to Boost Productivity by Using It](https://everhour.com/blog/project-management-using-github/)

To write good user stories, you can use these references:
- [Agile User Story Principles and its Benefits | The Complete Guide](https://www.xenonstack.com/blog/agile-user-story)
- [User stories with examples and a template](https://www.atlassian.com/agile/project-management/user-stories#:~:text=For%20example%2C%20user%20stories%20might,report%20our%20sucess%20and%20failures).

Finally, the students will create a README file following these approaches: 
-	[Best-README-Template](https://github.com/othneildrew/Best-README-Template)
-	[How to Write a Good README File for Your GitHub Project](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)

#### Rubric
- **(100 points):** The group sets the GitHub project; all the required features are defined, and the requirements are complete (it defines the acceptance criteria). The README file shows what is the project and its motivation.
- **(80 points):** The group sets the GitHub project; all the required features are defined, but the requirements are incomplete (it does not define the acceptance criteria). The README file shows what is the project and its motivation.
- **(50 points):** The group sets the GitHub project; however, it misses part of the required information. Ex.:  There are features not defined, the requirements are incomplete, or the README file does not show what is the project or its motivation.
- **(0 points):** The group does not set the GitHub project.

### 🕵️ Step 2 – Client and Edge Stage  <a name = "col_cli"></a>

During this activity, the group configured the emulation scenario and implemented the android client and required brokers. The group published a video showing that this environment works. Also, the received comments about the documentation produced in the first step will be fixed.

#### Rubric
- **(100 points):** The group published the video and demonstrated that the environment works and is completed. The issues found in the documentation are fixed, and the comments provided by Professors are incorporated into its new version.
- **(80 points):** The group publishes the video, but the environment does not work, or it is not complete. The issues found in the documentation are fixed, and the comments provided by Professors are incorporated into its new version.
- **(50 points):** The group publishes the video, but the environment does not work, or it is not complete. The issues found in the documentation were not fixed, and the comments provided by Professors are not incorporated into its new version.
- **(0 points):** The group does not submit the video.

### 🥽 Step 3 – Cloud Stage  <a name = "col_cloud"></a>

During this activity, the group implemented the broker in the cloud, which receives all messages from the brokers existent in the emulation environment. Also, the broker integration with a SQL database and the dashboard with the required features is done. All stages are integrated. The group published a video showing that this environment works. Also, the received comments about the documentation produced in the first step will be fixed.

#### Rubric
- **(100 points):** The group published the video and demonstrated that the environment works and is completed. The issues found in the documentation are fixed, and the comments provided by Professors are incorporated into its new version.
- **(80 points):** The group publishes the video, but the environment does not work, or it is not complete. The issues found in the documentation are fixed, and the comments provided by Professors are incorporated into its new version.
- **(50 points):** The group publishes the video, but the environment does not work, or it is not complete. The issues found in the documentation were not fixed, and the comments provided by Professors are not incorporated into its new version.
- **(0 points):** The group does not submit the video.

### 🍪🎂 Step 4 – Final Presentation  <a name = "col_ppt"></a>

The final workshop is a critical activity in the GSL, where it is the opportunity for the groups to show the technical result of the cooperation. It follows the basic structure of an Academic Workshop and will happen asynchronously. The students will record a video of 30 minutes (maximum) to present the project and demonstrate the skills achieved during the cooperation. The Final Workshop is compulsory for all students, and not attending implies receiving zero points in the grade and reprobation in the GSL cooperation.
To participate in the Workshop, each group needs to make a presentation using an editor (like PowerPoint, Google Slides, Canvas, etc.) which discusses the following minimum topics:
-	**What is the problem? (until 3 minutes)**: In this part, the student needs to explain the situation the system plans to solve using external references (like news, papers, etc.). It is essential that the question related to the “why” needs to be answered. Try to motivate the audience to continue to watch your video.
-	**Technical Architecture of Solution (until 8 minutes)**: The student needs to explain the technical architecture. It is essential to identify the system’s border (what is inside and outside) and use formal language (like package, system UML diagram, or SysML). 
-	**How to configure the solution (until 1 minute)**: It is essential to cite the issues about how to compile, configure, and run your solution. Remember, one of the items required to deliver is the README in the git. The idea is to explain the setup and some tips for compiling the code.
-	**Demo of System (>=8 minutes)**: This part is essential to demonstrate all the system's functionalities.

Given the time and the group size, each student must expose to a part of the presentation. It is important to remember that all students in the group need to understand the whole project and its technologies.

A **day before the workshop**, groups need to publish the following material on the GitHub Project Site:
-	Project Source Code (GitHub) + GPL license
- Problem and Motivation
- How to compile code (README file)
- Presentation file will be used in the workshop.

Also, groups need to send a message in the Slack channel named “gsl-br-mex” with the link to the GitHub site. **Observation: the git hub site needs to be available for 30 days after the end of the cooperation.**
 

#### Rubric
| **Item** | **Maximum Grade** |
| --- | --- |
| **Speaker** |
| The group defined the problem and motivation and used external references to support them. | 5 |
| The technical architecture is presented using a formal language (like SysML or UML) and is complete. | 10 |
| The student shows how to compile and install the system. | 5 |
| The demo of the system demonstrates all the system's capabilities and shows that it fully follows the requirement proposed. | 25 |
| The student demonstrates an understanding of the project and the technologies involved. | 15 |
| **Documentation (GitHub)** |
| README is the project's documentation describing how to use the system, compile and install the solution, and how use the system. | 10 |
| The GitHub site contains the technical architecture documented using a formal language (like SysML or UML), and it is complete. | 10 |
| The system works without bugs. | 10 |
| All required files were published in GitHub. | 10 |

## 🤔🤔🤔💭💭 Reflection <a name = "reflection"></a>

The **reflection** activity is the final element, where participants could share their learning experience on the ground on the content learned about the differences and similarities found with their partners during the collaboration. It is one of the essential features of this type of collaborative exercise because it is when the students reflect on what they learned by interacting with a group of students from another country and another experience different from theirs.  

Just as you did during the Icebreaker, go to the assigned [Padlet board](https://globalclassroom.padlet.org/barretoabb/bo47oalv7yl42g9s), and create a new video sharing your thoughts about our experience considering the following: 
-	How do you think your cultural background impacts how you interact and negotiate with others?
-	Has collaborated with international peers impacted your learning experience?
-	After this experience, are there any changes in your worldview?

You don't have to answer each question individually; it would be better to just take these questions as a guide to constructing a complete reflection. 

Remember, posting a video (1-3 min max) will be great, but you can also post it as a text (there is no text limit).

Sharing your post, you are free to comment on any of your peers' contributions.

#### Rubric
- **(100 points):** You make a post with your video of 1 to 3 minutes discussing your experience and post a text complementing the video reflection.
- **(80 points):** You made a post with your video of 1 to 3 minutes discussing your experience but did not post a text complementing the video reflection. 
- **(50 points):** You make a post with a brief video (less than 1 minute).
- **(0 points):** You did not share a video.



