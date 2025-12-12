Hi there 👋

# Aspiring Full-Stack Developer & Project Lead 🚀

### About Me

I am a passionate aspiring **Full-Stack Developer** currently mastering modern web technologies at **Langara College**.

My background includes **15 years of construction project management**, where I built a robust foundation in delivering complex projects—particularly large-scale **data centers**—from conception to completion. This experience has honed my abilities in:
* **Project Oversight:** Managing complex timelines and scope.
* **Global Team Collaboration:** Successfully leading diverse, multinational teams in Japan and Singapore.

My enthusiasm for **problem-solving** fueled my pivot to software engineering. I am deeply focused on developing with **JavaScript, React, and Node.js**, and I aim to leverage my seasoned project management and team collaboration skills to architect and deliver innovative software solutions.

Let's connect and build something impactful! Connect with me on [LinkedIn](https://www.linkedin.com/in/ryo-ito46/)!

---

### 🛠️ Tech Stack

![](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![](https://img.shields.io/badge/-Expo-1B1F23?style=flat-square&logo=expo&logoColor=white) ![](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=black) ![](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white) ![](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white) ![](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white) ![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 🚀 Featured Projects

### 💊 Project: Dosis [MedTech](https://dosis-wmdd.netlify.app/)

<details>
<summary><strong>View Details (Medication Management App)</strong></summary>

**Concept:** Dosis is a mobile application designed to seamlessly integrate medication taking into the user's daily life, minimizing cognitive load and effort.

* **Key Features:**
    * One-step schedule registration based on user rhythm and medication requirements.
    * Comprehensive Push Notifications (including refill timing).
    * Interaction Blocker during medication addition for focused registration.

#### 🛠️ Technology Used

| Category | Technologies |
| :--- | :--- |
| **Front/Mobile** | **ReactNative (Expo)** |
| **Back-end** | **Node.js, Express** |
| **Auxiliary** | **Python** (for OCR assistance) |
| **Database** | **MongoDB** (integrated with Agenda for scheduling) |

#### 👤 My Responsibilities (Core Focus)
**Role: Primary Contributor / Core Implementer**

* **Architectural Design:** Designing the core logic for medication registration, schedule generation, and notification features.
* **Data Modeling:** Designing the database schema and data modeling strategy.
* **Implementation:** Implementing core registration features, including OCR functionality.
* **Refactoring:** Overall code refactoring and system integration.

#### 💡 Challenges & Solutions

1.  **Safety & Scalability (MedTech Perspective):**
    * **Challenge:** As a MedTech application, we were required to establish a secure and realistic specification, which was challenging due to the Canadian government's drug API availability and the diversity of potential use cases.
    * **Solution:** Developed a realistic, long-term development plan. Architected the data source to allow seamless switching from the self-maintained DB to an external DB, and eventually to an API, without major core logic rework. We adopted a policy to prevent unnecessary feature bloat by ensuring that use cases would be expanded in phases as the database became richer.

2.  **Usability vs. Flexibility (PM Perspective):**
    * **Challenge:** Balancing the attractiveness of flexible feature expansion against the risk of creating overly complex settings, which would increase the learning curve and decrease manageability for users.
    * **Solution:** Prioritized releasing a basic set of features first to validate the app's core concept and philosophy against market needs before introducing complex, optional flexibility.

3.  **Technical Constraint (Expo Limitation):**
    * **Challenge:** Facing the limitations of Expo's Native functionality for advanced mobile features during later development phases.
    * **Solution:** Conducted a comprehensive **feature feasibility study** and formulated a **detailed migration plan** (e.g., transitioning to Expo Bare Workflow or full React Native CLI) to proactively manage technical debt and ensure future scalability.

</details>

---

### 📚 Project: Cubie [EduTech](https://cubie-learning.wmdd.ca/)

<details>
<summary><strong>View Details (Unified Educational Platform)</strong></summary>

**Concept:** Cubie is a unified platform designed to streamline collaboration between **Teachers, Students, and Parents**, addressing the inefficiencies caused by the complexity of existing educational systems.

* **Key Features:**
    * **Teachers:** Centralized format for material sharing, assignment management, and grade evaluation.
    * **Students:** Easy access to materials, submission/grade check, AI-powered self-study, and collaboration chat.
    * **Parents:** Grade tracking and school notification reception.

#### 🛠️ Technology Used

| Category | Technologies |
| :--- | :--- |
| **Front-end** | **React, Recharts** (for data visualization) |
| **Back-end** | **Node.js, Express, Socket.io** (for real-time features) |
| **Database/AI** | **MongoDB, Gemini** |
| **Cloud** | **AWS** |

#### 👤 My Responsibilities (Core Focus)
**Role: Lead Developer** (Full Stack)

* **Project Foundation:** Setting up the development environment, creating the boilerplate structure, and establishing the base data modeling.
* **Core Implementation:** Implementing the core logic for material and assignment exchange between students and teachers.

#### 💡 Challenges & Solutions

1.  **Technology Adoption & Efficiency:**
    * **Challenge:** The project required **React development**, which was new to the entire team.
    * **Solution:** Leveraging the team's strong affinity for JavaScript, we strategically chose the **MERN stack**. By personally handling the environment setup and boilerplate implementation, I ensured the team could immediately focus on core feature implementation, **maximizing the project period**.

2.  **Complex Multi-Role UX:**
    * **Challenge:** Creating intuitive and distinct user experiences (UX) for the complex assignment workflow between Students and Teachers, while ensuring technical feasibility.
    * **Solution:** Achieved the goal by engaging in **repeated technical feasibility reviews** and **close collaboration with the designer**, successfully implementing the necessary unique user interfaces.

</details>

---

### 🫂 Project: Impacto (Event & Petition App) [SocialTech]
**Project Demo Video:** [Watch the Dosis Project Demo on Google Drive](https://drive.google.com/file/d/1C_cStFj7zrxBO-hYCvoZD636t8wBsM7k/view?usp=sharing)

<details>
<summary><strong>View Details (Community Engagement Tool)</strong></summary>

**Concept:** The platform was developed to solve the two main challenges in community organizing: the **psychological barrier to starting activities** and the **difficulty of gaining supporter consensus (Petition)**. Impacto simplifies the event and petition processes, and amplifies the activity's momentum through real-time participant statistics and live chat.

#### Core Features

* Streamlined **Event and Petition registration** functionality.
* Effective **viewing forms** for registered activities.
* **Real-time participant statistics** display.
* **Live Chat** functionality for activity promotion.

#### 🛠️ Technology Used

| Category | Technologies |
| :--- | :--- |
| **Front-end** | **Pure JavaScript (Vanilla JS)**, HTML, CSS, **PWA** |
| **Back-end/BaaS** | **Firebase** (Authentication, Firestore/RTDB) |
| **Cloud/Infrastructure** | **Firebase Hosting** (Assumed) |

#### 👤 My Responsibilities (Core Focus)
**Role: Primary Contributor / Core Implementer**

* **Live Chat Implementation:** Designed and implemented the Live Chat feature, including image/video posting and organizer deletion functionality.
* **Persistent UX:** Implemented the chat as a **floating window** to ensure the chat content remained visible during page transitions.
* **Foundational Leadership:** Led Firebase environment setup and the implementation of **PWA features** (offline settings, manifest) utilizing **Service Worker**.

#### 💡 Challenges & Solutions

1.  **Complex State Management (Pure JS):**
    * **Challenge:** In a **framework-agnostic** environment, implementing complex **State Management** was required to handle chat state persistence and seamless UX during page transitions and event start-up.
    * **Solution:** Designed a **custom global State Management pattern** utilizing **Local Storage and Session Storage** to achieve seamless UX without reliance on a major framework.

2.  **Robust PWA Foundation & Security:**
    * **Challenge:** Ensuring offline functionality and security across multiple developers while establishing PWA standards.
    * **Solution:** Led the definition and modification of **Firebase Security Rules** and the implementation of the **offline caching strategy using Service Worker** to establish a robust and modern foundation.

</details>

---
