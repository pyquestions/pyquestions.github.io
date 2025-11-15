
#  Contributing to PyQuestions

Thank you for considering contributing to **PyQuestions**!  
This project is community-driven, and your help makes it better.

---

## Ways You Can Contribute

- Add new questions & answers  
- Improve existing answers  
- Fix typos or formatting  
- Improve UI (CSS)  
- Improve functionality (JavaScript)  
- Suggest new features  
- Report bugs  

---

##  How to Contribute (Step-by-Step)

### 1. Fork the Repository

Click the **Fork** button on GitHub.

### 2. Clone Your Fork

````

git clone [https://github.com/](https://github.com/pyquestions/pyquestions.github.io)

```

### 3. Create a New Branch

```

git checkout -b feature-new-question

```

### 4. Make Your Changes  
For question additions, edit:

```

questions.json

````

Make sure IDs are unique.

---

## Question Format

Add questions like this:

```json
{
  "id": 10,
  "question": "What is a variable in Python?",
  "answer": "A variable stores data and is created by assigning a value to a name."
}
````

---

## Coding Guidelines

### JSON

* Use valid JSON
* Use double quotes `" "`
* No trailing commas

### HTML/CSS

* Keep it simple and readable
* Use semantic HTML
* Avoid large inline styles

### JavaScript

* Keep code clean and modular
* Use `const` and `let`
* Avoid unused variables

---

## Testing Your Changes

1. Open `index.html` in your browser
2. Confirm the site loads properly
3. Ensure your new Q&A appears

---

## Submit a Pull Request

Push your branch:

```
git push origin feature-new-question
```

Then open a **Pull Request** on GitHub:

* Give a clear title
* Describe your changes
* Link related issues if any

We’ll review it as soon as possible.

---

## Need Help?

Open an **Issue** in the repository anytime.
We’re happy to assist!

