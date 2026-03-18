# JS Quiz
 
> An interactive multiple-choice quiz app — questions load dynamically, answers are validated instantly, and a score screen is shown at the end.
 
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

![Project Preview](https://github.com/Luan-Neumann-Dev/QuizzJS/assets/155394874/ae0e0848-4f46-4cc6-9ab6-f66183e5822b)
![Project Preview](https://github.com/Luan-Neumann-Dev/QuizzJS/assets/155394874/7a616e28-96f1-4435-a6d9-e5f42d9b945c)
![Project Preview](https://github.com/Luan-Neumann-Dev/QuizzJS/assets/155394874/021363ef-f3c2-46a2-9207-683c736cc6d4)

## 🎯 About
 
JS Quiz is a browser-based multiple-choice quiz focused on programming trivia. Questions and answer options are stored as a JavaScript array of objects and rendered dynamically via DOM manipulation — no page reloads, no frameworks. After all questions are answered, a score screen displays the percentage and number of correct answers, with the option to restart.

## ✨ Features
 
- 🧩 **Dynamic Question Rendering** - Questions and answers are built from a data array and injected into the DOM each round
- ✅ **Instant Answer Feedback** - Correct and wrong answers are highlighted immediately after selection
- ⏱️ **Auto-advance** - A 1.5s delay after each answer lets the user read the feedback before moving on
- 📊 **Score Screen** - Final screen shows percentage score and correct answer count, with a restart button
- 📱 **Responsive** - Layout adapts to mobile screens via media queries
 
## 🛠️ Built With
 
- **HTML5** - Semantic structure with a hidden answer template cloned dynamically per question
- **CSS3** - Dark theme, card layout, color-coded answer feedback, and responsive media queries
- **JavaScript** - Data-driven question rendering, DOM cloning, `setTimeout` for timed transitions, and score calculation
 
## 🚀 Getting Started
 
### Prerequisites
 
- A modern web browser (Chrome, Firefox, Safari, Edge)
 
### Installation
 
```bash
# Clone the repository
git clone https://github.com/Luan-Neumann-Dev/js-quiz.git
 
# Navigate to project directory
cd js-quiz
 
# Open in browser
open index.html
```
 
## 📁 Project Structure
 
```
js-quiz/
├── index.html          # Quiz markup — question container, score screen, and answer template
├── css/
│   └── styles.css      # Dark theme, card layout, answer states, and responsive styles
└── js/
    └── scripts.js      # Quiz data, dynamic rendering, answer checking, and score logic
```
 
## 🎓 What I Learned
 
- Driving UI entirely from a JavaScript data structure (array of question objects)
- Using `cloneNode(true)` to replicate a hidden HTML template for each answer button
- Using `data attributes` (via `setAttribute`) to store correct/wrong metadata on DOM elements
- Controlling flow with `setTimeout` to create timed transitions between questions
 
## 📝 Notes
 
- This is a **frontend-only** educational project
- Questions are hardcoded in the JavaScript file — easy to extend by adding objects to the `questions` array
- No external libraries or frameworks used
 
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
## 👤 Author
 
**Luan Neumann**
 
- LinkedIn: [Luan-Neumann-Dev](https://www.linkedin.com/in/luan-henrique-neumann-dev/)
- GitHub: [@luan-neumann-dev](https://github.com/Luan-Neumann-Dev)
 
---
 
⭐ If you found this project helpful, consider giving it a star!
