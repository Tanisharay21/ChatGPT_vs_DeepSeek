# ChatGPT vs DeepSeek: User Interaction & Performance Analysis

## Project Overview
This project analyzes and compares user interaction patterns across two AI assistants — **ChatGPT** and **DeepSeek** — using a simulated dataset of **10,000 AI interaction sessions**.

The goal is **not** to declare a “winner,” but to understand **how users engage with AI systems**, how perceived response quality varies across tasks, and which metrics meaningfully reflect user satisfaction.

The analysis focuses on **behavioral trends, metric validity, and decision-oriented insights**, similar to what a product or analytics team would do when evaluating AI tools.

All analysis was conducted in **Python (pandas, numpy)**.

---

## Data Source & Assumptions
- The dataset is **simulated**, designed to reflect realistic AI usage patterns  
- Values such as session duration (max 60 minutes) and response length (max 500 tokens) are capped  
- The data is suitable for **comparative trend analysis and behavioral insights**, not absolute benchmarking  
- Response quality represents **perceived / feedback-based signals**, not ground-truth accuracy  

This project emphasizes **how to think with imperfect data**, not pretending the data is perfect.

---

## Objectives
- Compare user interaction patterns across AI platforms  
- Identify which task types generate higher perceived value  
- Test common engagement assumptions (e.g., time spent = satisfaction)  
- Evaluate whether language or device impacts AI performance  
- Translate technical metrics into **clear business insights**  

---

## Key Questions Explored
- Do faster responses correlate with higher user satisfaction?  
- Are longer sessions actually more engaging?  
- How do technical vs general queries differ in user behavior?  
- Does language or device impact perceived response quality?  
- Which metrics are useful — and which are misleading?  

---

## Key Insights

### 1. Performance Signals Matter More Than Platform Familiarity
Across sessions, **perceived response quality and response speed** aligned more closely with user ratings than platform loyalty or retention.

**Insight:** Users care about outcome quality, not brand attachment.

---

### 2. AI Delivers Highest Value in Technical Workflows
Technical tasks (e.g., debugging, algorithm explanations) showed:
- Higher perceived quality scores  
- Fewer follow-up corrections  
- More focused engagement patterns  

Creative and educational tasks showed slightly lower quality scores but **stable satisfaction**, suggesting users value guidance even when responses are imperfect.

**Insight:** Corrections often reflect collaboration, not failure.

---

### 3. Corrections ≠ Errors
Sessions with higher correction counts still received strong satisfaction scores.

**Interpretation:** Users frequently refine AI outputs rather than reject them.

---

### 4. Session Duration Is a Weak Engagement Metric
Correlation between session duration and response length was close to zero.

**Implication:** Long sessions often involve reading, thinking, or iteration — not dissatisfaction.

**Takeaway:** Time-based engagement metrics are poor proxies for value.

---

### 5. Language and Device Have Minimal Impact
No meaningful performance advantage was observed across:
- English, German, French, Spanish, Chinese  
- Desktop vs mobile usage  

**Conclusion:** Query structure and task clarity matter more than language or device.

---

## What This Project Demonstrates
- Critical evaluation of common analytics metrics  
- Comfort working with imperfect / simulated data  
- Feature engineering driven by business questions  
- Translation of technical results into product-relevant insights  
- Responsible, limitation-aware analysis  

---

## Tools & Techniques Used
- Python (pandas, numpy)  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Correlation & behavioral analysis  
- Business-oriented insight framing  

---

## Limitations
- Dataset is simulated and capped  
- Response quality reflects perceived feedback, not objective correctness  
- Technical query data is not uniformly distributed across platforms  
- Findings indicate **trends**, not definitive rankings  

These limitations are acknowledged intentionally to maintain analytical integrity.

---

## Summary
This project focuses on **decision-focused analytics** — understanding not just *what* users do with AI, but *how* engagement metrics can mislead if interpreted naively.

Rather than ranking AI systems, the analysis demonstrates how product teams can **evaluate AI usage responsibly**, challenge assumptions, and focus on meaningful signals of user value.
