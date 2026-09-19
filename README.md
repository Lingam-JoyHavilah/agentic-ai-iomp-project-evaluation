# Agentic AI – IOMP Project Evaluation

## 📌 About the Project

This project is an AI-powered workflow developed for **Industry Oriented Mini Project (IOMP) evaluation**.

The system automates the process of collecting student project evaluation details, storing review scores, calculating results, and generating an AI-based evaluation report.

## 🚀 Technologies Used

- n8n
- Supabase
- OpenAI
- JavaScript
- JSON

## ⚙️ How It Works

1. Collects student and project details through an evaluation form.
2. Retrieves the required evaluation criteria.
3. Collects scores for the project review.
4. Stores student, team, review, and score information in Supabase.
5. Calculates review marks and percentages.
6. Processes Review 1 and Review 2 results.
7. Calculates the cumulative result.
8. Uses an OpenAI-powered AI Agent to generate an evaluation report.
9. Stores the generated AI report in Supabase.
10. Sends the evaluation report through email.

## 🤖 AI Evaluation

The AI Agent generates the evaluation report based on the submitted scores and remarks.

### Score Interpretation

| Score | Meaning |
|------:|---------|
| 4 | Very Good |
| 3 | Good |
| 2 | Satisfactory |
| 1 | Needs Improvement |

The AI report is generated using the available evaluation data without adding unsupported information.

## 🗄️ Database

Supabase is used to store the project evaluation data.

Main tables used in the workflow include:

- `evaluation_criteria`
- `project_teams`
- `students`
- `project_reviews`
- `review_scores`
- `team_members`
- `ai_evaluation_reports`

## 🎯 Purpose

The main purpose of this project is to explore how **Agentic AI and workflow automation** can be used to automate an academic project evaluation process.

## 📚 Learning Outcomes

Through this project, I gained practical exposure to:

- Agentic AI workflows
- n8n automation
- Supabase database integration
- OpenAI integration
- Automated result calculation
- AI-based report generation
- Connecting multiple services into a single workflow
