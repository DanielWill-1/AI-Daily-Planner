# AI Daily Planner

The AI Daily Planner is a Python-based CLI tool that uses a lightweight pretrained language model (DistilGPT-2) to generate intelligent, time-aware daily schedules based on user-inputted tasks and available time ranges. If the model output is unreliable, a deterministic fallback algorithm ensures a valid schedule is always produced.

---
# Features

Accepts task input with or without specified durations.

Uses heuristic-based inference for task durations.

Generates human-like schedules using DistilGPT-2.

Includes fallback logic for structured, deterministic planning.

Detects and adjusts for time constraints.

Console-based interface for quick usage.
---
# tech stack

Language: Python 3

Libraries:

transformers: for using the DistilGPT-2 model

datetime: for time-based calculations

re: for parsing and validation

Model: distilgpt2 (lightweight GPT-2 variant) from HuggingFace
---
# example
![image](https://github.com/user-attachments/assets/0d33d6a7-1a5d-41fa-92fb-71e2c8633ed7)

---
# future improvement

Add GUI/Web UI using Streamlit or Flask

User preferences for priority and breaks

Time zone and calendar integration

Persistent storage (e.g., SQLite, Firebase)

---
# How to use
```bash
pip install transformers
python app.py
```

---
