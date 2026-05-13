🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

### **Break the Ice. Get 5 in a Row. Make New Friends.**

Social Bingo is the game that turns "What do you have in common?" into laugh-out-loud moments at every event.

[Try the Game](#-quick-start) • [Learn to Build It](#-lab-guide) • [Join the Community](#-contributing)

</div>

---

## 🎮 What's Soc Ops?

Soc Ops is an interactive **bingo game for in-person events, conferences, and mixers**. It's simple, it's fun, and it actually *works* for getting people talking to strangers.

**How It Works:**
- 🎲 Start with a random 5×5 grid of fun prompts
- 👥 Move around and find people who match each square
- ✨ Get them to sign your square
- 🏆 Get 5 in a row (horizontal, vertical, or diagonal) to win!

Perfect for:
- 🎉 Conference icebreakers
- 🤝 Team building events  
- 🎓 School mixers & orientation days
- 💼 Networking events
- 🚀 Any gathering where you want people to connect

---

## ✨ Features

| Feature | Details |
|---------|---------|
| 📱 **Web-Based** | Works on any device with a browser—no app download needed |
| ⚡ **Real-Time** | Live game state management with session persistence |
| 🎨 **Modern UI** | Clean, responsive design that works on mobile and desktop |
| 🔄 **Customizable** | Easy to modify prompts and add your own questions |
| 📝 **Open Source** | Built with FastAPI, Jinja2, and modern Python practices |

---

## 🚀 Quick Start

### For Players

1. **Open the game** in your browser (URL provided by event organizer)
2. **Click "Start Game"** to generate your bingo card
3. **Find people** who match each square on your card
4. **Get bingo** with 5 in a row to win! 🎉

### For Developers

Get the game running locally in **3 commands**:

```bash
# Clone the repository
git clone https://github.com/lukabombala/my-soc-ops-python.git
cd my-soc-ops-python

# Install dependencies
pip install -e .

# Start the server
soc-ops
```

Then open your browser to **`http://localhost:8000`** and start playing!

**Requirements:** Python 3.13+

---

## 📚 Lab Guide

Learn to **build, customize, and extend** Soc Ops with the guided lab series:

| Part | Topic | What You'll Learn |
|------|-------|-------------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | Project context and prerequisites |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | Environment configuration and AI context setup |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | UI/UX best practices and modern styling |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | Building AI-powered custom agents |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Orchestrating multiple AI agents |

> 📝 All guides are available offline in the [`workshop/`](workshop/) folder.

---

## 🛠️ Tech Stack

- **Backend:** FastAPI + Uvicorn (async Python web framework)
- **Frontend:** Jinja2 templates + HTMX (modern, minimal dependencies)
- **Game Logic:** Pure Python with type hints
- **Testing:** pytest with full coverage
- **Code Quality:** Ruff (linting & formatting)

---

## 📖 Project Structure

```
soc-ops/
├── app/
│   ├── main.py              # FastAPI app & routes
│   ├── game_logic.py        # Bingo board generation & win detection
│   ├── game_service.py      # Session management
│   ├── models.py            # Pydantic data models
│   ├── data.py              # Game prompts & constants
│   ├── static/              # CSS & assets
│   └── templates/           # HTML templates
├── tests/                   # Full test coverage
├── docs/                    # Documentation
├── workshop/                # Learning lab guides
└── pyproject.toml           # Project dependencies & config
```

---

## 🧪 Testing & Quality

Run the full test suite:

```bash
pytest                    # Run all tests
ruff check               # Check code style
ruff format .            # Auto-format code
```

---

## 🤝 Contributing

We love contributions! Here's how to get involved:

1. **Report Issues:** Found a bug? [Open an issue](../../issues)
2. **Suggest Features:** Have an idea? [Start a discussion](../../discussions)
3. **Submit Changes:** Send a [pull request](../../pulls)
4. **Improve Docs:** Help make the docs better

Read our [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📄 License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🙏 Code of Conduct

This project is committed to fostering an inclusive and welcoming community. Please read our [Code of Conduct](CODE_OF_CONDUCT.md).

---

<div align="center">

**Made with ❤️ for building connections at every event**

[⬆ Back to Top](#-soc-ops)

</div>
