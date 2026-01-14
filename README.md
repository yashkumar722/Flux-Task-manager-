# Flux-Task-manager-
Tired of endless to-do lists that don't tell you where to start? This tool uses AI to prioritize your tasks based on what you're actually trying to accomplish, then taps into LLM to give you the resources and help you need. Your personal assistant. Peace'
## 🧠 How the AI Works
The system uses **Google Gemini Flash** to parse natural language and assign scores based on:
- **Priority ($W=0.6$):** Extracted importance of the task.
- **Urgency ($W=0.4$):** Proximity to the deadline.
- **Adaptive Learning:** Penalizes tasks that are frequently skipped to suggest better timing.

## 🛠️ Tech Stack
- **AI:** Google Gemini API
- **Language:** Python (Google Colab)
- **Data:** Pandas & Matplotlib
