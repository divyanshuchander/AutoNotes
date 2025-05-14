# AutoNotes

**AutoNotes** is a local AI-powered note-taking tool that generates summaries from YouTube videos and local media files.

---

## 🛠️ Setup Instructions

### Prerequisites

- Python 3.x
- [Ollama](https://ollama.com) installed
- FFmpeg installed
- MLX Whisper installed
- `Mjh1051702/youtube:latest` model pulled via Ollama

### 1. Clone the Repository

```bash
git clone https://github.com/divyanshuchander/AutoNotes.git
cd AutoNotes
```

### 2. Setup a Python Environment & install the dependencies

```bash
pip -m venv <virtual env name>
pip install -r requirements.txt
```
### 3. Install Ollama and pull required LLM Model

```bash
ollama pull Mjh1051702/youtube:latest(Model Name)
```
