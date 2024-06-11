# LinkedIn Job Application Bot

This project is an automation script that uses Selenium to apply for jobs on LinkedIn. It logs in using your LinkedIn credentials, navigates to a specified job search page, and attempts to apply for the listed jobs. If a job application is complex, it skips it and moves to the next one.

## Features

- Automated login to LinkedIn
- Navigation to job search results
- Automated job application for simple applications
- Skips complex applications

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/LinkedIn-Job-Application-Bot.git
   cd LinkedIn-Job-Application-Bot
   ```

2. **Install the required packages:**
   Make sure you have [pip](https://pip.pypa.io/en/stable/) installed, then run:
   ```sh
   pip install selenium
   ```

3. **Download the Chrome WebDriver:**
   - Visit the [ChromeDriver download page](https://sites.google.com/a/chromium.org/chromedriver/downloads).
   - Choose a version compatible with your Chrome browser.
   - Extract the downloaded file and note its path.

## Usage

1. **Set up your credentials and paths:**
   Open `main.py` and replace the placeholders with your LinkedIn login email, password, phone number, and the path to your Chrome WebDriver:
   ```python
   ACCOUNT_EMAIL = "your_login_email"
   ACCOUNT_PASSWORD = "your_login_password"
   PHONE = "your_phone_number"
   chrome_driver_path = "/path/to/chromedriver"
   ```

2. **Run the script:**
   ```sh
   python main.py
   ```
