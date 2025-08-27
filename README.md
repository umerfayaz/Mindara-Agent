Mindara Agent 🤖

Mindara is an autonomous AI assistant built with LangGraph and Flask, designed to optimize daily work by handling tasks 24/7. It’s not just a chatbot — it’s a fully functional agent capable of scheduling meetings, managing emails, and performing context-aware actions.

🚀 Features

Autonomous Task Handling – Runs continuously to manage tasks and workflows.

Meeting Scheduler – Integrates with calendars to schedule, check, and update meetings.

Email Manager – Sends, organizes, and responds to emails automatically.

Context-Aware Decisions – Acts intelligently based on task context, not just simple responses.

Custom Commands – Supports personal commands like daily briefs, music playback, and more.

🛠 Tech Stack

LangGraph Framework – Structured orchestration of autonomous agents.

Flask API – Backend server for scalable integrations.

Environment Variables & dotenv – Secure management of API keys and passwords.

Tested with Multiple LLMs – GPT-4o Mini, LLaMA 70B, and DeepSeek R1 for versatility.

⚡ Getting Started

Clone the repository:

git clone https://github.com/umerfayaz/Mindara-Agent.git

Install dependencies:

pip install -r requirements.txt


Run the agent:

python ai_sidekick/app.py

📂 Repository Structure
ai_sidekick/         # Core agent scripts
frontend/            # Frontend interface
.sidekick-frontend/  # Ignored
.env                 # Local environment variables (ignored)
