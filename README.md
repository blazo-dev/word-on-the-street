# 🟨 Word on the Street 🎮

A console-based word guessing game made with Node.js.  
Try to guess a secret programming word one letter at a time — but be careful, you only get **5 lives**!

> 🧩 **This project was developed as part of the** > **Workforce Opportunity Services (WOS) in partnership with Auto Club Enterprises (ACE)**
> A 14-week intensive initiative that combines enterprise-level technical training, hands-on project work, and agile team simulations.

---

## 🧩 Game Description

This game randomly selects a programming-related word such as `function`, `array`, or `closure`.  
You must guess the word one letter at a time. For every incorrect guess, you lose a life.

**Features:**

-   No external dependencies
-   Built using only Node.js core modules
-   Colorful console messages and emojis
-   Auto-restart after win or loss

---

## 🚀 Getting Started

### Prerequisites

-   [Node.js](https://nodejs.org/) v18 or higher (for `readline/promises`)

### Installation

Clone this repository:

```bash
git clone https://github.com/blazo-dev/word-on-the-street.git
cd word-on-the-street
```

### Run the game

```bash
npm start
```

---

## 🎮 How to Play

-   You'll see a hidden word represented by underscores.
-   Type a letter to guess.
-   You have **5 lives**.
-   Repeated wrong guesses cost a life.
-   You can type `0` at any time to exit.

---

## 🛠️ Project Structure

This is a single-file project with no dependencies:

-   `index.js`: Main game logic

---

## 📷 Example Gameplay

```bash
🟨🎮  Welcome to Word on the Street! 🎮🟨

🔤 Guess the secret programming word one letter at a time.
❌ You have 5 lives. Wrong guesses cost a life.

🧠 Word: _ _ _ _ _ _ _
❓ Wrong Letters:
❤️  Lives Remaining: 5

👉 Enter your guess (or type 0 to exit): a
🧠 Word: _ A _ A _ _ _
❓ Wrong Letters:
❤️  Lives Remaining: 5
```

---

## 📄 License

This project is open-source and free to use.

---

## 🙌 Acknowledgements

[**Workforce Opportunity Services (WOS)**](https://www.linkedin.com/company/workforce-opportunity-services)
[**Auto Club Enterprises (ACE)**](https://www.linkedin.com/company/aaa-auto-club-enterprises/).

Created with 💻 and ☕ by [Bryan Lazo](https://github.com/blazo-dev).
