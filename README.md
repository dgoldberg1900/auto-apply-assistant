# Auto Apply Assistant

Auto Apply Assistant is a smart tool that automates the job search process by analyzing your resume, extracting key qualifications, and launching browser-based job searches tailored to your skills and experience. It helps streamline repetitive job hunt tasks while keeping you in control.

---

## 🚀 Features

- 📄 Upload a resume PDF — no manual job title input required
- 🔍 Intelligent keyword extraction (from Skills, Summary, and Experience sections only)
- 🤖 Uses automation to search job platforms based on your actual qualifications
- 🔐 Prompts for user credentials securely — nothing is hardcoded or stored
- 🧠 Designed with flexibility for future upgrades like auto-apply and ranking matches

---

## 📂 Project Structure
```
auto-apply-assistant/
├── auto_apply_assistant/      # Main application package/module
│   ├── __init__.py            # Makes 'auto_apply_assistant' importable as a package
│   ├── resume_parser.py       # Extracts and filters meaningful resume keywords
│   ├── job_scraper.py         # Launches browser, logs in, searches, and applies for jobs
│   └── config_loader.py       # (Optional) Module to load configuration (e.g., from .env)
├── tests/                     # Contains all test files
│   ├── __init__.py            # Makes 'tests' importable
│   └── test_selenium_setup.py # Verifies Selenium environment is working correctly
│   └── test_resume_parser.py  # (Future) Unit tests for resume_parser functions
│   └── test_job_scraper.py    # (Future) Integration/functional tests for job_scraper
├── .env.example               # Example environment variables (credentials, paths) - DO NOT COMMIT ACTUAL .env
├── .gitignore                 # Specifies intentionally untracked files that Git should ignore
├── main.py                    # Main script to run the entire auto-apply process
├── README.md                  # This file - project description, setup, and usage instructions
└── requirements.txt           # Lists Python packages required by the project
```
---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/dgoldberg1900/auto-apply-assistant.git
cd auto-apply-assistant


