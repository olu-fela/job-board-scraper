# Job Board Scraper

## Version 1 - Emailing Relevant Daily Job Postings Scraped from Job Boards
This is a Python script that:
- Scrapes multiple job boards (Indeed, LinkedIn, Glassdoor, RemoteRocketShip)
- Filters for remote Data Science, Data Engineering, and Data Analysis jobs
- Sends an email alert with new job postings
- Runs automatically every 24 hours

**Next Steps**
- Set up your email credentials (replace "your_email@gmail.com" and "your_email_password" in the script).
- Run the script on a server or local machine (use cron jobs or Windows Task Scheduler for automation).
- Modify job search filters if needed (add/remove job boards or keywords).

## Version 2 - Display Relevant Daily Job Postings Scraped from Job Board
Updated the Python script to:
- Display job postings in a Streamlit UI instead of sending email alerts
- Add a "Scrape Jobs Now" button for manual job scraping
- Continue running automated daily scraping in the background

**Next Steps**
- Run the script using streamlit run script.py to launch the web interface.
- Click the "Scrape Jobs Now" button to manually fetch new job postings.
- Let the automated process run in the background for daily updates.

## Version 3