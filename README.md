# CopilotFixTheCode

# 🚀 GitHub Copilot Hack Session

## 🧠 Theme: "Refactor & Test — Building Confidence with Copilot"

### 🎯 Objective
Participants will use GitHub Copilot's **Ask**, **Edit**, and **Agent** modes to:
- Understand and debug code.
- Refactor to improve quality and security.
- Add unit tests using AI assistance.

---

## 🕐 Agenda (1–2 hours)

### 🔹 Part 1: Introduction (10 mins)
- Overview of GitHub Copilot Modes:
  - **Ask**: Understand code, clarify bugs, get suggestions.
  - **Edit**: Refactor, document, and fix code.
  - **Agents**: Achieve complex goals (secure code, add logging, etc).
- Explain language-independence of session.

### 🔹 Part 2: Live Demo (15–20 mins)
**Examples in Python & JavaScript:**

#### 🔧 Example (Python)
```python
# Bad input sanitizer
# Task: Fix, explain, and test this

def sanitize_input(user_input):
    return user_input.strip().lower.replace("<", "").replace(">", "")
```

- Use Copilot Ask: "What's wrong with this code?"
- Use Copilot Edit: "Fix this code to avoid injection risks."
- Use Copilot Agent: "Make this production ready with logging and error handling."

#### 🔧 Example (JavaScript)
```javascript
// Faulty email validator
function isValidEmail(email) {
    return email.includes("@") && email.includes(".");
}
```
- Repeat Ask, Edit, Agent.

### 🔹 Part 3: Hack Time (20–30 mins)
**Choose your language**
- Python, JavaScript, TypeScript, Java, C#, etc.

**Choose a problem:**
- Input sanitizer
- Password strength checker
- Simple file reader
- String transformer (camelCase, snake_case)

**Tasks:**
1. Use Copilot Ask to understand.
2. Use Copilot Edit to refactor/fix.
3. Use Copilot Agent to add production features.
4. Use Copilot to generate tests.

### 🔹 Part 4: Testing with Copilot (15–20 mins)
- Ask: "Write unit tests for this function."
- Improve: "Add negative test cases."
- Challenge: "Convert to parameterized tests."
- Optionally run tests with pytest, JUnit, Jest, etc.

### 🔹 Part 5: Demos & Wrap (15 mins)
- Volunteer sharing.
- Recap:
  - How each mode helped.
  - Where Copilot accelerated dev/test workflow.
- Feedback poll.

---

## 📂 GitHub Repo Structure
```
📁 copilot-hack-session
├── README.md (this guide)
├── problems
│   ├── input_sanitizer.py
│   ├── email_validator.js
│   ├── password_checker.java
│   └── csv_parser.cs
└── test_templates
    ├── test_input_sanitizer.py
    └── test_email_validator.test.js
```

---

## 📌 Prompt Cheat Sheet
- "What does this function do?"
- "Is this secure?"
- "Refactor this for readability."
- "Add input validation."
- "Write unit tests with edge cases."
- "Mock external API call in test."
- "Add docstring."
- "Make this class thread-safe."

---

## 🧠 Tips
- Keep prompts short and natural.
- Highlight code + right-click to activate Ask/Edit.
- Use GitHub Copilot Chat in the sidebar for deeper interaction.

---

## 🗳️ Poll (Optional)
- Which Copilot feature did you use most? Ask / Edit / Agent / Tests
- How confident are you now writing/refactoring code with Copilot?

---

Let’s build smarter, together! 💻✨
