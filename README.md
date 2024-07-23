# Mass-Mail-dispatcher
Introduction
The Mass Mail Dispatcher is a web application developed with React and Vite to simplify the process of sending emails to a list of recipients from a CSV file. Users can input sender details, attach a CSV file with recipient email addresses, and compose email messages. The application validates email addresses from the CSV file, distinguishing between valid and invalid ones.

Technologies Used
React + Vite: JavaScript library for building dynamic user interfaces.
Tailwind CSS: Utility-first CSS framework for styling.
Email.js: JavaScript library for sending emails via various email services.
Features
User Input Form:

From Address: Enter the sender's email address.
Subject: Specify the subject of the email.
CSV File Input: Upload a CSV file with recipient email addresses.
Message: Input the body of the email.
CSV File Validation:

Validate email addresses using regular expressions.
Display counts of valid and invalid email addresses.
Email Sending:

The application includes a sendEmails() function intended to send emails.
Currently, it logs a message to the console, indicating the initiation of the email sending process.
UI Styling:

Designed using Tailwind CSS for a visually appealing and responsive layout.
Features gradient backgrounds and text gradients.
Usage Instructions
Enter sender's email address, subject, and email message in respective input fields.
Upload a CSV file with recipient email addresses.
Click the "Send Emails" button to initiate the email sending process (currently logging to the console).
Future Improvements
Implement Email Sending:

Connect to a backend service or email API for actual email sending.
User Authentication:

Enhance security by adding user authentication for email sending access.
Error Handling and Feedback:

Improve error handling during the email sending process.
Provide better user feedback on the progress.
Progress Indicator:

Implement a progress indicator for the email sending process.
User Experience:

Enhance overall user experience based on feedback.
Introduce additional features to meet user needs.
