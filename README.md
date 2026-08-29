🎓 Student Performance Prediction System

<p align="center">
  <strong>A clean, responsive student information portal that connects directly to a prediction application.</strong>
</p><p align="center">
  <a href="https://mizanmohd039-a11y.github.io/html-login-student-performance/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-2563EB?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/mizanmohd039-a11y/html-login-student-performance">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository">
  </a>
</p><p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white" alt="GitHub Pages">
</p>---

🌐 Live Demo

👉 "Open Student Performance Prediction System →" (https://mizanmohd039-a11y.github.io/html-login-student-performance/)

Experience the interface directly in your browser — no installation required.

«Note: The GitHub Pages link renders the front-end interface. After submitting the form, the application redirects the entered student information to the connected Streamlit prediction application.»

---

✨ Overview

Student Performance Prediction System is a lightweight web interface designed as the entry point for a student performance prediction workflow.

The interface provides a simple and professional form where students can enter their basic academic information before continuing to the prediction application.

The current front-end collects:

- 👤 Student name
- 📧 Gmail address
- 📱 10-digit phone number
- 🎓 Engineering branch
- 📚 Course
- 📅 Academic year

After successful form validation, the JavaScript layer packages the information into URL parameters and redirects the user to the connected Streamlit application.

---

🚀 Key Features

Feature| Description
🎓 Student Portal| Clean entry point for the student prediction workflow
📝 Structured Form| Collects essential student and academic information
✅ Built-in Validation| Required fields, email validation, and 10-digit phone validation
📱 Responsive UI| Designed to work across desktop, tablet, and mobile screens
🎨 Modern Design| Gradient background, card layout, rounded controls, and visual hierarchy
🔗 Prediction Integration| Sends submitted information to the Streamlit prediction application
⚡ Lightweight| Simple HTML, CSS, and JavaScript implementation
🌐 GitHub Pages Ready| Can be deployed directly from the repository

---

🧭 How It Works

┌──────────────────────────────┐
│      🎓 Student Portal       │
│                              │
│  Enter student information   │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       ✅ Form Validation      │
│                              │
│  Name • Gmail • Phone        │
│  Branch • Course • Year      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       🔗 Data Transfer        │
│                              │
│   URLSearchParams generated  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│   🤖 Prediction Application   │
│        Streamlit App         │
└──────────────────────────────┘

Form Flow

1. 👤 Enter your full name
2. 📧 Enter your Gmail address
3. 📱 Enter your 10-digit phone number
4. 🎓 Select your branch
5. 📚 Select your course
6. 📅 Select your academic year
7. 🚀 Click Continue to Prediction
8. 🔗 The application transfers the entered values to the prediction app

---

🛠️ Tech Stack

Frontend

- HTML5 — semantic page structure and form elements
- CSS3 — responsive layout, gradients, cards, shadows, and form styling
- JavaScript — form handling, validation flow, URL parameter generation, and redirection

Deployment

- GitHub Pages — static front-end hosting
- Streamlit — connected prediction application

---

📁 Project Structure

html-login-student-performance/
│
├── 📄 index.html       # Main student information interface
├── 🎨 frontt.css       # Styling and responsive design
└── 📘 README.md        # Project documentation

---

💻 Run Locally

Because this is a lightweight front-end project, you can run it without installing a framework or package manager.

1. Clone the repository

git clone https://github.com/mizanmohd039-a11y/html-login-student-performance.git

2. Enter the project directory

cd html-login-student-performance

3. Open the application

Open "index.html" directly in your browser.

For a better development experience, you can also use a local development server such as VS Code Live Server.

---

🌍 GitHub Pages Deployment

The project is structured for static hosting because the main entry point is the root-level:

index.html

To deploy with GitHub Pages:

1. Open the repository on GitHub.
2. Go to Settings.
3. Open Pages.
4. Select Deploy from a branch.
5. Choose the "main" branch.
6. Select the root folder "/".
7. Save the configuration.
8. Open the generated GitHub Pages URL.

🔗 Project Live URL

https://mizanmohd039-a11y.github.io/html-login-student-performance/

---

🎨 UI Highlights

The interface uses a student-focused visual style featuring:

- 🎓 Graduation-cap visual identity
- 💙 Blue academic color palette
- 🌈 Soft gradient background
- 🪟 Elevated white form card
- 🔵 Rounded input controls
- ✨ Focus states for form fields
- 📱 Responsive layout
- 🚀 Prominent prediction action button

The current interface is implemented directly in the HTML with responsive styling support.

---

📋 Available Options

🎓 Branches

The form currently supports:

- Computer Science & Engineering
- Information Technology
- Electronics & Communication Engineering
- Electrical & Electronics Engineering
- Mechanical Engineering
- Civil Engineering

📚 Courses

- B.Tech
- BCA
- B.Sc
- MCA
- M.Tech

📅 Academic Years

- 1st Year
- 2nd Year
- 3rd Year
- 4th Year

---

🔗 Prediction Application Integration

When the user submits the form, JavaScript creates URL parameters containing:

name
email
phone
branch
course
year

The browser then redirects to the connected Streamlit application with those values attached to the URL.

This makes the repository act as the student-facing entry interface, while the prediction logic is handled by the connected application.

---

🔐 Important Note About Data

The current front-end passes submitted form values through the browser URL when redirecting to the prediction application.

Because URLs can potentially appear in browser history, logs, analytics systems, or referrer information, do not use this implementation for sensitive or production-grade personal data without adding an appropriate secure backend and data-handling strategy.

For a production deployment, consider:

- 🔒 HTTPS
- 🛡️ Server-side validation
- 🔑 Secure API communication
- 🚫 Avoiding sensitive information in query parameters
- 🗄️ Proper data storage policies
- 🔐 Authentication and authorization where required
- 📜 Appropriate privacy and consent practices

---

🔮 Future Improvements

Potential enhancements include:

- [ ] 🔐 Add secure authentication
- [ ] 🛡️ Move data transfer from URL parameters to a secure backend/API
- [ ] 📊 Add a dedicated prediction-result dashboard
- [ ] 📈 Display performance insights visually
- [ ] 💾 Add secure student record management
- [ ] 🌙 Add dark mode
- [ ] ♿ Improve accessibility and keyboard navigation
- [ ] 🌐 Add multilingual support
- [ ] 🧪 Add automated form testing
- [ ] 📱 Further optimize the mobile experience
- [ ] ⚡ Add loading and submission states
- [ ] 🔔 Add user-friendly validation messages

---

🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Contribution workflow

# Fork the repository

# Clone your fork
git clone https://github.com/YOUR-USERNAME/html-login-student-performance.git

# Create a feature branch
git checkout -b feature/your-feature

# Make your changes

# Commit
git add .
git commit -m "feat: describe your change"

# Push
git push origin feature/your-feature

Then open a Pull Request on GitHub.

💡 Good contribution ideas

- Improve accessibility
- Refine the responsive design
- Improve validation
- Add better error handling
- Improve documentation
- Add automated tests
- Improve the integration with the prediction backend

---

⭐ Support the Project

If you find this project useful or interesting:

⭐ Star the repository

🍴 Fork the project

🐛 Report issues

💡 Suggest improvements

🤝 Contribute

Every contribution helps improve the project!

---

📌 Repository

GitHub:
https://github.com/mizanmohd039-a11y/html-login-student-performance

Live Demo:
https://mizanmohd039-a11y.github.io/html-login-student-performance/

Prediction Application:
https://studentperformanceprediction-system-mohfrg8np6nsn4rivaiyek.streamlit.app/

---

👨‍💻 Author

Mizan Mohammad

Built with ❤️ using HTML, CSS & JavaScript.

<p align="center">
  <strong>🎓 Student Performance Prediction System</strong>
  <br>
  <sub>Simple interface • Responsive design • Prediction workflow</sub>
</p>---

<p align="center">
  <a href="https://mizanmohd039-a11y.github.io/html-login-student-performance/">
    🚀 <strong>View Live Project</strong>
  </a>
</p>
