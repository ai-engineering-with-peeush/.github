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

### 🔵 Series: Anomaly & Behavioral Detection in Production

Unsupervised detection of behavioral anomalies in production — no labels, no predefined rules. From raw logs to a scoring API, with an honest evaluation against injected attacks.

| # | Title | Type | Status | Code |
|---|-------|------|--------|------|
| 5 | [Build a Login Anomaly Detector in Python — No Labels, No Rules (End-to-End)](https://youtu.be/h3JQGq-ZA_I) | Hands-On | 🟡 Scheduled (Jun 25) | [Login Anomaly Detector](https://github.com/ai-engineering-with-peeush/yt-05-login-anomaly-detector) |

---

### 🔴 Series: Debugging ML in Production

A deep-dive into the most common ways ML pipelines fail silently in production — and how to fix them with clean, testable Python.

| # | Title | Type | Status | Code |
|---|-------|------|--------|------|
| 4 | [You Can't Debug What You Can't See — Adding Step-Level Observability to Your ML Pipeline](https://youtu.be/0-SEzeCT9qE) | Hands-On | 🟢 Live | [Step-Level Observability](https://github.com/ai-engineering-with-peeush/yt-04-step-level-observability) |
| 3 | [How to Build a Data Freshness Validation Layer in Python — Silent Data Source Failure Fix](https://youtu.be/xW1xgx28D_w) | Hands-On | 🟢 Live | [Data Freshness Validator](https://github.com/ai-engineering-with-peeush/yt-03-data-freshness-validator) |
| 2 | [I Spent 3 Months Debugging a "Working" ML Model — Here's What I Found (Part 2)](https://youtu.be/j_IjpiZE_4k) | Theory | 🟢 Live | — |
| 1 | [I Spent 3 Months Debugging a "Working" ML Model — Here's What I Found (Part 1)](https://youtu.be/GsxQQvXGzDs) | Theory | 🟢 Live | — |

> **How the series works:** Parts 1 & 2 cover the theory — the 5 failure modes, why they happen, and what the fix looks like. Parts 3 & 4 are hands-on implementations fixing two of those failure modes in clean, testable Python.

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
