EAgent — AI English Exam Practice Agent

EAgent is a lightweight AI-powered tutoring agent designed to help high school students practice English exams efficiently every day.

It simulates a personal AI tutor capable of generating practice tests, grading answers, analyzing mistakes, and providing explanations using structured tool-calling.

The project demonstrates how AI agents can assist in education through multi-step reasoning and tool integration.

Live Demo:
https://e-agent-iota.vercel.app/

GitHub Repository:
https://github.com/TSA-29/EAgent

Overview

EAgent is designed for students preparing for:

Vietnamese National High School Exam (THPT Quốc Gia)

IELTS basic levels (≈5.5–6.5)

Instead of passive learning, students can interact with the AI to:

Practice daily exams

Receive automated grading

Understand mistakes

Improve weak grammar areas

The agent combines AI reasoning + structured tools to simulate a real learning workflow.

Key Features
Daily English Practice Tests

The agent can automatically generate structured English practice tests based on exam patterns.

Automatic Answer Grading

Student answers are evaluated automatically using grading tools.

Mistake Analysis

The agent identifies:

grammar weaknesses

vocabulary problems

recurring mistake patterns

Detailed Explanations

For incorrect answers, the AI provides clear explanations and learning guidance.

Personalized Learning Suggestions

Based on analysis, the agent recommends next learning steps.

Multi-Step AI Reasoning

The system supports tool-calling workflows, allowing the AI to:

generate a test

evaluate answers

analyze mistakes

explain grammar

suggest improvements

This mimics the behavior of a personal AI English tutor.

Tool-Based Agent Design

By default, the agent operates with specialized tools.

These tools allow the AI to perform structured educational tasks:

generate_exam → create English practice tests

grade_answers → evaluate student responses

analyze_mistakes → detect weak grammar areas

explain_grammar → explain rules and concepts

recommend_next_tasks → suggest learning steps

This architecture demonstrates how AI agents can coordinate multiple tools to solve learning tasks.

Example Learning Workflow

Example interaction:

Student request

Give me a daily English practice test.

Agent workflow

1️⃣ Generate exam questions
2️⃣ Wait for student answers
3️⃣ Grade responses automatically
4️⃣ Analyze mistake patterns
5️⃣ Provide explanations
6️⃣ Recommend next exercises

Project Structure
EAgent/
│
├── agent.py
│   Core AI agent logic and tool-calling workflow
│
├── tools.py
│   Tools used by the agent (exam generation, grading, analysis)
│
├── ui.py
│   Chat interface for interacting with the AI tutor
│
├── requirements.txt
│   Python dependencies
│
└── README.md
Installation
Prerequisites

Python 3.8+

Install dependencies
pip install -r requirements.txt
Run Locally

Start the AI agent:

python agent.py

or run the UI:

chainlit run ui.py -w
Deployment

This project can be deployed using platforms such as:

Vercel

Render

Railway

Live deployment example:

https://e-agent-iota.vercel.app/

Example Prompts

Try asking the AI:

Generate a daily English practice test.

Grade my answers and explain my mistakes.

Which grammar topics am I weak at?

Give me exercises to improve my grammar.

Explain why question 3 is wrong.

Educational Goal

The goal of this project is to demonstrate how AI agents can support exam preparation and personalized learning.

Instead of static learning materials, students receive:

interactive practice

instant feedback

personalized improvement suggestions

Future Improvements

Potential future features:

Vocabulary tracking

IELTS speaking evaluation

Adaptive difficulty tests

Student progress analytics

Learning streak system (daily practice)
