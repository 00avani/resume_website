
Welcome to the GitHub repository for my personal resume website! This site showcases my academic journey, achievements, hobbies, and contact information as a BBA student at the Indian Institute of Management Bangalore. Built with HTML and CSS, the website features a clean, responsive design with a modern aesthetic, optimized for global accessibility via GitHub Pages.
Features

Responsive Layout: Adapts seamlessly to desktops, tablets, and mobile devices.
Modern Design: Uses Roboto font, a cohesive color scheme, and a prominent profile picture.
Structured Content: Includes sections for About Me, Education, Achievements, Hobbies, and a Contact form.
Custom Styling: Enhanced lists and emphasized text for better readability.
Global Hosting: Deployed on GitHub Pages with Cloudflare’s CDN for fast worldwide access.

File Structure

index.html: The main HTML file containing the website’s structure and content.
style.css: The CSS file defining styles, layout, and responsiveness.
avani-profile.png: The profile picture displayed in the hero section.

Prerequisites

A GitHub account (github.com).
A web browser (e.g., Chrome, Firefox) for testing.
Optional: Git installed locally for cloning and managing the repository (Git Download).



Test the Website:

Visited and tested the provided URL to ensure the site loads correctly.
Also,Checking that the profile picture displays, text is readable, and the layout is responsive on mobile devices.


Usage

Viewing: Accessed the live site at https://00avani.github.io/resume_website/.
Edited Content:
Updated index.html to modify text (e.g., About Me, Education).
Replaced avani-profile.png with a new image (recommended: 250x250px, PNG format).
Commit changes:git add .
git commit -m "Update content"
git push origin main



Styling:
Edited style.css to change colors (e.g., #fdf6e3 for background), fonts, or layout.
Example: Adjust .profile-pic for a different image size.


Testing Responsiveness:
Used browser developer tools (F12 > Toggle Device Toolbar) to simulate various screen sizes.

Customization

Profile Picture: Changed the src attribute in index.html’s <img> tag to a new image file.
Colors: Modified style.css (e.g., change #004080 for headings or #fdf6e3 for the body background).
Fonts: Updated the Google Fonts link in index.html (e.g., to Open Sans) and adjusted font-family in style.css.
New Sections: Added sections (e.g., Portfolio) by copying the <section> structure in index.html and styling in style.css.
Contact Form: The form is static. To make it functional, integrated a service like Formspree:<form action="https://formspree.io/your-email" method="POST">

Updated input name attributes and signed up at formspree.io.

Notes
Ensuring avani-profile.png is in the root directory, or updated the image path in index.html.
The contact form requires a backend service for functionality (e.g., Formspree, Netlify Forms).
Optimized avani-profile.png with tools like TinyPNG to reduce load times.
For SEO, added meta tags in index.html:<meta name="description" content="Avani Pandya's resume website, showcasing education and achievements.">
<meta name="keywords" content="Avani Pandya, resume, BBA, IIM Bangalore">
