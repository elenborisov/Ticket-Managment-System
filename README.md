#STARTING APPLICATION:

start server by: npm run dev
start client by: npm start

#Use create elen-database.sql to create the database!

#make .env file in main folder with the following settings, you have to fill them up:

#SERVER AND TOKEN SETTINGS

DATABASE_HOST  = DATABASE_HOST
DATABASE_USER = DATABASE_USERNAME
DATABASE_PASS = DATABASE_PASSWORD
DATABASE_NAME = DATABASE_NAME
DATABASE_TICKETS_TABLE_NAME = TICKETS_TABLE_NAME
DATABASE_USERS_TABLE_NAME = USERS_TABLE_NAME
SECRET_TOKEN = YOUR_SECRET_TOKEN
SERVER_PORT = 5000

#JIRA SETTINGS
JIRA_API_KEY = YOUR_JIRA_KEY
JIRA_DOMAIN_NAME = YOUR_JIRA_DOMAIN
JIRA_PROJECT_KEY = YOUR_JIRA_PROJECT_KEY
JIRA_USER = YOUR_JIRA_EMAIL
JIRA_ACCOUNT_ID = YOUR_JIRA_ACCOUNT_ID