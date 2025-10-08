INFR3120 Portfolio Website Documentation
This document provides a detailed overview of the design, development, and validation process for my personal portfolio website
Student: Shariq Abdul-Wahid
Course: INFR3120 – Web and Scripting Programming

1. Project Access
You can view the live site and the source code here:
Live GitHub Pages Site: https://shariqabdulwahid.github.io/portfolio-site
GitHub Repository: [https://github.com/shariqabdulwahid/portfolio-site](https://github.com/shariqabdulwahid-stack/Portfolio)

2. Responsive Design and Structure
For this section, I built the entire site to be fully responsive using fluid design principles and media queries, strictly adhering to the course requirement that Flexbox is not used. Instead, I relied on fluid percentages and floats to control the layout across different devices.
To manage styles consistently, I implemented a dedicated CSS file structure for specific viewports:
Mobile: Styles apply up to max-width: 480px (managed by mobile.css).
Tablet: Screens between 481px – 768px (styles are handled within the desktop.css file via a media query).
Laptop/Desktop: Screens from 769px and above (managed by the primary desktop.css file).
This layered approach ensures that the layout, including column widths and stacking behavior, is accessible and readable regardless of the user’s device.

3. Advanced Styling: CSS3 Gradients
I incorporated both required gradient types to enhance the visual design and demonstrate competency with advanced CSS styling:
Linear Gradient (Home Page Body): I applied a subtle linear gradient to the body of the Home page (index.html) to provide visual depth and move away from a flat background.
Code: background: linear-gradient(to bottom, var(--light-blue), #90CAF9);
Angle Linear Gradient (Contact Button): I used a repeating angle linear gradient on the submit button on the Contact Me page (contact.html). This visual effect helps highlight the primary call-to-action button.
Code: background-image: repeating-linear-gradient(45deg, #2c89cc, var(--primary-blue) 10%, #1565C0 20%);

4. Consistent Color Scheme
I developed a cohesive and professional color palette using Adobe Color to ensure clarity and accessible contrast. I implemented this scheme using CSS variables within the base.css file for maximum efficiency and consistency:
CSS Variable
Hex Value
Role/Description
--primary-blue
#0D47A1
Deep Blue (Headings, Main BG)
--secondary-blue
#1976D2
Vibrant Blue (Buttons, Accents)
--light-blue
#E3F2FD
Very Light Blue (Base background)
--text-dark
#212121
Dark Text
--text-light
#FFFFFF
White Text
--accent-light
#64B5F6
Lighter blue for card BG/Hover

Source Inspiration: The concept of using CSS variables was directly inspired by the W3Schools’ CSS Variables Guide: https://www.w3schools.com/css/css3_variables.asp


5. External Code Usage
All development code is original or adapted from class demos. The only external technology I used was for form handling:
Form Submission via FormSubmit
Source: https://formsubmit.co
Purpose: I chose this service because it was necessary to securely send form data to an email address without requiring any server-side scripting
This technique is fully documented in contact.html and comprises less than 10% of the total code.
All external code is fully understood and commented for clarity in the file.


6. Validation & Testing
I thoroughly tested and validated all pages to ensure quality and compliance using the following industry tools:
HTML Validation: W3C Markup Validator (https://validator.w3.org/)
CSS Validation: W3C CSS Validator (https://jigsaw.w3.org/css-validator/)
Link Checker: W3C Link Checker (https://validator.w3.org/checklink)
Accessibility: WAVE WebAIM (https://wave.webaim.org/)
Spell Check: Verified using Grammarly



7. Version Control
I managed the project using a public GitHub repository with an organized folder structure. The commit history clearly demonstrates my progress throughout the development process, including major milestones:
Initial layout setup
Page content addition
Styling and responsiveness implementation
Final validation and README documentation

8. Pages and Files Included
I organized the project using the following files:
index.html
The Home page with primary navigation and an introduction.

about.html
Contains a personal photo, introductory text, and an embedded video (with poster and controls).

projects.html
Displays descriptions for 5 academic projects.

contact.html
The validated contact form using FormSubmit.

base.css
Global styles and definitions for all CSS variables.

mobile.css
Specific styles targeting mobile devices (up to 480px).

desktop.css
Styles covering tablet, laptop, and desktop viewports (769px and above).


