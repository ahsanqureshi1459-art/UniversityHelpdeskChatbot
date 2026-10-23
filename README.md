# University Helpdesk Chatbot Using Python

## Project Overview
The University Helpdesk Chatbot is a Python-based application designed to help students get answers to common university questions.

The chatbot provides predefined answers about admissions, examinations, fees, scholarships, student ID cards, and university departments.

## Features
- Answers common university questions.
- Matches user questions with stored questions.
- Displays a fallback message when it cannot understand a question.
- Stores questions and answers in a JSON file.
- Runs locally on a computer.

## Technologies Used
- **Python:** Used to develop the chatbot.
- **JSON:** Used to store questions and answers.
- **difflib:** Used in the similarity-matching version to compare text.

## Project Files
- `main.py` — Original chatbot program.
- `nlp_chatbot.py` — Text similarity-based chatbot program.
- `data.json` — Contains predefined questions and answers.

## How to Run
1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in a terminal.
4. Run the following command:

```bash
python nlp_chatbot.py
```

5. Type a question in English.
6. Type `exit` to close the chatbot.

## Current Limitations
- The chatbot answers questions using predefined information.
- It may not understand questions phrased in an unfamiliar way.
- The information available depends on the questions and answers stored in `data.json`.

## Project Status
This project is a student FYP prototype and may be improved based on testing and supervisor feedback.
