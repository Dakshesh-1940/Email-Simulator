# Email Simulator

A simple console-based Email Simulator built using Python and Object-Oriented Programming (OOP) principles.

## Features

* Send emails between users
* Receive emails in a personal inbox
* View a list of received emails
* Read full email contents
* Automatically mark emails as read
* Display email timestamps
* Delete emails from the inbox
* Handle invalid email selections gracefully

## Concepts Demonstrated

This project was built to practice:

* Classes and Objects
* Encapsulation
* Object Relationships
* Lists
* String Formatting
* Date and Time Handling
* Basic Input Validation
* Python OOP Design

## Project Structure

### Email Class

Represents an email message.

Attributes:

* Sender
* Receiver
* Subject
* Body
* Timestamp
* Read Status

Methods:

* `mark_as_read()`
* `display_full_email()`
* `__str__()`

### Inbox Class

Manages a user's emails.

Methods:

* `receive_email()`
* `list_emails()`
* `read_email()`
* `delete_email()`

### User Class

Represents a user who can send and receive emails.

Methods:

* `send_email()`
* `check_inbox()`
* `read_email()`
* `delete_email()`

## Example Workflow

1. Create users.
2. Send emails between users.
3. Check inbox contents.
4. Read specific emails.
5. Delete emails.
6. Verify inbox updates.

## Sample Output

```text
Email sent from Tory to Ramy!

Email sent from Ramy to Tory!


Ramy's Inbox:

Your Emails:
1. [Unread] From: Tory | Subject: Hello | Time: 2026-06-19 21:30

--- Email ---
From: Tory
To: Ramy
Subject: Hello
Received: 2026-06-19 21:30
Body: Hi Ramy, just saying hello!
------------

Email deleted.

Ramy's Inbox:
Your inbox is empty.
```

## How to Run

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project folder:

```bash
cd email-simulator
```

Run the program:

```bash
python main.py
```

## Future Improvements

* User login system
* Persistent storage using files or SQLite
* Search emails by sender or subject
* Email folders (Inbox, Sent, Trash)
* Email attachments
* Command-line menu interface
* GUI version using Tkinter or PyQt

## Author

Dinesh Kumar

Built as a Python OOP practice project.
