# Mess-Feedback-System

It looks like you have provided a detailed description of your project, which involves creating a mess feedback system for both mess managers and students. This system will allow users to provide feedback on various aspects of the mess and enable mess managers to analyze the feedback data. Here's a basic README outline you could use to summarize your project:

---

# Mess Feedback System

## Description
The Mess Feedback System is designed to streamline the process of giving and viewing feedback related to mess management. This system eliminates the need for traditional physical registers by offering an online platform for both mess managers and students. Students can provide feedback on food quality, cleanliness, and other aspects, while mess managers can access and analyze the feedback data to improve the overall mess experience.

### Entities
1. **User**: Students who provide feedback on mess-related aspects.
2. **Mess Manager**: Responsible for analyzing feedback data and implementing improvements.

### Modules
1. **User Registration**: New users can register by providing a unique username, valid email, and password. Duplicate usernames are not allowed.
2. **User Login**: Registered users can log in using their credentials to access the feedback system.
3. **Feedback Page**: Logged-in users can submit feedback on various aspects of the mess, specifying the date of their feedback.
4. **About Us**: A static webpage showcasing information about the mess team.
5. **Contact Us**: A static webpage displaying contact information for the mess.

### Libraries and Functions Used
- **Django render**: Used for rendering HTML pages.
- **django.core.mail**: Used to send emails, especially for forgot password functionality.
- Various functions for user registration, login, password reset, feedback submission, and data retrieval.

## Achievements
- Successful user signup and login process.
- Successful feedback submission to mess managers.
- Efficient storage and retrieval of feedback data from the database.
- Implementation of a password reset link for users.

## Possible Future Work
- Implement input sanitization to prevent SQL injection vulnerabilities.
- Develop a mechanism to delete user data from the database for privacy concerns.

## Compilation Instructions
1. Run the command: `python3 manage.py runserver`
2. Open your browser and go to `http://127.0.0.1:8000/login`

## Flow
1. User registration and login.
2. User provides feedback on the mess system.
3. Mess managers analyze feedback data for improvements.

---

Feel free to customize and expand upon this README template to provide more specific details about your project's features, technology stack, and any other relevant information.
