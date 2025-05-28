*User Registration Form*
This project is a simple HTML user registration form with basic client-side validation implemented in JavaScript. It collects user credentials such as User ID, Password, and User Type for registration purposes.

*Features*
User-friendly registration form interface

Basic input fields: User ID, Password, and User Type
Client-side validation using JavaScript
Responsive and styled using internal CSS

![image alt](https://github.com/HemantGupta4909/dummy-project/blob/a368c5772c91eec0488676dab26f211aa791eb57/Screenshot%20(222).png)

*Form Fields*
User ID: Text input, minimum 3 characters required
Password: Password input, minimum 5 characters required
User Type: Dropdown with options: Student or Working Professional

![image alt](https://github.com/HemantGupta4909/dummy-project/blob/e8a9f59f4b029d8dd3e5da48ccdb58c6ab337f5a/Screenshot%20(223).png)

*Validation Logic*
Implemented in JavaScript via the validateForm() function:
Ensures User ID is at least 3 characters long
Ensures Password is at least 5 characters long
If validation fails, an alert message appears and the form is not submitted

![image alt](https://github.com/HemantGupta4909/dummy-project/blob/e8a9f59f4b029d8dd3e5da48ccdb58c6ab337f5a/Screenshot%20(224).png)

*Form Submission*
The form is designed to submit data to submit.csv using the POST method. This is likely intended for server-side processing. Note: Saving directly to a .csv file via POST requires server-side handling, which is not included in this code.

*Styling*
Background color of form: light purple
Inputs and dropdown are styled with consistent padding and spacing
Submit button styled with teal color and white text

