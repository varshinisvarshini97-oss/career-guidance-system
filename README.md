# 🎯 Intelligent Career Guidance System

### An Intelligent Career Guidance System Using Machine Learning and Behavioral Analysis

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel)](https://career-guidance-system-nhfx.vercel.app)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=node.js)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/API-Express.js-000000?logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb)](https://www.mongodb.com/)
[![Machine Learning](https://img.shields.io/badge/ML-KNN-orange)](https://scikit-learn.org/)
[![AI](https://img.shields.io/badge/AI-Gemini-blue)](https://ai.google.dev/)

## 🌐 Live Demo

**Live Website:**  
https://career-guidance-system-nhfx.vercel.app

---

## 📌 About the Project

The **Intelligent Career Guidance System** is a full-stack web application designed to help students and job seekers identify suitable career paths based on their **skills, interests, behavioral characteristics, and career preferences**.

The system combines **Machine Learning, behavioral analysis, skill-gap analysis, personalized learning recommendations, and Generative AI** to provide a personalized career development experience.

Instead of providing generic career suggestions, the system analyzes user-specific information and generates recommendations based on the individual's profile.

---

## 🎯 Problem Statement

Students often struggle to decide which career path is suitable for them because they may not have:

- Clear knowledge of different career options
- Awareness of the skills required for specific careers
- Understanding of their current skill level
- A personalized learning roadmap
- Reliable guidance about courses and learning resources

Traditional career guidance systems often provide static recommendations.

This project addresses these limitations by combining **Machine Learning and Behavioral Analysis** to provide more personalized career guidance.

---

## 💡 Proposed Solution

The system collects information about the user through:

- User profile
- Skills
- Interests
- Behavioral assessment
- Career preferences
- Learning progress

The collected information is processed by the recommendation system to:

1. Analyze the user's profile
2. Perform behavioral analysis
3. Recommend suitable careers
4. Identify missing skills
5. Calculate skill readiness
6. Generate a personalized roadmap
7. Recommend relevant courses
8. Track learning progress
9. Provide AI-powered career assistance

---

# 🚀 Key Features

## 👤 User Authentication

- User registration
- User login
- JWT-based authentication
- Protected routes
- Secure password handling
- User session management

---

## 🧑‍💼 User Profile

Users can maintain their professional profile including:

- Education
- Skills
- Interests
- Career preferences
- Experience
- Personal information

---

## 🧠 Behavioral Assessment

The system evaluates user behavior and preferences through an assessment.

The behavioral information is used as an additional input for career recommendation.

The goal is to understand characteristics such as:

- Interests
- Work preferences
- Problem-solving orientation
- Technical preferences
- Career interests

---

# 🤖 Machine Learning Career Recommendation

The project uses the **K-Nearest Neighbors (KNN)** algorithm for career recommendation.

### Basic workflow

```text
User Profile
     ↓
Skills & Interests
     ↓
Behavioral Assessment
     ↓
Feature Processing
     ↓
KNN Model
     ↓
Career Similarity
     ↓
Recommended Careers
```

KNN identifies users or career profiles with similar characteristics and uses those similarities to generate career recommendations.

---

# 📊 Skill Gap Analysis

After recommending a career, the system compares the user's current skills with the skills required for that career.

Example:

```text
Career: Full Stack Developer

Current Skills
✓ JavaScript
✓ React
✓ Node.js
✓ MongoDB

Missing Skills
✗ TypeScript
✗ Docker
✗ AWS
✗ System Design
```

The system can then calculate the user's **skill readiness** and identify areas that require improvement.

---

# 🗺️ Personalized Career Roadmap

The system generates a structured learning roadmap based on the user's career goal and skill gaps.

Example:

```text
Phase 1
HTML + CSS
      ↓
Phase 2
JavaScript
      ↓
Phase 3
React
      ↓
Phase 4
Node.js + Express
      ↓
Phase 5
MongoDB
      ↓
Phase 6
Deployment
      ↓
Full Stack Developer
```

---

# 📚 Personalized Courses

Based on the recommended career and missing skills, users receive course recommendations.

The system helps users understand:

- What to learn
- Why to learn it
- Which skills to prioritize
- What to learn next

---

# 📈 Progress Tracking

Users can track their learning progress.

Progress information can include:

- Completed skills
- Learning progress
- Roadmap completion
- Course progress
- Skill readiness

---

# 🤖 AI Career Assistant

The system includes an AI-powered career assistant using **Google Gemini**.

The assistant can help users with:

- Career-related questions
- Skill recommendations
- Learning guidance
- Interview preparation
- Resume-related guidance
- Career planning

The AI assistant provides personalized responses based on the user's career context.

---

# 💬 Feedback System

Users can provide feedback about their experience with the platform.

This helps administrators understand:

- User satisfaction
- System usability
- Recommendation quality
- Areas for improvement

---

# 👨‍💼 Admin Dashboard

The application includes an administrative dashboard.

Administrators can manage:

### Career Management

- Create careers
- Update careers
- Delete careers
- View career information

### Skill Management

- Create skills
- Update skills
- Delete skills
- Manage career-skill relationships

### Analytics

Administrators can view system-level information and user analytics.

---

# 🏗️ System Architecture

```text
                     ┌──────────────────────┐
                     │      User / Admin     │
                     └──────────┬───────────┘
                                │
                                ▼
                     ┌──────────────────────┐
                     │    React Frontend    │
                     │      + Vite          │
                     └──────────┬───────────┘
                                │
                              Axios
                                │
                                ▼
                     ┌──────────────────────┐
                     │   Node.js + Express  │
                     │       REST API       │
                     └───────┬───────┬──────┘
                             │       │
                ┌────────────┘       └────────────┐
                ▼                                 ▼
       ┌─────────────────┐              ┌─────────────────┐
       │    MongoDB      │              │  ML / AI Layer  │
       │    Database     │              │ KNN + Gemini AI │
       └─────────────────┘              └─────────────────┘
```

---

# 🛠️ Technology Stack

## Frontend

- React
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React
- Axios
- React Router

## Backend

- Node.js
- Express.js
- REST API
- JWT Authentication
- bcrypt

## Database

- MongoDB
- MongoDB Atlas

## Machine Learning

- K-Nearest Neighbors (KNN)
- Behavioral Analysis
- Feature-based career recommendation

## Artificial Intelligence

- Google Gemini API

## Deployment

- Vercel
- MongoDB Atlas

---

# 📁 Project Structure

```text
career-guidance-system/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── context/
│   │   ├── hooks/
│   │   └── ...
│   ├── public/
│   └── package.json
│
├── .gitignore
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone https://github.com/varshinisvarshini97-oss/career-guidance-system.git
```

```bash
cd career-guidance-system
```

---

## 2. Backend Setup

Navigate to the backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

Start the backend:

```bash
npm run dev
```

---

## 3. Frontend Setup

Open another terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create your frontend environment file if required:

```env
VITE_API_URL=your_backend_api_url
```

Start the development server:

```bash
npm run dev
```

---

# 🔐 Environment Variables

Never commit your `.env` files to GitHub.

Example:

```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret
GEMINI_API_KEY=your_api_key
```

Use `.env.example` when sharing the required environment variable names.

---

# 🔄 Application Workflow

```text
User Registration
       ↓
Login
       ↓
Create Profile
       ↓
Behavioral Assessment
       ↓
Analyze Skills & Interests
       ↓
KNN Career Recommendation
       ↓
Recommended Career
       ↓
Skill Gap Analysis
       ↓
Personalized Roadmap
       ↓
Course Recommendations
       ↓
Learning Progress
       ↓
AI Career Assistance
```

---

# 📊 Example Career Recommendation

A user may provide:

```text
Skills:
JavaScript
React
Node.js
MongoDB
Python

Interests:
Web Development
Software Development
Problem Solving
```

The system analyzes these characteristics and may recommend:

```text
1. Full Stack Developer
2. Frontend Developer
3. Backend Developer
```

The system can then identify missing skills and generate a learning roadmap.

---

# 🔒 Security

The application uses several security mechanisms:

- JWT authentication
- Password hashing using bcrypt
- Protected API routes
- Environment variables for sensitive configuration
- Role-based access for administrative functionality

Sensitive API keys and database credentials are not stored directly in source code.

---

# 🌐 Deployment

### Frontend

Deployed using **Vercel**.

**Live Application:**

https://career-guidance-system-nhfx.vercel.app

### Database

MongoDB Atlas is used for cloud database management.

### Backend

The backend can be deployed independently using a Node.js-compatible hosting platform.

---

# 🔮 Future Enhancements

Potential future improvements include:

- Advanced recommendation models
- More behavioral assessment dimensions
- Resume analysis using AI
- Job recommendation system
- Real-time job market analysis
- Salary prediction
- Interview preparation module
- Skill certification tracking
- LinkedIn profile analysis
- Career trend prediction
- Advanced ML model comparison
- Explainable AI recommendations

---

# 🎓 Academic Project

This project was developed as an academic and practical implementation of:

- Machine Learning
- Behavioral Analysis
- Web Development
- Artificial Intelligence
- Database Management
- REST API Development
- Full-Stack Development

The project demonstrates how Machine Learning and Generative AI can be combined with a full-stack web application to provide personalized career guidance.

---

# 👩‍💻 Author

**Varshini S**

Computer Science and Engineering

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is developed for educational and academic purposes.
