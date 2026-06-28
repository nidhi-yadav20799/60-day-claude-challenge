# Day 5 – Context Engineering

## Objective

Learn how providing context to Claude improves the quality, relevance, and personalization of AI-generated responses.

---

# Prompt A – Without Context

## Prompt

```text
Create a 30-day learning roadmap.

Include:
- Weekly milestones
- Daily tasks
- Resources
- Projects
- Final outcome

Make it practical and beginner-friendly.
```

## Observation

* Claude generated a generic 30-day Data Science roadmap.
* The roadmap started with Python basics and introductory concepts.
* It was useful for beginners but did not consider my existing knowledge or career goals.

### Screenshots

* prompt_a_output_1.png
* prompt_a_output_2.png
* prompt_a_output_3.png
* prompt_a_output_4.png

---

# Prompt B – With Context

## Prompt

```text
Create a 30-day learning roadmap.

Context:
- Current Situation: Data Science Graduate currently doing a Data Science Internship
- Current Skills: Python, SQL, Pandas, NumPy, Machine Learning, Data Analysis, Power BI, Tableau, Git, GitHub, Streamlit
- Goal: Become an Entry-Level Data Scientist and build a strong portfolio with real-world Machine Learning projects
- Available Time: 4 Hours per Day
- Experience Level: Intermediate
- Preferred Learning Style: Project-Based Learning

Include:
- Weekly milestones
- Daily tasks
- Resources
- Projects
- Final outcome

Make it practical and beginner-friendly.
```

## Observation

* Claude created a personalized roadmap based on my current skills.
* Beginner topics were skipped, and the focus shifted to advanced Machine Learning concepts.
* The roadmap included portfolio projects, Streamlit deployment, GitHub improvements, and real-world applications.
* The recommendations aligned with my career goal of becoming a Data Scientist.

### Screenshots

* prompt_b_output_1.png
* prompt_b_output_2.png
* prompt_b_output_3.png

---

# Comparison

| Prompt A (Without Context) | Prompt B (With Context)                   |
| -------------------------- | ----------------------------------------- |
| Generic roadmap            | Personalized roadmap                      |
| Beginner-focused           | Tailored to my experience                 |
| Covers basic Python topics | Focuses on ML projects and deployment     |
| Same plan for most users   | Designed specifically for my career goals |

---

# Questions

### 1. Which roadmap feels more personalized?

Prompt B provides a personalized learning roadmap because it considers my current skills, available study time, and career objective.

### 2. Which roadmap would I actually follow?

I would follow Prompt B because it matches my current level and helps me build projects relevant to Data Science job roles.

### 3. What role did context play?

Providing context allowed Claude to generate recommendations based on my background instead of giving a generic beginner roadmap. The output became more relevant, practical, and career-focused.

---

# Key Learnings

* Context Engineering significantly improves AI responses.
* The more relevant information provided, the better the output.
* Personalized prompts reduce unnecessary information.
* AI can generate learning plans tailored to specific goals and experience levels.
* Context leads to more actionable and efficient recommendations.

---

# Files

* prompt_a_output_1.png
* prompt_a_output_2.png
* prompt_a_output_3.png
* prompt_a_output_4.png
* prompt_b_output_1.png
* prompt_b_output_2.png
* prompt_b_output_3.png

