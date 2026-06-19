# Secure_Login_System
Overview of Secure Login System:

The Secure Login System is a web-based application developed using Python Flask, SQLite, and bcrypt to provide secure user authentication. The system allows users to register and log in using a username and password while ensuring that passwords are securely stored as hashed values rather than plain text.

The application implements essential security measures such as password hashing, input validation, SQL injection prevention through parameterized queries, and session management. After successful authentication, users can access a protected dashboard and securely log out of the system.

This project demonstrates the fundamental concepts of web application security and user authentication, helping protect user accounts from common attacks and unauthorized access.

Technologies Used:

The Secure Login System was developed using Python as the programming language and Flask as the web framework for handling routes, forms, and user interactions. SQLite was used as the database to store user information securely. bcrypt was used to hash passwords before storing them in the database, ensuring that passwords are not saved in plain text. HTML was used to create the user interface pages such as registration, login, and dashboard.

Conclusion:

The Secure Login System successfully provides a secure method for user registration and authentication. By implementing password hashing, input validation, SQL injection protection, and session management, the system enhances the security of user accounts and prevents unauthorized access. This project demonstrates the importance of secure authentication practices in web applications and serves as a foundation for developing more advanced security features in future applications.
