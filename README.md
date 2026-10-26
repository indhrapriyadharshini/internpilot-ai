# InternPilot AI – AI-Powered Internship Assistance Chatbot

## Project Overview

**InternPilot AI** is an AI-powered internship assistance chatbot designed to help students with internship-related queries and career guidance.

The chatbot provides a simple conversational interface where students can ask questions and receive helpful responses about internships, skills, resumes, interview preparation, and career opportunities.

## Objectives

- Provide instant responses to internship-related questions.
- Help students understand internship requirements.
- Guide students in improving their resumes and skills.
- Support interview preparation.
- Make internship information easier to access through a chatbot interface.

## Key Features

- **AI-Powered Chatbot:** Answers internship and career-related questions.
- **Internship Guidance:** Provides information and guidance about internship opportunities.
- **Resume Assistance:** Helps students understand how to improve their resumes.
- **Skill Development Guidance:** Suggests relevant skills for career preparation.
- **Interview Preparation:** Provides interview questions and preparation tips.
- **User-Friendly Interface:** Simple and responsive web interface.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js, Vite |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI Integration | OpenAI API |
| Authentication | JWT |
| Email Integration | SMTP |

## Project Structure

```text
internpilot-ai/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── .env.example
│   └── package.json
│
├── README.md
└── .gitignore
```

## Installation and Setup

### Prerequisites

- Node.js
- npm
- MongoDB database
- OpenAI API key (if AI integration is enabled)

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd internpilot-ai
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the `server` folder using `.env.example` as a reference.

Configure the required values:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5174
OPENAI_API_KEY=your_openai_api_key
```

Add other variables required by the project's `.env.example` file.

**Important:** Never upload your `.env` file, passwords, or API keys to GitHub.

### 4. Start the Backend

```bash
npm run dev
```

### 5. Install Frontend Dependencies

Open another terminal:

```bash
cd client
npm install
```

### 6. Start the Frontend

```bash
npm run dev
```

Open the local URL displayed in your terminal to access the application.

## Expected Outcome

InternPilot AI aims to provide students with an accessible AI chatbot for internship-related assistance. It brings internship guidance, resume support, skill recommendations, and interview preparation into one conversational platform.

## Future Enhancements

- WhatsApp chatbot integration.
- Multilingual chatbot support.
- Personalized internship recommendations.
- Improved AI response accuracy.
- Additional career guidance features.

## Project Purpose

This project is developed as part of an AI Tool Development task, with the primary focus on building an AI-powered chatbot for internship assistance.
