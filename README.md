# Cloud-Based-Virtual-Healthcare-Assistant

**Project Title:** Virtual Healthcare Assistant: A Chatbot Integrated with AWS for Medical Information Retrieval

**Introduction:**

This project responds to the increasing demand for innovative solutions bridging the gap between patients and healthcare services. The Virtual Healthcare Assistant is designed to be adaptable and user-centric, leveraging the capabilities of Amazon Web Services (AWS) to ensure efficiency, scalability, and secure data management.

**Key Objectives:**

1. Efficiency and Scalability: Utilizing AWS to enhance the efficiency and scalability of the Virtual Healthcare Assistant.

2. User-Centric Approach: Designing the assistant to be adaptable and user-centric, focusing on patient engagement and healthcare service extension to remote or inaccessible locations.

3. Medical Information Retrieval: Addressing challenges such as medical appointment scheduling, health information retrieval, and feedback mechanisms.

**Significance of AWS Integration:**
The primary focus is on creating a robust and scalable chatbot system that seamlessly integrates with healthcare operations. AWS technologies play a crucial role in the development of an intelligent and responsive healthcare chatbot.

**Project Overview:**

__Patient Engagement:__ Redefining patient engagement through innovative solutions.

**Structure of the Project:**
The subsequent sections will delve deeper into methodologies, experiments from both patients' and doctors' perspectives, and technological choices. The discussion will highlight the significance of AWS integration in achieving the project's goals.

**Instructions:**
1. Download the code file from code -> Login_Page.html and Open the Login Page.
2. Enter the Username and Password for chatbots
    Username and password for patient bot - patient1 and password1
    Username and password for doctor bot  - doctor1 and password2
3. After logging in, chatbot appears respectively for patient and doctor logins in kommunicate application.
  **Patient Interface**:
   - Give first question as Hi or Id.
   - Select appointment, reschedule or cancel the appointment
   - Give the date and time for appointment and the appointment is confirmed
   - The same will be updated in dynamo DB
  **Doctor Interface**:
   - Type Id of patients as '01', '123', '6' etc
   - Give values as "Blood Pressure" or "Heart rate"
   - It will display the patient details stored in dynamo db.
4. Same way can test for all scenarios.
5. After sometime, session will logout automatically.
     
