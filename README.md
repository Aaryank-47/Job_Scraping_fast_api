# Job Scraping API

## 🔍 About

This project enables job scraping from LinkedIn and Indeed using **BeautifulSoup** and **Selenium**.  
It provides a powerful backend API that scrapes job data and serves it to a browser extension frontend.

- ✅ Scrapes job listings using automation tools.
- 🌐 Backend is already deployed and functional.
- 🧩 Frontend (Chrome Extension): [Job_Scraping_Extension_Frontend](https://github.com/Aaryank-47/Job_Scraping_Extension_Frontend.git)

## 🖼️ Frontend Preview

![CareerLaunch Frontend Screenshot](./Job_Scraping_UI.png)


## 🗂️ Repository Structure

- `.env` – For storing environment variables (API keys, credentials, etc.)
- `api.py` – Main API file with all backend routes and scraping logic.
- `requirements.txt` – Contains all required Python packages.

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-link>

### 2. Navigate to the project folder

cd .\Scrape_API\

### 3. Create a virtual environment and activate it
python -m venv venv
.\venv\Scripts\activate


### 4. Install the required packages

pip install -r requirements.txt

### 5. Start the FastAPI server using Uvicorn

uvicorn api:app --reload


🔗 Frontend (Browser Extension)
# You can find the Chrome Extension (frontend) here:
https://github.com/Aaryank-47/Job_Scraping_Extension_Frontend.git




