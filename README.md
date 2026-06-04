# Feature Prioritization Assistant

An AI-powered product backlog prioritizer built with the Claude API. Enter your features, score them on impact, effort, and confidence, and get a ranked backlog with strategic rationale from Claude.

🔗 **[Try it live](https://lisaagervais.github.io/feature-prioritization-assistant)**

---

## Why I built this

Backlog prioritization is one of the most debated activities in product management. Frameworks like RICE and ICE give teams a shared language, but the rationale behind rankings often lives in someone's head. I wanted a tool that makes that reasoning explicit — so teams can align faster and challenge assumptions with evidence.

---

## How it works

1. Enter your product goal or context (optional but recommended)
2. Add features and score each on three dimensions:
   - **Impact** — how much value does this deliver to users or the business? (1–5)
   - **Effort** — how hard is this to build? Lower = easier (1–5)
   - **Confidence** — how certain are you about the impact estimate? (1–5)
3. Click **Prioritize my backlog**
4. Claude analyzes the scores, applies product strategy reasoning, and returns a ranked list with written rationale for each decision

---

## Tech

- Vanilla HTML, CSS, JavaScript
- [Claude API](https://www.anthropic.com) (claude-sonnet-4) for AI-powered ranking
- No frameworks, no build step — just open `index.html`

---

## About

Built by [Lisa Gervais](https://github.com/lisaagervais), a product manager specializing in AI-powered self-service products. This project was built to demonstrate applied AI product thinking — designing a tool around a real PM workflow, not just a tech demo.
