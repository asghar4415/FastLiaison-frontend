# FAST Liaison App

The **FAST Liaison App** is an AI-powered university career platform designed to connect **students**, **career offices**, and **employers** in a single ecosystem.  
This repository contains the **frontend (React.js)** for the project.

---

## Overview

The platform allows:
- **Career Offices** to post jobs, internships, and manage student applications.  
- **Students** to explore opportunities, apply through AI-powered tools (resume/cover letter generator, job recommendations).  
- **Employers** to access a verified candidate pool and use AI-based ranking for hiring.

This app communicates with a **Node JS backend API** and may connect to a **Python-based AI microservice** for NLP features.

---

## Environment Setup

### Install dependencies
```bash
npm install

### Create .env file in the project root

VITE_API_BASE_URL=http://localhost:5000/api
VITE_AI_BASE_URL=http://localhost:8000

### Start the development server
```bash
npm run dev

## Collaboration Workflow
All contributors must follow this branching and PR process:

# 1. Clone the repository
git clone https://github.com/asghar4415/FastLiaison-frontend.git
cd FastLiaison-frontend

# 2. Create a new branch for your feature
git checkout -b feature-<your-feature-name>

# 3. Make your changes, then commit
git add .
git commit -m "Added <your-feature-name>"

# 4. Push your branch
git push origin feature-<your-feature-name>

# 5. Open a Pull Request on GitHub
# Assign @asghar4415 as the reviewer

