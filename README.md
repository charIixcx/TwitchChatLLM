# Twitch Chat Setup Guide

## Prerequisites

### 1. Install Python Dependencies
Make sure Python is installed on your operating system, then install the required dependencies using pip:
```bash
pip install [dependencies listed in requirements]
```

### 2. Install LM Studio
- [Download and install LM Studio](https://lmstudio.ai/) for your operating system
- LM Studio will be used to fetch models and run a local API server

### 3. Choose and Download a VLM Model
Pick a Vision-Language Model (VLM) from LM Studio's catalog:
- **Recommended**: Gemma 3 12b QAT (requires 7GB of VRAM)
- **Lower VRAM alternatives**: Qwen3 VL 4B or 8B

### 4. Configure the Script
Edit the `MODEL` parameter at the top of the script to match the exact name of the model you chose.

## Running the Application

### 1. Start the LM Studio Server
1. Open LM Studio
2. Navigate to the **Developer** tab
3. Toggle **Start server** (located at the top left of the screen)

### 2. Launch the Script
Open your terminal, navigate to the directory containing the script, and run:
```bash
python TwitchChat.py
```

---

You're all set! The program should now be running.
