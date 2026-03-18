🌍 WellBot
AI-Powered Global Wellness Assistant Platform
A scalable, intelligent system designed to deliver personalized health insights, proactive wellness guidance, and conversational AI support.

🧠 Overview
WellBot is an AI-driven wellness platform that goes beyond traditional chatbots by combining:

Conversational AI
Health data tracking
Behavioral insights
Personalized recommendations
It is designed to act as a digital wellness companion, helping users make informed lifestyle decisions through continuous interaction and analysis.

🚀 Key Features
🤖 AI Conversational Assistant
Context-aware multi-turn conversations
Personalized responses based on user health data
Integration with multiple AI providers (OpenAI, Gemini, OpenRouter)
📊 Health Analytics Dashboard
BMI calculation and tracking
Nutrition scoring system
Health streak monitoring
Historical timeline visualization
🥗 Smart Wellness Recommendations
AI-generated diet suggestions
Lifestyle improvement insights
Preventive health guidance
🌐 Multi-language Support
Internationalization (i18n) enabled
Designed for global accessibility
🛠 Admin Panel
Monitor user interactions
Analyze system usage
Manage AI responses
🏗️ System Architecture
Frontend (React + Vite)
        ↓
Backend (Flask API)
        ↓
Service Layer (AI, Scheduler, OCR)
        ↓
AI Providers (OpenAI | Gemini | OpenRouter)
        ↓
Database (SQLite)
⚙️ Tech Stack
Frontend
React.js
Vite
CSS
Backend
Flask
SQLAlchemy
Alembic (migrations)
AI Integration
OpenAI API
Google Gemini API
OpenRouter
Database
SQLite (development-ready, scalable to PostgreSQL)
📁 Project Structure
wellbot/
├── backend/
│   ├── app/
│   │   ├── routes/
│   │   ├── services/
│   │   └── models.py
│   ├── migrations/
│   └── run.py
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── services/
│
└── documents/
🔐 Environment Variables
Create a .env file inside backend/:

DATABASE_URL=sqlite:///site.db
SECRET_KEY=your_secret_key
JWT_SECRET_KEY=your_jwt_secret
OPENAI_API_KEY=your_api_key
GEMINI_API_KEY=your_api_key
OPENROUTER_API_KEY=your_api_key
⚠️ Do not commit .env files. Use .env.example for reference.

▶️ Getting Started
1️⃣ Backend Setup
cd wellbot/backend
pip install -r requirements.txt
python run.py
2️⃣ Frontend Setup
cd wellbot/frontend
npm install
npm run dev
🔄 How It Works
User interacts via frontend interface
Request is sent to Flask backend
Backend processes user data and context
AI services generate intelligent response
Response is returned and displayed
📈 Future Enhancements
Emotion-aware AI responses
Mobile application (React Native / Flutter)
Cloud deployment (AWS / Vercel / Render)
Wearable device integration
Predictive health analytics
🤝 Contributors
Krishnendu Anil
Team C
📜 License
This project is licensed under the MIT License.

