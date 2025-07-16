# Landing-Page (ZapNote)

HTML Form Collection - Step-by-Step Instructions
Iteration 1: Initial Structure

Create a new directory called html-form-collection.
Within the html-form-collection directory, create an index.html file.
Fill it out with the usual boilerplate HTML and add an h1 heading "HTML Form Collection" to the body.
Add a brief paragraph explaining what this project is about: "A collection of HTML forms demonstrating different input types and validation techniques."

Iteration 2: Contact Form Page

Create a new directory within the html-form-collection directory and name it forms.
Create a new HTML file within the forms directory called contact.html. Be sure to include the usual boilerplate HTML.
For now, just include an h1 heading with "Contact Form" as its content.
Back in the index.html file, add a link to the contact form page. Under the <h1>HTML Form Collection</h1> heading, write out the link like so: <a href="forms/contact.html">Contact Form</a>.
Add a link back to the index page on your contact form page for easier navigation. Place this link at the top of your contact page:
html<a href="../index.html">← Back to Home</a>


Iteration 3: Contact Form Content
Your contact form page should have the following content:

Form Structure: Under the h1 heading, create a <form> element with action="#" and method="post".
Fieldset for Organization: Wrap your form inputs in a <fieldset> with a <legend> that says "Your Information".
Basic Input Fields: Add the following inputs with proper labels:

Name (text input, required)
Email (email input, required)
Phone (tel input, optional)
Subject (select dropdown with options: General Inquiry, Support, Business, Feedback)


Message Area: Add a <textarea> for the message with:

Label "Message"
Required attribute
Placeholder text
Rows="5" and cols="50"


Checkbox Option: Add a checkbox with label "Send me a copy of this message"
Submit Buttons: Add two buttons:

Submit button with text "Send Message"
Reset button with text "Clear Form"



Iteration 4: Survey Form Page

Create a new HTML file called survey.html in the forms directory.
Add the usual boilerplate HTML and an h1 heading "Customer Survey".
Add a link back to the index page: <a href="../index.html">← Back to Home</a>
Link to this new page from your index.html file.

Iteration 5: Survey Form Content
Your survey form should demonstrate more advanced input types:

Personal Information Fieldset:

Name (text, required)
Age (number input with min="13" max="120")
Email (email, required)


Service Experience Fieldset:

Service rating (range input from 1-10)
Visit date (date input)
Visit time (time input)


Radio Button Group (How did you hear about us?):

Social Media
Friend/Family
Search Engine
Advertisement
Other


Checkbox Group (Services used - select all that apply):

Consultation
Technical Support
Training
Maintenance


Textarea: "What can we improve?" (optional)
Final Question: Dropdown asking "Would you recommend us?" with options from "Definitely" to "Definitely Not"

Iteration 6: Registration Form Page

Create registration.html in the forms directory.
Add boilerplate HTML and h1 heading "User Registration".
Add navigation link back to home.
Link to this page from your index.html.

Iteration 7: Registration Form Content
This form should demonstrate validation attributes:

Account Information Fieldset:

Username (text, required, minlength="3", maxlength="20")
Email (email, required)
Password (password, required, minlength="8")
Confirm Password (password, required)


Personal Information Fieldset:

First Name (text, required)
Last Name (text, required)
Date of Birth (date, required)
Gender (radio buttons: Male, Female, Other, Prefer not to say)
Country (select dropdown)
Phone (tel, optional)
Website (url, optional)


Preferences Fieldset:

Interests (checkboxes: Technology, Sports, Music, Travel, Food)
Bio (textarea with maxlength="500")
Profile Picture (file input with accept="image/*")


Terms and Conditions:

Required checkbox for agreeing to terms
Optional checkbox for newsletter subscription



Iteration 8: Improve Navigation

Go back to your index.html file.
Instead of having all links on separate lines, put them in an unordered list:
html<ul>
  <li><a href="forms/contact.html">Contact Form</a></li>
  <li><a href="forms/survey.html">Customer Survey</a></li>
  <li><a href="forms/registration.html">User Registration</a></li>
</ul>

Add a brief description under each link explaining what that form demonstrates.

Iteration 9: Add Form Validation Testing

Go back to each form and test the following:

Try submitting empty required fields
Test email validation with invalid emails
Test number inputs with values outside min/max ranges
Test password minimum length requirements


Add helpful title attributes to inputs that have pattern validation.
Add placeholder text to inputs where it would be helpful.

Iteration 10: Final Touches

Add a footer to each page with: <footer><p>&copy; 2025 HTML Form Collection. Practice project for learning HTML forms.</p></footer>
Make sure all forms have proper name attributes on inputs for form submission.
Validate all your HTML using the W3C HTML Validator.
Test your forms in different browsers to see how they behave.

Project Structure When Complete:
html-form-collection/
├── index.html
└── forms/
    ├── contact.html
    ├── survey.html
    └── registration.html
Skills You'll Practice:

HTML form structure and semantics
Different input types (text, email, tel, password, number, date, time, range, url, file)
Form validation attributes (required, minlength, maxlength, min, max, pattern)
Proper label associations
Fieldsets and legends for grouping
Radio buttons and checkboxes
Select dropdowns and textareas
File uploads and accessibility considerations

Your forms won't be flashy without CSS, but focus on building them out with proper HTML structure and functionality first!