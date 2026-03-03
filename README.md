🚀 AI-Powered Personalized News Email Automation

An automated system that delivers personalized AI-generated news summaries to users based on their selected interests.
This workflow fetches users from a database, retrieves real-time news via API, generates summaries using an LLM, and sends personalized email digests automatically.
🎥 Demo Video

[![Watch the demo](https://img.youtube.com/vi/YyMEKa875ck/0.jpg)](https://youtu.be/YyMEKa875ck)

Click the thumbnail above to watch the full demo.
🔥 Features

1. Fetches active users from Supabase
2. Supports multiple interests per user
3. Retrieves real-time news via GNews API
4. Generates AI summaries using LLM (Llama 3)
5. Sends personalized email digests via Gmail
6. Fully automated workflow using n8n
   
🧠 Tech Stack

**n8n** – Workflow automation engine  
**Supabase** – Database  
**GNews API** – Real-time news source  
**LLM (Llama 3 via OpenRouter)** – AI summarization  
**Gmail API** – Email delivery  

## ⚙️ How It Works

1. Fetch active users from Supabase  
2. Parse and split multiple user interests  
3. Fetch interest-based news via API  
4. Generate clean AI summaries  
5. Send personalized email to each user  

🏗 Workflow Architecture

<img width="1559" height="661" alt="image" src="https://github.com/user-attachments/assets/c779a379-a65f-41f8-bb06-20e1bc8da308" />




 🔐 Setup Instructions

1. Clone this repository  
2. Import ` My workflow 2.json` into n8n  
3. Add your credentials:
   - GNews API key
   - LLM API key
   - Supabase credentials
   - Gmail credentials  
4. Run the workflow
    Example Email Output

Each user receives:

- A clean, AI-generated summary  
- Based only on their selected interests  
- Delivered directly to their inbox  

 Why This Project?

This project demonstrates:

- API integration  
- Multi-step automation logic  
- AI-powered content generation  
- Real-world workflow orchestration  
- End-to-end system design  

Future Improvements

- Web frontend for user registration  
- Scheduled daily automation  
- Email formatting enhancements  
- Deployment on cloud n8n instance  

Author

Built as a personal project to explore AI + automation workflows.
