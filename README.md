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

| Layer         | Technology |
|---------------|------------|
| **Language**  | Python |
| **AI Framework** | [Crew AI](https://github.com/joaomdmoura/crewAI) – multi-agent coordination |
| **Database**  | [Supabase](https://supabase.com) – user data, task tracking, progress |
| **Frontend**  | Bolt (React) – clean, interactive user interface |
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
````

---

## 🛠️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/supercoach-ai.git
cd supercoach-ai
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file and add your API keys and Supabase config:

```env
OPENAI_API_KEY=your_api_key
SUPABASE_URL=https://yourproject.supabase.co
SUPABASE_KEY=your_supabase_service_role_key
```

### 5. Run the project

```bash
python main.py
```

---

## 🧪 Example Use Case

A student logs in through the Bolt-based frontend and sees their next pending task.

They ask:

> "I'm stuck. What should I do next?"

SuperCoach AI routes the request to the **Expert Guide**, which gives clear next steps, shares resources, and sends a motivational message from the **Motivating Friend**.
If the student completes the task, they earn points or even a surprise reward!

---

## 📌 Roadmap

* [ ] Admin/coach dashboard (via Supabase & Bolt)
* [ ] Personalized AI agents per student
* [ ] Voice support for conversations
* [ ] Mobile app version
* [ ] Reporting & insights for coaches

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to improve or build.

---

## 📄 License

MIT License. See `LICENSE` file for details.

---

## 💡 Inspiration

SuperCoach AI was created to make coaching more scalable, personal, and effective — combining the human touch with intelligent automation.

---

Let us know if you'd like help with:

* `requirements.txt` example
* Supabase table schema
* Sample `.env` file
* Deployment steps (e.g., Docker, Railway, Render)
