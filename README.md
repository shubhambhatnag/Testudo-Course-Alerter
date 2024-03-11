# Testudo Course Alerter

Testudo Course Alerter is a web application built using NiceGUI and Python that helps students at the University of Maryland (UMD) get notified when a section opens up for a particular course they are interested in.

## Features

- Enter a course ID and select the section(s) you want to monitor
- Provide your email address to receive notifications
- Receive email notifications when a new section opens up or a seat becomes available in the monitored section(s)
- Automatic database management to keep track of user subscriptions

## Technologies Used

- Python
- NiceGUI
- BeautifulSoup (for web scraping)
- PostgreSQL (for data storage)
- Requests (for making HTTP requests)
- Asyncio (for asynchronous programming)
- smtplib (for sending emails)

## Setup

1. Clone the repository:

```bash
git clone https://github.com/shubhambhatnag/Testudo-Course-Alerter.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Set up the necessary environment variables:

- DB_URL: The connection string for your PostgreSQL database
- APP_EMAIL: The email address from which notifications will be sent
- APP_PASSWORD: The password for the APP_EMAIL account

4. Run the application:
 ```bash
python course_frontend.py
```
5. Access the application in your web browser at http://localhost:8080



