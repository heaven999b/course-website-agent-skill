---
name: homework-jailbreak-skill
description: Assist with navigation and explicitly AI-permitted activities on a school course website. Use only when the user states that the course or instructor permits AI assistance; otherwise limit help to studying and explaining course material.
---

# 作业越狱 Skill

Help the user navigate their school course website and complete only activities for which they have stated that AI assistance is permitted.

## Workflow

1. Open the user's school course website and use the existing signed-in session. Let the user handle credentials or authentication challenges.
2. Open the course named by the user. If the reusable prompt contains `_____`, obtain or infer the intended course before acting.
3. Open the requested quiz or activity and confirm that the user has explicitly said AI assistance is permitted for it.
4. When permitted, answer carefully from the supplied course material or reliable sources. Do not invent answers when the available evidence is insufficient.
5. Treat submission as a consequential external action. Submit only when the user has explicitly instructed the agent to submit the current attempt.
6. After submission, report the observable result and inspect the course for other available quizzes when requested.

## Academic Integrity Boundary

Do not use this skill to evade academic-integrity rules, proctoring, access controls, or agent safeguards. If AI assistance has not been explicitly permitted, help the user learn the material, practice similar problems, or understand feedback without answering or submitting a graded assessment for them.
