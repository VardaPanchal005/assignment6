Node.js Email API
This Node.js application uses Express to create an API for sending emails via Gmail. It handles OAuth 2.0 authentication to securely store credentials and send emails.

Features
OAuth 2.0 Authentication:

Endpoint /auth/initiate to start the OAuth process.
Endpoint /auth/callback to handle token exchange and storage.
Send Emails:

Endpoint /email/send to send emails using stored credentials.
Setup
Clone the Repository:

bash
Copy code
git clone <repository-url>
Install Dependencies:

bash
Copy code
npm install
Configure Environment Variables:

Create a .env file based on .env.example and add your OAuth credentials.
Run the Server:

bash
Copy code
node app.js
# or
npm start
Test API Endpoints:

Use Postman to test /auth/initiate, /auth/callback, and /email/send.
