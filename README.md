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

auto-apply-assistant/ ├── auto_apply_assistant/ │ ├── test_selenium.py # Verifies Selenium is working │ ├── resume_parser.py # Extracts and filters meaningful resume keywords │ └── job_scraper.py # Launches browser, logs in, and searches jobs using extracted keywords ├── .gitignore └── README.md

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/dgoldberg1900/auto-apply-assistant.git
cd auto-apply-assistant


