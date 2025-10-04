# Email_Fetching-webiste
It's a realtime email fatching app too fetch the emails from the user mailbox.

**Email Handler and Dashboard**
A desktop application built with Python and Tkinter that allows you to fetch, filter, and analyze emails from an IMAP-enabled email account. It provides a user-friendly dashboard to view, search, sort, and export email data. If you choose not to connect to a live email account, the application will run using a built-in set of dummy emails for demonstration purposes.

**Features**
Connect to any IMAP Server: Securely fetch emails from your provider (e.g., Gmail, Outlook).

Date Range Filtering: Easily specify a start and end date to retrieve emails from a specific period.

Interactive Dashboard:

View emails in a clean, sortable, and filterable table.

Search across all email fields (sender, subject, body).

Sort by date or sender name.

Double-click an email to view its full content in a preview window.

Data Export: Export the fetched email data to a CSV file with a single click.

Light & Dark Themes: Toggle between light and dark mode for comfortable viewing.

Offline/Demo Mode: Runs with a pre-loaded set of dummy emails if no IMAP connection is enabled.

Settings Persistence: Remembers your last-used settings (server, email, etc.) for convenience.

Screenshots
(It is highly recommended to add screenshots of your application here to showcase the UI)

Main Window:

Dashboard View:

Requirements
The application is built using Python's standard tkinter library but uses a few external packages for an improved user experience.

Python 3.6+

tkcalendar: For a more user-friendly date picker widget.

ttkbootstrap: For modern and clean styling of the UI elements.

Installation & Usage
Clone the repository:

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
cd your-repository-name

Install the required packages:

pip install tkcalendar ttkbootstrap

Run the application:

python main.py

How to Use:

Select a Date Range: Choose a start and end date for the emails you want to fetch.

(Optional) Connect to Email:

Check the "Connect to Email Account" box.

Enter your IMAP server details, email address, and password.

Specify the mailbox/folder you want to search (e.g., "INBOX").

Fetch Emails: Click the "Fetch Emails" button. This will open the Dashboard window with the results.

Important Note for Gmail Users
If you are using a Gmail account, you cannot use your regular password directly in the application due to Google's security policies. You must:

Enable 2-Step Verification on your Google Account.

Generate an App Password specifically for this application.

Use the 16-character App Password in the password field instead of your normal login password.

You can find instructions on how to generate an App Password on Google's support page: Sign in with App Passwords.

Configuration
The application automatically creates an email_filter_settings.json file in the same directory to store your last-used configuration (server, email, mailbox, and date range). The password is not saved.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
