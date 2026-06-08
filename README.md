# Elevate Labs Web Development Internship - Task 6

## Contact Form Validation Using JavaScript

### Objective

Build a contact form with client-side validation for Name, Email, and Message fields using HTML, CSS, and JavaScript.

## Features

* Contact form with Name, Email, and Message fields
* Responsive and user-friendly interface
* Client-side form validation using JavaScript
* Email validation using Regular Expressions (Regex)
* Dynamic error messages for invalid inputs
* Success message displayed on valid submission
* Form reset after successful submission
* Prevents form submission when validation fails

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

## Project Structure

Task6/
├── email_validation_screenshot.png
├── empty_fields_validation_screenshot.png
├── index.html
├── page_screenshot.png
├── README.md
├── script.js
├── style.css
└── valid_form_screenshot.png

## Validation Rules

### Name

* Cannot be empty

### Email

* Cannot be empty
* Must follow a valid email format

### Message

* Cannot be empty

## Regex Used for Email Validation

```javascript
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
```

## Screenshots

### Contact Form UI

* page_screenshot.png

### Empty Fields Validation

* empty_fields_validation_screenshot.png

### Invalid Email Validation

* email_validation_screenshot.png

### Successful Form Submission

* valid_form_screenshot.png

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in any web browser.
4. Test the form validation functionality.

## Learning Outcomes

* Form handling in JavaScript
* Event handling using `addEventListener()`
* Using `event.preventDefault()`
* DOM manipulation
* Client-side validation
* Regular Expressions (Regex)
* Dynamic user feedback

## Author

**Nimisha Budati**

Submitted as part of the Elevate Labs Web Development Internship Program.
