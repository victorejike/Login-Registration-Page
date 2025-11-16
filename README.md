📘 Book Flip Login & Registration UI
<div align="center"> <img src="https://img.shields.io/badge/Book%20Flip-Login%20Page-blueviolet?style=for-the-badge"> <img src="https://img.shields.io/badge/Design-Responsive-success?style=for-the-badge"> <img src="https://img.shields.io/badge/Feature-Dark%20Mode-orange?style=for-the-badge">

<br><br>

<h3>A Modern 3D Book-Style Authentication Interface</h3> <p> Beautiful login and registration pages with 3D flip animation,<br> dark/light mode, and a clean modern UI.<br> Built with <strong>HTML</strong>, <strong>CSS</strong>, and <strong>JavaScript</strong>. </p> <br>

<a href="#-preview">🎥 Preview</a> •
<a href="#-installation">📁 Installation</a> •
<a href="#-features">🎨 Features</a> •
<a href="#️-customization">🛠️ Customize</a>

</div>
🎥 Preview
<div align="center"> <table> <tr> <td><strong>Light Mode</strong></td> <td><strong>Dark Mode</strong></td> </tr> <tr> <td> <img src="https://via.placeholder.com/400x250/8a2be2/ffffff?text=Light+Mode+Login" width="400"> </td> <td> <img src="https://via.placeholder.com/400x250/121212/ffffff?text=Dark+Mode+Login" width="400"> </td> </tr> </table> </div>
✨ Features
🎯 Core Features

📖 3D Book Flip Animation — Smooth transition between login & register

🌙 Dark/Light Mode Toggle — Modern theme switch

📱 Fully Responsive — Works on all devices

🎨 Modern UI Design — Glassmorphism + gradients

🔐 Authentication Features

✔️ Real-time form validation

✔️ Password confirmation check

✔️ Email format validation

👥 Social login buttons included

⚡ Interactive Elements

✨ Hover animations

🎯 Input focus states

🔔 Toast notifications

🔄 Smooth page transitions

🚀 Installation
# Clone repository
git clone https://github.com/yourusername/book-flip-login.git

# Enter project folder
cd book-flip-login

# Open in browser
open index.html


Or simply:

Download index.html

Open it in a web browser

Done! 🎉

🛠️ Technology Stack
<div align="center">
Technology	Purpose
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">	Page structure
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">	Styling + animations
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">	Interactivity + validation
<img src="https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white">	Icons
</div>
🎨 Customization
🎨 Color Scheme
:root {
    --primary: #8a2be2;
    --secondary: #00bfff;
    --bg-dark: #121212;
    --card-dark: #1e1e1e;
    --text-dark: #f0f0f0;
}

⏳ Animation Speed
.book {
    transition: transform 1s ease-in-out;
}

📁 Project Structure
book-flip-login/
├── index.html
├── screenshot-light.png
├── screenshot-dark.png
└── README.md

🔧 Browser Compatibility
Browser	Version	Support
Chrome	60+	✅
Firefox	55+	✅
Safari	12+	✅
Edge	79+	✅
Internet Explorer	-	❌
🎯 Usage Examples
Basic HTML Structure
<div class="book" id="book">
    <div class="book-page front">...</div>
    <div class="book-page back">...</div>
</div>

JavaScript Integration
document.getElementById('book').classList.add('flipped');
document.body.classList.toggle('dark-mode');

🌟 Advanced Features
Backend Ready
loginForm.addEventListener('submit', async (e) => {
    e.preventDefault();
    const response = await fetch('/api/login', {
        method: 'POST',
        body: new FormData(loginForm)
    });

    if (response.ok) showMessage(loginMessage, 'Login successful!', 'success');
});

OAuth Ready

Google

Facebook

Twitter

🤝 Contributing
# Fork the repository
# Create feature branch
git checkout -b feature/my-feature

# Commit
git commit -m "Add new feature"

# Push
git push origin feature/my-feature