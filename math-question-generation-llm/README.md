Math Question Generation using LLM
📌 Project Overview
This project demonstrates the use of Large Language Models (LLMs) to generate professional, exam-ready math questions based on a given curriculum and reference (base) questions.

The final deliverable includes:

Two new math questions similar in type and difficulty to the provided base questions.

Clean LaTeX equations.

Professionally styled diagrams generated from AI image tools using LLM-generated image descriptions.

A Word document containing both questions in the required @title … @plusmarks format.

🛠 Workflow
Step 1 – LLM Question Generation
The two base questions were provided in the recruiter’s document.

I fed these base questions into Cursor AI with a structured prompt to:

Generate two new but similar questions.

Follow the exact Question Output Format from the problem statement.

Include LaTeX formulas where relevant.

Suggest detailed image descriptions.

Step 2 – Image Creation
The LLM output included clear image descriptions.

These descriptions were used in DALL·E to generate professional, textbook-style diagrams:

Question 1: Academic-style table showing categories for combinations.

Question 2: Technical drawing of a geometric shape with dimensions.

Step 3 – Document Formatting
The final Word document contains:

All question text in the given format.

Images placed beside each question for clarity.

Consistent fonts, spacing, and layout as in the base document.

Images were compressed to keep the file size small.

📂 Repository Structure
javascript
Copy
Edit
math-question-generation-llm/
│
├── Math_Question_Generation_Compressed.docx
├── README.pdf / README.docx
├── prompts.txt
└── images/
    ├── q1_combination_table.png
    ├── q2_cylinder_volume.png
📈 Skills Demonstrated
LLM Prompt Engineering – Designed prompts to produce precise question formats and content.

AI Image Generation – Translated LLM image descriptions into DALL·E diagrams.

Document Design – Created a professional, recruiter-ready .docx in the given format.

Version Control – Organized deliverables in GitHub for easy access.