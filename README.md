PROJECT NAME: VALENTINE WEBSITE
===============================

DESCRIPTION: A simple, single-page Valentine proposal website with smooth UI animations.
TECHNOLOGY: HTML, CSS, JavaScript
DEPLOYMENT: Vercel
FORM HANDLING: Formspree

-----------------------------------------------------------------------------------------------------------------------------

PROJECT OVERVIEW
This project is a lightweight Valentine proposal website built using a single HTML file. All styling, animations, 
and logic are contained within one file to ensure easy deployment and maintenance. The website collects user responses 
(Yes or No) using Formspree without requiring any backend server.

PROJECT STRUCTURE
valentine-site
│
└── index.html

Note: All HTML, CSS, JavaScript, animations, and Formspree integration are included inside the index.html file.

-----------------------------------------------------------------------------------------------------------------------------

DEPLOYMENT ON VERCEL (WITHOUT GITHUB)
1. Visit https://vercel.com
2. Sign in or create an account.
3. Click "Add New" → "Project".
4. Select "Deploy without Git".
5. Upload the folder containing index.html.
6. Click "Deploy".
7. After deployment, a live URL will be generated.
8. No build configuration is required.

-----------------------------------------------------------------------------------------------------------------------------

FORMSPREE INTEGRATION GUIDE
Formspree is used to collect and receive responses from the website.

STEP 1: Create a Formspree Account
- Visit https://formspree.io
- Sign up using your email address and verify your email.

STEP 2: Create a New Form
- Log in to the Formspree dashboard.
- Click "New Form".
- Create a basic form and save it.

STEP 3: Obtain Form ID
- After creating the form, a Form ID will be provided.
- Example Form ID: mgolegjw

STEP 4: Configure Form ID in index.html
- Define the Formspree ID in JavaScript as: FORMSPREE_ID = "mgolegjw"

STEP 5: Data Sent to Formspree
- When the user selects YES:
    * response: Yes
    * message: She said yes
    * timestamp: Current date and time
- When the user selects NO:
    * response: No
    * message: She said no
    * timestamp: Current date and time

All responses are available in the Formspree dashboard and via email notifications.

-----------------------------------------------------------------------------------------------------------------------------

IMPORTANT NOTES
- The main file must be named index.html.
- Test Formspree submission before sharing the website.
- Ensure the website works correctly on mobile devices.
- Keep animations lightweight for better performance.

PURPOSE OF PROJECT
This project is intended as a personal Valentine surprise focusing on:
- Simple and clear language.
- Attractive and modern UI.
- Smooth animations.
- Honest user feedback.
