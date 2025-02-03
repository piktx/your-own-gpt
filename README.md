# 🤖 Dual-Mode AI Chat Platform

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Chainlit](https://img.shields.io/badge/Chainlit-4A154B?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-00ADD8?style=for-the-badge)

**Two powerful chat implementations** using cutting-edge AI models with unique capabilities:

1. **MiniGPT** - Web-based ChatGPT clone with reasoning visualization 🔍
2. **LocalGPT** - Multimodal vision-capable assistant with chain-of-thought 🖼️

## 🌟 Key Features

### MiniGPT (Streamlit)
- **Thinking Visualization** 🧠  
  Real-time reasoning process display with expandable sections
- **Streaming Responses** ⚡  
  Token-by-token output generation
- **Custom UI** 🎨  
  Branded interface with DeepSeek integration
- **Session Management** 🔄  
  Persistent chat history across interactions

### LocalGPT (Chainlit)
- **Multimodal Input** 🖼️  
  Image + Text understanding with Llama3.2-Vision
- **Chain-of-Thought** 🔗  
  Step-by-step process visualization
- **Local Execution** 💻  
  100% offline-capable implementation
- **Interactive Elements** 🎚️  
  Native file upload support and streaming

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/piktx/your-own-gpt.git
cd your-own-gpt

# Install dependencies
pip install -r requirements.txt

# Run MiniGPT (Web UI)
streamlit run minigpt.py

# Run LocalGPT (Local Server)
chainlit run local_gpt.py -w
