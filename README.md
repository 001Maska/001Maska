## Hi there 👋

Portfolio Website
A modern, responsive portfolio website showcasing my web development skills and projects. Built with clean HTML, CSS, and JavaScript featuring a dark brutalist aesthetic with smooth animations.

 Features

Responsive Design - Fully optimized for desktop, tablet, and mobile devices
Modern UI - Dark theme with vibrant accent colors and smooth animations
Fast Loading - Lightweight, no external dependencies except Google Fonts
Smooth Scrolling - Enhanced navigation with scroll-triggered animations
SEO Friendly - Semantic HTML structure for better search engine visibility
Accessibility - Clean code with proper contrast ratios and readable fonts


🛠️ Built With

HTML5 - Semantic markup structure
CSS3 - Custom animations, gradients, and responsive layout
JavaScript - Smooth scrolling and intersection observer animations
Google Fonts - DM Sans & JetBrains Mono

📋 Sections

Hero - Introduction with call-to-action buttons
About - Brief professional summary
Tech Stack - Skills organized by category (Frontend, Backend, Tools)
Projects - Featured projects with descriptions and links
Process - My development workflow
Contact - Links to email, GitHub, and LinkedIn



Color Palette
cssPrimary Background: #0a0a0a
Card Background: #121212
Accent Color: #00ff88
Text Primary: #ffffff
Text Secondary: #a0a0a0
Border: #252525
📦 Installation & Setup

Clone the repository

bash   git clone https://github.com/your-username/portfolio.git

Navigate to the project directory

bash   cd portfolio

Open the file

Simply open portfolio.html in your browser
Or use a local server:



bash     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve

View in browser

Navigate to http://localhost:8000



🔧 Customization
Update Personal Information

Contact Details (Line ~550)

html   <a href="mailto:your.email@example.com" class="contact-btn">Email</a>
   <a href="https://github.com/yourusername" target="_blank" class="contact-btn">GitHub</a>
   <a href="https://linkedin.com/in/yourusername" target="_blank" class="contact-btn">LinkedIn</a>

Projects Section (Line ~380)

Update project titles, descriptions, and links
Add your actual GitHub repositories and live demo URLs


About Section (Line ~270)

Customize your professional bio



Change Colors
Update CSS variables in the :root section (Line ~10):
css:root {
    --accent: #00ff88;  /* Change accent color */
    --bg-dark: #0a0a0a; /* Change background */
}
Add Your Logo
Replace the greeting text with your logo:
html<img src="path/to/your/logo.png" alt="Logo" class="logo">
📱 Responsive Breakpoints

Desktop: 1200px+
Tablet: 768px - 1199px
Mobile: < 768px

🚀 Deployment
GitHub Pages

Rename portfolio.html to index.html
Create a new repository named your-username.github.io
Push your code:

bash   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
