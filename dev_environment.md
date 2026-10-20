# Development Environment

## Project
AI-personalized learning web platform with a parent monitoring role.

## System Components
- Web app: web platform used by students and parents
- AI engine: personalization, flags low activity
- Database: stores activity log, scores, weak topics
- Parent: monitoring role (notifications, dashboard, report)

## Hardware / OS
- OS: Windows 11
- IDE: Visual Studio Code

## Tech Stack
- Frontend: React 18, HTML/CSS/JavaScript
- Backend: Node.js 20, Express
- AI engine: Python 3.11
- Database: MySQL 8
- Version control: Git, GitHub

## Tools
- VS Code extensions: ESLint, Prettier, SQLTools, Markdown Preview
- API testing: Postman
- Diagrams: draw.io / dbdiagram.io

## How to Run
1. `git clone <your-repo-url>`
2. `cd backend && npm install`
3. Create `.env` with DB_HOST, DB_USER, DB_PASSWORD, DB_NAME
4. Import schema: `mysql -u root -p < schema.sql`
5. `npm start`
6. `cd ../frontend && npm install && npm start`
