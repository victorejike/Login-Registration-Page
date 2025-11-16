Book Flip Login & Registration Page
A modern, interactive login and registration page with a unique book flip animation and dark mode functionality.

https://img.shields.io/badge/Book%2520Flip-Login%2520Page-blue
https://img.shields.io/badge/Design-Responsive-green
https://img.shields.io/badge/Feature-Dark%2520Mode-orange

🌟 Features
Book Flip Animation: Smooth 3D page flip transition between login and registration forms

Dark Mode Toggle: Switch between light and dark themes with a single click

Responsive Design: Works perfectly on desktop, tablet, and mobile devices

Form Validation: Real-time validation with user-friendly error messages

Social Login Options: Google, Facebook, and Twitter login buttons

Modern UI: Gradient backgrounds, smooth animations, and interactive elements

Accessibility: Proper form labels and focus states

🚀 Live Demo
You can view the live demo by opening the index.html file in your web browser or click here for online demo.

📁 Project Structure
text
book-flip-login/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation (this file)
└── assets/             # Optional: For external resources
    ├── images/
    └── fonts/
🛠️ Technologies Used
HTML5: Semantic structure and forms

CSS3:

CSS Variables for theming

3D Transforms for book flip animation

Flexbox for layout

Gradient backgrounds and shadows

JavaScript:

Form handling and validation

Dark mode toggle functionality

Animation triggers

Font Awesome: Icons for UI elements

📱 Browser Compatibility
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

🎨 Customization
Colors
The project uses CSS custom properties for easy theming. Modify these variables in the :root selector:

css
:root {
    --primary: #8a2be2;      /* Main purple color */
    --secondary: #00bfff;    /* Main blue color */
    --bg-dark: #121212;      /* Dark mode background */
    --card-dark: #1e1e1e;    /* Dark mode card background */
    --text-dark: #f0f0f0;    /* Dark mode text color */
    --text-light: #333;      /* Light mode text color */
}
Animation Speed
Adjust the transition timing by modifying:

css
--transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
📋 Installation & Usage
Clone or Download the project files

Open index.html in your web browser

Interact with the login/registration forms

Toggle dark mode using the moon/sun button

Flip between forms using the "Sign Up" / "Sign In" links

🔧 Implementation Details
Book Flip Animation
The flip animation is achieved using:

CSS 3D transforms with perspective and transform-style: preserve-3d

backface-visibility: hidden to hide the reverse side

JavaScript class toggling for animation triggers

Dark Mode Implementation
CSS custom properties for dynamic theming

JavaScript class toggling on body element

Smooth transitions for all color changes

Form Validation
Client-side validation with custom error messages

Password strength checking (minimum 6 characters)

Password confirmation matching

Success/error message display system

📝 Code Overview
HTML Structure
html
<div class="container">
    <button class="theme-toggle">🌙</button>
    <div class="book" id="book">
        <div class="book-page front">Login Form</div>
        <div class="book-page back">Registration Form</div>
    </div>
</div>
Key JavaScript Functions
javascript
// Toggle book flip animation
book.classList.add('flipped');

// Toggle dark mode
body.classList.toggle('dark-mode');

// Show validation messages
showMessage(element, text, type);
🎯 Future Enhancements
Backend integration for actual user authentication

Password strength meter

Remember me functionality

Forgot password flow

Social media authentication integration

Multi-language support

Progressive Web App (PWA) features

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.