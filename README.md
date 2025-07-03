🎉 Myntra Review Scraper Project
A Streamlit-powered web application that scrapes, stores, and visualizes customer reviews for Myntra products.

🚀 Features

Feature

Description

🕸️ Web Scraping

Extracts product reviews using Selenium + BeautifulSoup.

💾 Data Storage

Saves and retrieves reviews in MongoDB Atlas.

📊 Interactive Dashboard

Visual analytics built with Streamlit.

📈 Report Generation

Auto-generates summary reports and visual charts.

🔧 Prerequisites

Python 3.8 or higher

MongoDB Atlas account (Optional; defaults configured)

Google Chrome browser + matching ChromeDriver

🛠️ Installation

Clone the repo or download the ZIP:

git clone https://github.com/yourusername/myntra-review-scraper.git
cd myntra-review-scraper

Install dependencies:

pip install -r requirements.txt

(Optional) Local Install:

pip install -e .

▶️ Usage

1. Run the Streamlit App

streamlit run app.py

Open your browser at http://localhost:8501

Enter a Myntra product URL or name to scrape reviews.

2. Jupyter Notebook Analysis

jupyter notebook myntra.ipynb

Explore raw data and generate custom visualizations.

📁 Project Structure

├── app.py               # Streamlit application entry point
├── myntra.ipynb         # Jupyter notebook for data exploration
├── requirements.txt     # Python dependencies
├── setup.py             # Package metadata & install config
├── src/                 # Primary Python package
│   ├── cloud_io/        # MongoDB I/O utilities
│   ├── scrapper/        # Scraper logic (Selenium & BS4)
│   ├── utils/           # Helper functions
│   ├── data_report/     # Automated report scripts
│   ├── constants.py     # Global constants
│   └── exception.py     # Custom exception classes
├── pages/               # Streamlit multipage components
│   └── generate_analysis.py
├── static/              # CSS & static assets
│   └── css/
├── templates/           # HTML templates (optional)
└── data.csv             # Sample dataset

🤝 Contributing

We welcome contributions! Please:

Fork the repository

Create a feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add YourFeature')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request

📜 License

Distributed under the MIT License. See LICENSE for more information.

Made with ❤️ by Your Name