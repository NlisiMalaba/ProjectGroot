SmartFeedback — AI-Powered Customer Feedback Analyzer
❗️Problem Statement:
Many businesses collect customer feedback but struggle to extract meaningful insights. Manual review is time-consuming, subjective, and often inconsistent. Small businesses especially lack tools to analyze sentiment or identify recurring issues from customer responses.

💡 Proposed Solution:
SmartFeedback is a full-stack microservices application that enables users to submit text or voice feedback. It leverages AI to automatically:

Analyze sentiment

Extract key themes

Suggest improvements

Business owners can view all feedback insights in a centralized dashboard, with visualizations and trend analysis to make data-driven decisions.

✨ Key Features:
🎤 Feedback Collection
Submit feedback via text or voice (converted to text)

Supports anonymous or authenticated submissions

🧠 AI Analysis
Sentiment analysis (positive, negative, neutral)

Keyword/topic extraction

Actionable suggestions

📊 Manager Dashboard
View feedback history

Sentiment trend charts over time

Filter by keyword, time, sentiment

🔔 Notifications
Alert admins when critical (very negative) feedback is received

👨‍👩‍👧 Authentication & Role Management
Login/Register (JWT)

Role-based access (User, Admin)

🧪 API Docs
Swagger/OpenAPI for public API endpoints

🚀 DevOps & Deployment
Dockerized services

CI/CD with GitHub Actions

Deployed backend (e.g. Railway/Render) + frontend on Vercel
