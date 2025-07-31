# Prompt Engineering Using Large Language Models

This project explores the effectiveness and factual accuracy of using a Large Language Model (LLM), like ChatGPT, to analyze structured sports statistics. Specifically, it evaluates how well ChatGPT can answer questions based on the **2024–2025 Syracuse University Men’s Basketball** team.

## 📊 Dataset

The dataset includes detailed performance statistics for each Syracuse player and team-wide metrics, including:
- Game outcomes (win/loss records)
- Scoring averages
- Shooting percentages
- Turnovers, steals, and blocks
- Attendance metrics
- Performance splits: home vs away, conference vs non-conference

The dataset is provided in PDF format.

## 🤖 Objective

The main goal was to:
- Feed the statistics to ChatGPT
- Ask structured natural language questions
- Measure how accurately the model interprets and responds based on the data

## 🧠 Prompt Sample Topics

The prompt file (`Prompts.pdf`) includes questions like:
- Who was the top scorer?
- Which player had the best defensive stats?
- Who should be targeted or trained more based on weaknesses?
- How did the team perform in home vs. away games?
- Strategic suggestions if playing against Syracuse

ChatGPT’s answers were analyzed for factual correctness and reasoning based on the dataset.

## 📌 Key Takeaways

- ChatGPT correctly extracted numerical stats (e.g., points per game, rebound totals).
- It was able to synthesize insights like player weaknesses, home crowd impact, and game strategies.
- Minor discrepancies occurred in derived metrics or subjective reasoning, highlighting areas for improvement in LLM fact grounding.

## 📁 Files

- Full season statistical report of Syracuse Men's Basketball 2024–25 available at [Link](https://cuse.com/sports/mens-basketball/stats/2024-25)
- `Prompts.pdf` — Prompt questions and ChatGPT responses


