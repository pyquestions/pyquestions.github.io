
# PyQuestions – GitHub Pages Q&A Platform

[![GitHub Pages](https://img.shields.io/badge/Live_Site-PyQuestions-blue?logo=github)](https://pyquestions.github.io/)
![License](https://img.shields.io/badge/License-MIT-green)
![Stars](https://img.shields.io/github/stars/pyquestions/pyquestions.github.io?style=social)

PyQuestions is an open, lightweight **static Q&A website** built with HTML, CSS, and JavaScript and hosted on **GitHub Pages**.

It provides a clean and fast interface for browsing coding questions and answers stored in a simple JSON file.

---

## Features

- Fast static site (no backend or database required)  
- Questions and answers stored in `questions.json`  
- Search and filtering support (upcoming)  
- Simple, responsive, and clean UI  
- Easy contributions through Pull Requests  
- Hosted on GitHub Pages  

---

## Project Structure

```

pyquestions.github.io/
│
├── index.html        # Main website page
├── styles.css        # UI styles & layout
├── index.js          # Client-side logic
├── questions.json    # List of all questions & answers
├── LICENSE           # MIT License
└── README.md         # Project documentation

````

---

## How to Add or Edit Questions

All Q&A content is stored in `questions.json`.

Example:

```json
[
  {
    "id": 1,
    "question": "What is Python?",
    "answer": "Python is a high-level, interpreted programming language."
  }
]
````

### To add a question:

1. Edit `questions.json`
2. Add a new object with `id`, `question`, `answer`
3. Submit a Pull Request

---

##  Contributing

We welcome contributions!
You can help by:

* Adding new programming questions
* Improving existing answers
* Enhancing UI / styling
* Improving JavaScript features
* Reporting bugs or issues

👉 See **CONTRIBUTING.md** for full contributor guidelines.

---

## Run Locally

1. Clone the repository:

```
git clone https://github.com/pyquestions/pyquestions.github.io
```

2. Open `index.html` in your browser
3. No server or build tools required

---

## Tags / Keywords

```
Q&A, Coding Questions, Python Questions, Interview Prep, GitHub Pages,
Programming Help, HTML CSS JS, Static Website, JSON Data, Developer Resources
```

---

## License

Released under the **MIT License**.
You are free to use, modify, and distribute this project.

