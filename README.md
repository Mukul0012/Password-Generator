# 🔐 Password Generator

A simple and secure **password generator web application** that allows users to generate strong, random passwords based on their preferred requirements.

The application provides an easy-to-use interface for creating passwords with configurable character options.

---

## ✨ Features

* 🔑 Generate random passwords instantly
* 🔢 Customize password length
* 🔠 Include uppercase letters
* 🔡 Include lowercase letters
* 🔢 Include numbers
* 🔣 Include special characters
* 📋 Copy generated password to clipboard
* ⚡ Fast and lightweight interface
* 📱 Responsive design
* 🎨 Simple and user-friendly UI

---

## 🛠️ Tech Stack

* **HTML5** — Application structure
* **CSS3** — Styling and responsive design
* **JavaScript** — Password generation logic and DOM manipulation

---

## 📂 Project Structure

```text
Password-Generator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

The application generates a password by creating a character pool based on the user's selected options.

```text
User Input
    │
    ├── Password Length
    ├── Uppercase
    ├── Lowercase
    ├── Numbers
    └── Special Characters
            │
            ▼
     Character Pool
            │
            ▼
    Random Selection
            │
            ▼
    Generated Password
            │
            ▼
       Copy to Clipboard
```

### Password Generation Process

1. User selects the desired password length.
2. User chooses the character types to include.
3. JavaScript creates a character set based on those selections.
4. Characters are randomly selected from the available set.
5. The generated password is displayed to the user.
6. The user can copy the password to the clipboard.

---

## 🚀 Getting Started

### Prerequisites

No additional software or dependencies are required.

You only need a modern web browser.

### Clone the Repository

```bash
git clone https://github.com/Mukul0012/Password-Generator.git
```

### Navigate to the Project

```bash
cd Password-Generator
```

### Run the Application

Simply open:

```text
index.html
```

in your preferred browser.

Alternatively, you can use **VS Code Live Server** for local development.

---

## 🔒 Security Note

This application generates passwords **locally in the browser** and does not require a backend server or database.

Generated passwords should still be handled carefully. Avoid sharing passwords or storing them in insecure locations.

For highly sensitive accounts, consider using a reputable password manager with a cryptographically secure password generator.

---

## 🎯 Project Objectives

This project was built to practice:

* JavaScript fundamentals
* DOM manipulation
* Event handling
* Random value generation
* Conditional logic
* Clipboard API
* Responsive UI development
* Frontend project structure

---

## 🔮 Future Improvements

Potential improvements include:

* [ ] Password strength indicator
* [ ] Cryptographically secure random generation using Web Crypto API
* [ ] Password generation history
* [ ] One-click password regeneration
* [ ] Dark/light mode
* [ ] Custom character sets
* [ ] Exclude similar characters such as `O`, `0`, `l`, and `1`
* [ ] Password entropy estimation
* [ ] Improved accessibility
* [ ] Progressive Web App (PWA) support

---

## 🌐 Live Demo

**Live Demo:**
https://mukul0012.github.io/Password-Generator/

**GitHub Repository:**
https://github.com/Mukul0012/Password-Generator

---

## 👨‍💻 Author

### Mukul Bhalkar

Computer Engineering Student | Full-Stack Developer

* GitHub: https://github.com/Mukul0012

---

## 📄 License

This project is licensed under the **ISC License**.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

---

**Built with ❤️ using HTML, CSS and JavaScript.**
