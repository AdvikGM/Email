Email Simulator

A simple Python-based email simulator built using Object-Oriented Programming (OOP).
This project demonstrates how users can send, receive, read, list, and delete emails using custom classes.

Features
Create users with their own inboxes
Send emails between users
Automatically store timestamps for emails
Mark emails as read
Display full email details
List all emails in an inbox
Delete emails from inbox
Object-oriented design using classes and methods
Classes Used
Email

Represents an email message.

Attributes
sender
receiver
subject
body
read
timestamp

Methods
mark_as_read()
display_full_email()
__str__()
Inbox

Stores and manages emails for a user.

Methods

receive_email(email)
list_emails()
read_email(index)
delete_email(index)
User

Represents a user with an inbox.

Methods

send_email(receiver, subject, body)
check_inbox()
read_email(index)
delete_email(index)
Example Workflow
Create users
Send emails
Check inbox
Read email
Delete email
View updated inbox
