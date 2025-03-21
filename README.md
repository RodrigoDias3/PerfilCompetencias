# **Skills Profile**

For privacy reasons and because the project is still under development, I won't be able to post the application code, but I will try to demonstrate the work done so far and the next steps in the project.

## 📌 **About the project**

Skills Profile is an application developed in Kotlin using Spring Boot, with a MySQL database. The system is intended for Universidade Lusófona and its main objective is to facilitate the collection and analysis of student and employee competencies, using forms and Natural Language Processing (NLP) techniques.

## 🎯 **Motivation**

The need for the project arose from a real problem identified by the University's Human Resources (HR) Department. Currently, the collection and analysis of competencies are time-consuming processes and depend on manual interpretations, making it difficult to gain insights into the progress of students and employees. This application proposes to automate this process, providing a practical and efficient tool for data analysis.

## **🔧 Features**
The application has three modes of use:

- **Student** mode:
  - Filling in forms with multiple choice questions.
  - Viewing progress.
  
    <img height="900px" alt="" src="https://github.com/user-attachments/assets/7c6ec8cd-69bc-4925-9020-46db76a038dd"/>
    <img height="900px" alt="" src="https://github.com/user-attachments/assets/7bb8f47d-a5db-49ca-8fee-d3184a70d83c"/>


- **Teacher** mode (middle management):
  - Filling in forms with open answers.
  - Use of NLP to analyze responses.

- **Human Resources** (HR) mode:
  - Visualization of average results for students and employees.
  - Data export for future analysis.

## 🏗️ **Architecture**

The application follows an architecture based on `Spring Boot`, being responsible for processing `HTTP` requests and generating dynamic HTML pages through `Thymeleaf`. The structure includes:

![image](https://github.com/user-attachments/assets/31a2c593-f0bb-4074-bd66-c980e5421799)

- **Backend**: Developed in `Kotlin` with `Spring Boot`.
- **Database**: `MySQL` for data storage and management.
- **Frontend**: `HTML`, `Bootstrap` and `Chart.js` for data visualization.
- **Artificial Intelligence**: `OLLAMA` for skills analysis.

## 🏆 **Conclusion**
The Skills Profile presents itself as an innovative solution for Lusófona University, optimizing the collection and analysis of skills. The use of NLP and interactive visualizations makes the process more efficient and accessible to students, employees and the HR team.

## This project was developed by:
- Rodrigo Dias - a22205897
- Miguel Melo - a21905215
