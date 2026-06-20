# AI Engineering with Peeush

Hands-on code for the **[AI Engineering with Peeush](https://www.youtube.com/@AIEngineeringWithPeeush)** YouTube channel.

Every video in this channel comes with a companion repo — real, runnable Python code you can clone and adapt for your own projects. No toy examples. No hand-waving. Just the code.

---

## Who this is for

- **ML Engineers** debugging models and pipelines in production
- **Data Scientists** moving from notebooks to production systems
- **Backend Engineers** building or maintaining ML-adjacent infrastructure

If you've ever had a model silently fail in production and spent hours figuring out why — this channel is for you.

---

## Content

### 🔴 Series: Debugging ML in Production

A deep-dive into the most common ways ML pipelines fail silently in production — and how to fix them with clean, testable Python.

| # | Title | Type | Status | Code |
|---|-------|------|--------|------|
| 1 | [I Spent 3 Months Debugging a "Working" ML Model — Here's What I Found (Part 1)](https://youtu.be/GsxQQvXGzDs) | Theory | 🟢 Live | — |
| 2 | [I Spent 3 Months Debugging a "Working" ML Model — Here's What I Found (Part 2)](https://youtu.be/j_IjpiZE_4k) | Theory | 🟢 Live | — |
| 3 | [How to Build a Data Freshness Validation Layer in Python — Silent Data Source Failure Fix (Part 3)](https://youtu.be/xW1xgx28D_w) | Hands-On | 🟢 Live | [Data Freshness Validator](https://github.com/ai-engineering-with-peeush/yt-03-data-freshness-validator) |
| 4 | [You Can't Debug What You Can't See — Adding Step-Level Observability to Your ML Pipeline (Part 4)](https://youtu.be/0-SEzeCT9qE) | Hands-On | 🟢 Live | [Step-Level Observability for ML Pipelines](https://github.com/ai-engineering-with-peeush/yt-04-step-level-observability) |

> **How the series works:** Part 1 and Part 2 cover the theory — the 5 failure modes, why they happen, and what the fix looks like. Part 3 covers hands-On code video to implement Data Freshness Validator Layer in Python! Part 4 covers hands-On code video to implement step-level observability for ML pipelines.

---

## How to use these repos

Each video repo is self-contained. Clone the one you need:

```bash
git clone https://github.com/ai-engineering-with-peeush/yt-03-data-freshness-validator
```

Every repo follows the same structure:

```
src/
  ├── <module>.py          # The code built in the video
  ├── adapters.py          # Real-world adapter examples
  ├── examples/            # End-to-end demo
  └── tests/               # Full test suite
```

---

## Connect

- 📺 [YouTube](https://www.youtube.com/@AIEngineeringWithPeeush)
- 💼 [LinkedIn](https://www.linkedin.com/in/peeushagarwal/)
