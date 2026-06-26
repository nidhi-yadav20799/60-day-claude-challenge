# Day 3 – Role-Based Prompting

## Objective

Learn how assigning different roles to Claude changes the quality, depth, and relevance of AI responses.

---

# Experiment 1 – Without Role Prompt

## Prompt

```
How can I improve my resume to get an entry-level Data Scientist role?
```

## Observation

* The response was helpful but generic.
* Suggestions focused on resume structure and common best practices.
* Less personalized and less industry-specific.

---

# Experiment 2 – Founder Persona

## Prompt

```
You are the founder of a fast-growing AI startup that hires Data Scientists.

Review my resume strategy and tell me what would make me stand out for an entry-level Data Scientist role.

I am a Data Science graduate currently doing a Data Science internship. I want practical advice that recruiters and startup founders actually look for. Prioritize high-impact improvements.
```

## Observation

* The advice became more practical and business-focused.
* Suggested stronger project impact, measurable achievements, and recruiter expectations.
* Explained what startup founders actually value in candidates.

---

# Experiment 3 – Developer / Senior Data Scientist Persona

## Prompt

```
You are a Senior Data Scientist and Machine Learning Engineer with 10+ years of industry experience.

Review my resume strategy and explain how I can improve it to get an entry-level Data Scientist role.

Focus on technical skills, projects, GitHub, machine learning, Python, SQL, deployment, and ATS optimization. Give practical recommendations.
```

## Observation

* The response was highly technical.
* Recommended improving GitHub projects, ATS keywords, deployment skills, SQL, Python, and machine learning portfolio.
* Provided actionable industry recommendations.

---

# Comparison

| Without Role      | Founder Role               | Senior Data Scientist Role          |
| ----------------- | -------------------------- | ----------------------------------- |
| Generic advice    | Business-focused advice    | Technical and industry-level advice |
| Basic resume tips | Recruiter expectations     | Technical skill improvements        |
| Limited context   | Startup hiring perspective | Data Science career guidance        |

---

# Claude Usage Tracker

## Completed

* Installed Claude Usage Tracker Chrome Extension.
* Explored the interface.
* Observed session usage, remaining messages, and reset timer.

Screenshot:

* claude_usage_tracker.png

---

# Key Learnings

* Role-Based Prompting significantly improves AI responses.
* Assigning a role provides better context and expertise.
* Different personas generate different perspectives for the same question.
* Founder persona focuses on business impact.
* Senior Data Scientist persona focuses on technical growth.
* Better prompts produce more relevant and actionable answers.

---

# Files

* role_based_prompting_linkedin_v2.png
* without_role_output_1.png
* without_role_output_2.png
* without_role_output_3.png
* founder_role_output_1.png
* founder_role_output_2.png
* founder_role_output_3.png
* founder_role_output_4.png
* developer_role_output_1.png
* developer_role_output_2.png
* developer_role_output_3.png
* claude_usage_tracker.png

---

## Conclusion

Role-Based Prompting helps generate more accurate, context-aware, and specialized AI responses. By assigning different expert personas, Claude adapts its reasoning, tone, and recommendations based on the role, making the output more useful for specific tasks.


