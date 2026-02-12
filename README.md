# HR Dashboard – Recruitment Management System For A University

## Overview
The HR Dashboard is a web-based recruitment management platform designed to modernize and streamline the candidate screening process for a university Human Resources department.  
The system centralizes candidate data, document management, interview tracking, and AI-assisted evaluation, replacing traditional manual recruitment workflows.

## Key Features
- Full Candidate Management (Create, Read, Update, Delete)
- Secure CV and document upload system
- Candidate status tracking (active / eliminated – soft delete)
- Interview round progress tracking
- Two-Factor Authentication (TOTP)
- AI-powered candidate scoring using LLaMA model via Groq
- Structured recruitment workflow dashboard

## Technologies Used
- Python
- Flask
- PostgreSQL
- HTML / CSS / JavaScript
- TOTP Authentication
- Groq LLaMA API (AI Candidate Evaluation)

## My Contributions
- Designed and implemented candidate CRUD management modules
- Implemented soft-delete candidate tracking system
- Developed interview status workflow management
- Integrated Two-Factor Authentication (TOTP)
- Implemented AI-based candidate ranking component
- Contributed to UI improvements and database structure design

## Installation
```bash
git clone https://github.com/username/hr-dashboard-recruitment-system.git
cd hr-dashboard-recruitment-system
pip install -r requirements.txt
python app.py
