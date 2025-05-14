## Nextgen-Yoga-App
A Python-based project that recommends yoga poses using Firestore vector search and Gemini-generated context. Built to explore AI-powered search and Google Cloud tools.
## Features

- Search yoga poses by text prompt  
- Vector similarity matching using Firestore  
- Gemini-generated descriptions for each pose  
- Simple web UI (Flask)  
- Optional TTS audio generation for poses  
- Deployable to Google Cloud Run  

## Tech Stack

- Python  
- Google Firestore (with vector support)  
- LangChain + Gemini (LLM)  
- Flask (web backend)  
- Text-to-Speech (Google Cloud)  
- Google Cloud Run (deployment)  

## How to Run Locally

1. Clone the repo  
2. Set up and activate virtual environment:  
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
4. Start the app:

   ```bash
   python main.py
   ```
Visit `http://localhost:8080` in your browser.

## Output Images
![Screenshot 2025-05-14 001812](https://github.com/user-attachments/assets/788ca667-5e13-4640-a3c2-4adc60d10069)

![Screenshot 2025-05-14 001929](https://github.com/user-attachments/assets/7d2cae9b-ec00-4400-bd23-2c2a36711b22)


