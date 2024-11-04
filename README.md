


### **Product Backlog**

The **Product Backlog** is a prioritized list of tasks or features (user stories) that need to be completed for the system to be functional. Each user story is ranked by its priority and estimated effort, defined as "story points."

---

| **ID** | **User Story**                                                                                   | **Priority** | **Story Points** |
|--------|--------------------------------------------------------------------------------------------------|--------------|------------------|
| **US1** | As a student, I want to register and create an account so that I can log in to the system.         | High         | 5                |
| **US2** | As a student, I want to fill in my personal and educational details in the application form.       | High         | 8                |
| **US3** | As a student, I want to upload my certificates (e.g., marksheets, ID proof) for verification.      | High         | 8                |
| **US4** | As an admin, I want to view submitted applications so that I can review them.                      | High         | 7                |
| **US5** | As an admin, I want to approve or reject applications based on the eligibility criteria.           | Medium       | 6                |
| **US6** | As an admin, I want to provide a reason for rejection so that students can correct their mistakes.  | Medium       | 5                |
| **US7** | As a student, I want to receive a notification about the approval or rejection of my application.   | Medium       | 6                |
| **US8** | As a student, I want to edit and resubmit my application if it gets rejected.                      | Medium       | 5                |
| **US9** | As an admin, I want to view a dashboard showing pending and processed applications.                | Low          | 7                |
| **US10** | As an admin, I want to filter applications based on different criteria (e.g., branch, status).     | Low          | 4                |

---

### **Explanation of Key Stories:**

1. **US1 (Account Registration)**: High-priority user story as it's the starting point for every student. Without this, no one can access the system.
2. **US2 (Application Form)**: Critical for the core functionality, allowing students to apply by entering their personal and educational information.
3. **US4 (Admin Application Review)**: Admin's ability to review applications is central to the system.
4. **US5 (Application Approval/Rejection)**: Admin must be able to accept or reject applications, forming a key part of the workflow.
5. **US8 (Resubmission)**: This adds flexibility, allowing students to resubmit after making corrections based on admin feedback.

---

This **Product Backlog** provides a clear list of the tasks to be completed, sorted by priority. Each user story is written in a way that focuses on the end-user's goals, a key part of the Scrum process.




---

### **Sprint Backlog**

The **Sprint Backlog** is a subset of the Product Backlog that the team commits to complete during a specific sprint. For this project, we will assume the sprint duration is **2 weeks**, and we'll focus on key user stories that can be implemented within that time.

---

| **Sprint** | **User Story ID** | **Task**                                                                                              | **Priority** | **Assigned To**  | **Time Estimate (Days)** |
|------------|-------------------|-------------------------------------------------------------------------------------------------------|--------------|------------------|--------------------------|
| Sprint 1   | US1                | Design user registration page with form validation                                                     | High         | [Developer 1]    | 2                        |
|            | US1                | Implement backend logic for student registration (Django user authentication)                         | High         | [Developer 2]    | 3                        |
|            | US2                | Create the application form UI (HTML/CSS)                                                             | High         | [Developer 1]    | 3                        |
|            | US2                | Implement form data handling (personal, educational details)                                           | High         | [Developer 2]    | 4                        |
| Sprint 1   | US3                | Develop document upload feature (file storage for marksheets, certificates)                           | High         | [Developer 3]    | 3                        |
|            | US3                | Validate and secure document uploads                                                                  | High         | [Developer 3]    | 2                        |
| Sprint 1   | US4                | Create admin dashboard UI to list all submitted applications                                           | Medium       | [Developer 1]    | 2                        |
|            | US4                | Implement backend logic for fetching and displaying applications for review                           | Medium       | [Developer 2]    | 3                        |

---

### **Sprint Breakdown Explanation:**

- **US1 (User Registration)**: This is essential for enabling users to access the system. Tasks include designing the registration form and implementing authentication in Django.
- **US2 (Application Form)**: The core feature of the system, requiring both UI development and backend form handling.
- **US3 (Document Upload)**: A critical feature allowing students to upload documents. It involves building the file upload feature and ensuring security through validation.
- **US4 (Admin Dashboard)**: Allows admins to view applications. It will involve designing the UI and developing the backend to list the applications.

### **Sprint Goals:**
- By the end of Sprint 1, we aim to have the student registration, application form, document upload, and a basic admin dashboard implemented.

### **Sprint Burndown Chart Example:**

| **Day** | **Estimated Work Remaining (hours)** | **Actual Work Remaining (hours)** |
|---------|--------------------------------------|-----------------------------------|
| Day 1   | 50                                   | 50                                |
| Day 2   | 45                                   | 48                                |
| Day 3   | 40                                   | 42                                |
| Day 4   | 35                                   | 40                                |
| Day 5   | 30                                   | 35                                |

---

### **Notes:**
- **Task Breakdown**: Each user story is broken down into smaller, actionable tasks that can be completed during the sprint.
- **Assigned Developers**: Tasks should be assigned to individual team members, ensuring balanced workload and timely completion.
- **Time Estimates**: Time is estimated in days, but you can also use hours depending on your team's preferences.













---

### **Agile Scrum Process Document for Online College Admission Management System**

---

### **1. Burndown Chart**

The **Burndown Chart** is used to track the progress of work in a sprint. It shows the total estimated work and how much work remains over time.

#### **Sprint Burndown Chart Example**

| **Day** | **Estimated Work Remaining (hours)** | **Actual Work Remaining (hours)** |
|---------|--------------------------------------|-----------------------------------|
| Day 1   | 50                                   | 50                                |
| Day 2   | 45                                   | 48                                |
| Day 3   | 40                                   | 42                                |
| Day 4   | 35                                   | 40                                |
| Day 5   | 30                                   | 35                                |
| Day 6   | 25                                   | 30                                |
| Day 7   | 20                                   | 25                                |
| Day 8   | 15                                   | 20                                |
| Day 9   | 10                                   | 12                                |
| Day 10  | 5                                    | 5                                 |
| Day 11  | 0                                    | 0                                 |

**Explanation**:  
- The **Estimated Work Remaining** is the expected reduction of work over time, whereas the **Actual Work Remaining** tracks the real progress made.
- The goal is to complete all tasks by the end of the sprint (Day 10-11).

---

### **2. Roles in Scrum**

#### **Product Owner**
- **Responsibilities**:
  - Defines the vision for the product (Online College Admission Management System).
  - Maintains the **Product Backlog** and prioritizes user stories based on business value and user needs.
  - Communicates requirements clearly to the Scrum team.
  - Ensures that the product delivers value to the stakeholders (e.g., students, admin users).
  - Reviews and approves the work done in each sprint during the **Sprint Review Meeting**.

#### **Scrum Master**
- **Responsibilities**:
  - Facilitates all Scrum ceremonies such as **Daily Standups, Sprint Planning, Sprint Review**, and **Sprint Retrospective**.
  - Removes impediments that hinder the team’s progress.
  - Ensures the team adheres to Scrum principles and practices.
  - Supports the team in becoming self-organizing.
  - Tracks the sprint progress using tools like the **Burndown Chart** and ensures the team stays on track.

---

### **3. Minutes of Meeting (MOM)**

---

#### **3.1 Daily Scrum Meeting MOM**  
**Date**: [21/10/24]  
**Attendees**: [Atharv ,Rajdeep ,Vishal ,Swapnil]  
**Duration**: 15 minutes  
**Facilitator**: Scrum Master

- **What was done yesterday?**
  - Developer 1 completed the registration page design.
  - Developer 2 implemented the backend for student registration.
  - Developer 3 worked on the document upload feature.

- **What will be done today?**
  - Developer 1 will start working on the application form UI.
  - Developer 2 will integrate form data handling with the backend.
  - Developer 3 will validate and secure the document uploads.

- **Are there any blockers?**
  - Developer 2 mentioned an issue with integrating the file storage for documents (blocker).
  - Scrum Master to address this issue.

**Action Items**:  
- Scrum Master to resolve the file storage issue by [insert date].

---

#### **3.2 Sprint Planning Meeting MOM**  

**Date**: [27/10/24]  
**Attendees**: [Atharv ,Rajdeep ,Vishal ,Swapnil]
**Duration**: 1 hour  
**Facilitator**: Scrum Master

**Agenda**:
1. **Review the Product Backlog**:  
   - The Product Owner reviewed the prioritized user stories for the sprint, focusing on key functionalities such as student registration, application form, and document upload.

2. **Select User Stories for the Sprint**:  
   - User Stories selected for Sprint 1:  
     - US1: Student registration and login.
     - US2: Application form with personal and educational details.
     - US3: Document upload functionality.
     - US4: Admin review dashboard.

3. **Task Breakdown and Estimation**:  
   - Tasks were broken down and assigned to team members.
   - Time estimates were given for each task (as reflected in the **Sprint Backlog**).

4. **Define Sprint Goal**:  
   - By the end of this sprint, the goal is to have a fully functional student registration system, an application form, and basic admin functionality for reviewing applications.

**Action Items**:  
- Development starts based on the tasks assigned.
- Scrum Master will monitor progress and organize daily standups.

---

#### **3.3 Sprint Review Meeting MOM**  

**Date**: [1/11/24]  
**Attendees**: [Atharv ,Rajdeep ,Vishal ,Swapnil]
**Duration**: 1 hour  
**Facilitator**: Scrum Master  
**Stakeholders**: Product Owner, College Admin, and IT Team.

**Agenda**:
1. **Demonstration of Completed Work**:
   - Developer 1 demonstrated the student registration flow.
   - Developer 2 presented the application form with document upload.
   - Developer 3 showed the admin’s ability to view applications.

2. **Feedback from Product Owner and Stakeholders**:
   - Product Owner was satisfied with the student registration and application form features.
   - College Admin suggested adding a filtering option to the admin dashboard to sort applications by branch or status.

3. **Plan for the Next Sprint**:
   - Address feedback by adding the filtering feature for the admin dashboard.
   - Focus on the notification system for students regarding their application status.

4. **Sprint Completion**:
   - All user stories planned for the sprint were completed except the filtering option, which will be moved to the next sprint backlog.

**Action Items**:  
- Add new filtering functionality to the next sprint backlog.
- Scrum Master to plan the next Sprint Planning Meeting.

---

