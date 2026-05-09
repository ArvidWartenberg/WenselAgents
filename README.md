# Installation & Setup

## 1. Install uv
`uv` is used for this project.

```bash
# Install uv
curl -LsSf [https://astral.sh/uv/install.sh](https://astral.sh/uv/install.sh) | sh
```

---

## 2. Install Ollama
Ollama is a tool for running large language models locally.

### Installation Steps:
#### Option A: Using the Official Installer
```bash
# Download and install Ollama
curl -Lfsso https://ollama.ai/releases/install.sh | bash
```
---

## Model Setup

### 1. Pull your model. I use the Optimized Qwen 3.5 35B MoE Model
```bash
# Pull the optimized model
ollama pull qwen3.5:35b-a3b
```

### 2. Verify Ollama Service Status
Ensure that the Ollama service is running:
```bash
# Check if Ollama is active
systemctl status ollama
```

