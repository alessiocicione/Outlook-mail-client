# Outlook-mail-client
Mail client for outlook implemented with python with built in spam detection system

in the project add empty folders named:
mail_ids,
content,
attachments

Required libraries:
shutil,
PyQt5,
numpy,
calendar,
email,
imaplib,
smtplib,
pickle,
sklearn

**Note on Authentication (as of 2025):**

Modern Outlook and Microsoft 365 accounts **now strictly require OAuth2** for secure login via applications.

This project's current implementation uses older protocols (like simple username/password via `imaplib` and `smtplib`) for demonstration purposes, as OAuth2 was not mandatory at the time of initial development.

**To use this client with a contemporary Outlook account, you must update the code to implement the full Microsoft Graph API's OAuth2 authorization flow.**
