# Twitch Chat Setup Guide

## Prerequisites

### 1. Install Python Dependencies
Make sure Python is installed on your operating system, then install the required dependencies using pip:
```bash
pip install --upgrade pillow mss requests
```

### 2. Get a Gemini API Key
1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **"Get API key"** or **"Create API key"**
4. Copy your API key

### 3. Set Up Your API Key

**On Linux/Mac:**
```bash
export GEMINI_API_KEY="your-api-key-here"
```

**On Windows (Command Prompt):**
```cmd
set GEMINI_API_KEY=your-api-key-here
```

**On Windows (PowerShell):**
```powershell
$env:GEMINI_API_KEY="your-api-key-here"
```

**For Codespaces:**
Add `GEMINI_API_KEY` as a Codespace secret:
1. Go to your GitHub repository settings
2. Navigate to **Secrets and variables** → **Codespaces**
3. Click **New repository secret**
4. Name: `GEMINI_API_KEY`
5. Value: your API key

## Running the Application

### Launch the Script
Open your terminal, navigate to the directory containing the script, and run:
```bash
python TwitchChat.py
```

---

You're all set! The program should now be running using Google's Gemini API (no local model required).
