# 🧠 SuperCoach AI

SuperCoach AI is an intelligent assistant built with Python to help coaches deliver impactful courses and support students throughout their learning journey. It ensures students stay on track, motivated, and guided by combining multiple AI-driven roles in one unified platform.

---

## 🚀 Features

### 🎯 Accountability Partner
- Tracks student tasks and progress
- Guides students with the next actionable step
- Adjusts tone based on commitment levels

### 🧑‍🏫 Expert Guide
- Answers course-related questions
- Uses RAG (Retrieval-Augmented Generation) for context-aware guidance
- Suggests additional resources and clarifies next steps

### 💬 Motivating Friend
- Sends personalized, uplifting messages
- Understands student goals, interests, and past struggles
- Encourages students when they feel stuck or need a boost

### 📈 Impact Analyst
- Collects feedback after major tasks
- Asks for testimonials and referrals at the right moments
- Detects inactivity or key wins to trigger relevant prompts

### 🎁 Reward Manager
- Gamifies learning through points and badges
- Issues surprise rewards (vouchers, discounts, etc.) for milestones

### 🧩 Orchestration Manager
- Routes requests to the right AI agent
- Validates and responds with appropriate feedback or help
- Ensures smooth system flow and interactions

---

## 🧰 Tech Stack

| Layer       | Technology                            |
|-------------|----------------------------------------|
| **Language**     | Python                                |
| **AI Framework** | [Crew AI](https://github.com/joaomdmoura/crewAI) – multi-agent coordination |
| **Database**     | [Supabase](https://supabase.com) – user data, task tracking, progress |
| **Frontend**     | Bolt (React) – clean, interactive user interface |
| **Integrations** | OpenAI API, Email/SMS/WhatsApp (planned), Webhooks |

---

## 📂 Project Structure

```bash
supercoach-ai/
├── agents/              # All agent logic (Accountability, Guide, etc.)
├── workflows/           # Task flows, decision trees
├── prompts/             # Prompt templates for various use cases
├── data/                # User progress, feedback, etc.
├── utils/               # Common utilities
├── supabase/            # Supabase integration helpers
├── main.py              # Entry point for the app
├── config.py            # Config and environment variables
├── README.md
└── requirements.txt
