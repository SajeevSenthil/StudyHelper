# StudyHelper

A comprehensive study assistant application that helps students summarize documents, generate quizzes, and track their learning progress.

## Features

### 📄 Document Summarization
- Upload and summarize PDF documents, text files, and other study materials
- AI-powered summarization using advanced language models
- Save and organize your summaries for future reference

### 🧠 Quiz Generation
- Automatically generate quizzes from your uploaded documents
- Multiple question types and difficulty levels
- Track quiz performance and learning progress

### 📊 Analytics & Progress Tracking
- View detailed analytics of your study sessions
- Track quiz scores and improvement over time
- Monitor learning patterns and study habits

### 💾 Library Management
- Save and organize all your summaries and quizzes
- Easy access to past study materials
- Search and filter your study content

## Technology Stack

### Frontend
- **Next.js 15** - React framework for production
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Supabase** - Backend as a service for authentication and database

### Backend
- **FastAPI** - Modern, fast Python web framework
- **Python** - Core backend language
- **Supabase** - Database and authentication

## Getting Started

### Prerequisites
- Node.js 18+ 
- Python 3.8+
- Supabase account

### Frontend Setup
```bash
cd cloud-frontend
npm install
npm run dev
```

### Backend Setup
```bash
cd StudyHelper-Backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8001
```

## Project Structure

```
StudyHelper/
├── cloud-frontend/          # Next.js frontend application
│   ├── app/                 # App router pages and API routes
│   ├── components/          # Reusable React components
│   ├── lib/                 # Utilities and configurations
│   └── public/              # Static assets
└── StudyHelper-Backend/     # FastAPI backend application
    ├── main.py              # Main application entry point
    ├── summarizer.py        # Document summarization logic
    ├── resources.py         # Resource management
    └── requirements.txt     # Python dependencies
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.
