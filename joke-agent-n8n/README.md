# 🤖 Joke Agent (n8n + LLM + Joke API)

A fun little experiment where I built my first **AI Agent** using [n8n](https://n8n.io/), **Google Gemini**, and a public **Joke API**.  
This agent listens to a chat message, fetches a joke, and delivers it back in real-time. 🎉  

---

## ✨ Features
- 🗨️ **Chat Trigger** – Start a conversation with the agent.
- 🤖 **LLM-powered Agent** – Uses Google Gemini to handle chat flow and responses.
- 😂 **Joke API Integration** – Fetches jokes dynamically from `https://v2.jokeapi.dev`.
- 🔄 **Agentic Workflow** – Combines LLM reasoning with API tools in n8n.
- 🎯 **Fun Demo** – Perfect first step into building AI agents.

---

## 🛠️ Tech Stack
- [n8n](https://n8n.io/) – Workflow automation
- [Google Gemini](https://ai.google/) – LLM for conversational intelligence
- [JokeAPI](https://jokeapi.dev/) – Joke source
- Node.js / APIs / Automation

---

## 📸 Demo
Here’s what the workflow looks like in n8n:

<img width="1918" height="897" alt="image" src="https://github.com/user-attachments/assets/e003cfe8-d8f5-4fd2-b0ab-c939365acbd8" />


---

## 🚀 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/joke-agent-n8n.git
   cd joke-agent-n8n
   ```

2. Open [n8n](https://n8n.io/) and recreate the workflow (or import the JSON if included).

3. Add your **Google Gemini API key** in the credentials.

4. Connect the **HTTP node** to JokeAPI (`https://v2.jokeapi.dev/joke/Any`).

5. Start the agent and send a chat message – it will reply with a joke. 🎉

---

## 📌 Example Output

```
User: Tell me a joke
Agent: Why don’t scientists trust atoms?  
Because they make up everything! 😆
```

---

## 🔮 Future Improvements

* Add multiple joke categories (dad jokes, programming jokes, dark humor 😅).
* Deploy as a Telegram/Slack bot.
* Memory for tracking which jokes have already been told.

---

## 💡 Inspiration

This was my first hands-on with **AI Agents** in n8n – a fun way to explore how **LLMs + APIs + automation** can work together. 🚀

```

Would you like me to also create the **workflow JSON export** (so others can directly import your agent into n8n), or just keep it as a README-only repo?
```
