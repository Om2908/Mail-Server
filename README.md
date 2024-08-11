Mail-Server

This project is a simple mail server implemented to handle sending and receiving emails. 
The server is built to be efficient, scalable, and easy to deploy. 
It offers essential features required to operate a functional mail server.

Features:
SMTP Support: Handles outgoing mail with Simple Mail Transfer Protocol (SMTP).
IMAP/POP3 Support: Manages incoming mail using Internet Message Access Protocol (IMAP) and Post Office Protocol 3 (POP3).
User Authentication: Secure login for users to access their mail.
Spam Filtering: Basic spam filtering to prevent unwanted emails.
Logging: Detailed logs for monitoring server activity.

Installation:

1) Clone the Repository:
git clone https://github.com/Om2908/Mail-Server.git
cd Mail-Server

2) Install Dependencies:
Ensure you have Node.js installed
npm install
npm i smtp-server
npm i @types/smtp-serve

Usage:

1) Sending Emails
   To send an email, use an SMTP client or the provided API. Ensure you have the correct SMTP settings configured.

2) Receiving Emails
   The server supports IMAP and POP3 protocols. Use any compatible client to receive emails.
