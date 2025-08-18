# Skill Bank Website

This is a modern, responsive, and animated website for a fictional company called Skill Bank. The website allows users to submit a form with their personal details, current skills, and desired skills. The submitted form data is sent to the company's email.

## Features

- Clean and minimal layout with modern typography.
- Animated interactions for buttons, form fields, and section transitions.
- Fully responsive design (mobile, tablet, and desktop).
- Smooth scrolling and lightweight animations.
- Professional color palette.
- Animated hero section.
- Form with validation.
- Email integration using Formspree.
- Responsive navigation menu.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1.  Clone the repository.
2.  Open `index.html` in your browser.
### Email Submission Setup

To receive form submissions to your email, you need to use Formspree:

1.  **Create an Account**: Go to [Formspree.io](https://formspree.io/) and sign up for a free account.
2.  **Create a New Form**:
    *   Click the **+ New form** button.
    *   Name your form (e.g., "Skill Bank Website").
    *   Set the **recipient email** to `tylerhillary03@gmail.com`.
    *   Click **Create Form**.
3.  **Get Your Form ID**:
    *   After creating the form, you will be taken to the integration page.
    *   Copy the unique URL provided. It will look something like `https://formspree.io/f/xxxxxxxx`.
4.  **Update `index.html`**:
    *   Open the `index.html` file.
    *   Find the line with `action="https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID"`.
    *   Replace `REPLACE_WITH_YOUR_FORM_ID` with your actual Formspree form ID.

Once you've done this, all form submissions will be sent to your email in a professional, easy-to-read table format.
