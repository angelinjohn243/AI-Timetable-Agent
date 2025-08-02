# 📅 AI Timetable Agent – Agentic Scheduling System using LangChain + CSP

AI Timetable Agent is an intelligent **agent-based system** that generates academic timetables based on faculty, subjects, rooms, and constraints.

This project demonstrates a real-world **agentic AI workflow** by combining LangChain (for reasoning) with **Constraint Programming (CSP)** to ensure valid, conflict-free timetables — all in a clean Gradio UI.

👉 **🔗 [Try the Live Demo on Hugging Face](https://huggingface.co/spaces/Angelin11/Time_table_Agent)**

---

## 🚀 Key Features

- ✅ **User-Guided Agent**: Takes department, semester, faculty, subjects, and rooms as input.
- ✅ **Constraint Programming**: Ensures no faculty or room conflicts during scheduling.
- ✅ **LangChain-Powered**: Uses a LangChain agent to understand input prompts and trigger the right tool.
- ✅ **Dynamic UI**: Built using Gradio Blocks for clean, structured input/output.
- ✅ **HTML Output**: Renders the generated timetable as a styled HTML table.

---

## 🧪 Tech Stack

| Tool/Library         | Purpose                                              |
|----------------------|------------------------------------------------------|
| **Python**           | Core logic and data handling                         |
| **LangChain**        | Defines the AI agent and tool interaction            |
| **python-constraint**| Solves hard constraints using CSP                    |
| **Gradio**           | Frontend for inputs and viewing the timetable        |
| **Hugging Face Spaces** | Hosting the full stack web app                    |

---

## 📂 How It Works

1. ✍️ **User Input**: You enter faculty names, subjects, and room numbers.
2. 🧠 **Agent Prompted**: A LangChain agent receives your input as a prompt.
3. 📎 **Constraint Solving**: A tool uses constraint programming to allocate sessions.
4. 🧾 **Timetable Generated**: The tool returns a conflict-free, day-wise HTML timetable.
5. ✅ **Output Displayed**: You see a full schedule from Monday–Friday, 9AM–3PM (with lunch break).

---

## 📅 Example Use Case

> Department: `CSE`  
> Semester: `6`  
> Faculty: `Manu, Abi, Ann, Mani, Sabu`  
> Subjects: `AI, ML, DL, NLP, MATHS`  
> Rooms: `201, 202, 203, 204`

🧾 **Result**:  
An optimized weekly timetable with no overlapping teachers or rooms — shown in a readable, HTML table format.

---

## 📦 Deployment

Deployed on Hugging Face Spaces  
🔗 **[Live Space URL](https://huggingface.co/spaces/Angelin11/Time_table_Agent)**

---

## 🤖 Project Highlights

- Emulates real-world **autonomous agent behavior**
- Built using **zero-shot reasoning** with LangChain
- Modular & scalable – easily extendable to lab hours, multiple batches, and PDF/Excel exports
- **No hardcoding** – all inputs are dynamic

---

## 📝 Author

👩‍💻 **Angelin John**  
📍 Kerala, India  
🎓 BE CSE-AI | Sathyabama Institute of Science and Technology  
🚀 Passionate about GenAI, Autonomous Agents & Educational AI Systems

---

## ⚠️ Note

This is a **demo-level educational project**. It showcases AI agent logic + constraint satisfaction.

---

