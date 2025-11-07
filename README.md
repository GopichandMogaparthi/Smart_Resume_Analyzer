# Smart_Resume_Analyzer
Smart Resume Analyzer (AI-powered)
# Smart Resume Analyzer

**AI-powered Resume Analyzer** — upload a resume, compare it to a job description, get a semantic match score and AI-generated improvement suggestions.

## Architecture (MVP)
- Frontend: React + TypeScript (port 3000)
- Backend: Spring Boot (port 8080)
- AI microservice: FastAPI (port 8000)
- DB: PostgreSQL (dev via Docker)
- Storage: AWS S3 (dev: local /uploads)

## Quickstart (dev)
1. Clone repo
2. Start Postgres & Redis with docker-compose (infra/docker-compose.yml)
3. Start backend: `./backend/gradlew bootRun`
4. Start ai-service: `cd ai-service && uvicorn main:app --reload --port 8000`
5. Start frontend: `cd frontend && npm install && npm run dev`

## Contribution
Follow branch naming & commit message conventions in CONTRIBUTING.md
