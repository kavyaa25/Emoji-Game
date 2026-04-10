# 🎮 Emoji Memory Game – React.js

A fun and interactive **Emoji Memory Game** built using **React.js and CSS**, where users must click unique emojis without repeating any to win the game.

---

## 🚀 Live Demo

*(Add your deployed link here – Vercel / Netlify)*

---

## 📌 Overview

This is a **memory-based game** that tests the user’s ability to remember previously clicked emojis.
The game becomes challenging as emojis **shuffle after every click**, creating a dynamic user experience.

---

## 🎯 Why I Built This Project

* To understand **React state management**
* To practice **event handling and game logic**
* To build an **interactive and dynamic UI**
* To improve **problem-solving and logic-building skills**

---

## 🖼️ Project Preview

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

---

## 🛠️ Tech Stack

* **Frontend:** React.js (Class Components)
* **Styling:** CSS (Flexbox, Responsive Design)

---

## ✨ Features

* 🎯 Click each emoji only once to win
* 🔀 Emojis shuffle after every click
* 📊 Displays **Score & Top Score**
* 🏆 Win / ❌ Lose screen
* 🔁 “Play Again” functionality
* 📱 Fully responsive UI

---

## ⚙️ How I Implemented This Project

### 1. Component-Based Architecture

* Split the app into reusable components:

  * EmojiGame (Main logic)
  * EmojiCard (Individual emoji)
  * NavBar (Score display)
  * WinOrLoseCard (Result screen)

---

### 2. State Management

Used React state to manage:

* `clickedEmojiList` → tracks clicked emojis
* `topScore` → highest score
* `status` → game running or ended

---

### 3. Core Game Logic

* When an emoji is clicked:

  * If already clicked → Game Over
  * If not → Add to list & increase score

---

### 4. Winning Condition

* If all emojis are clicked without repetition → User Wins

---

### 5. Shuffle Logic

* After every click, emojis are shuffled using:

  ```js
  array.sort(() => Math.random() - 0.5)
  ```
* This increases difficulty and engagement

---

### 6. Event Handling

* Handled click events in EmojiCard
* Passed handler function from parent component
* Reset game using “Play Again” button

---

### 7. Dynamic UI Updates

* Score updates in real-time
* Conditional rendering for:

  * Game screen
  * Win/Lose screen

---

### 8. UI & Responsiveness

* Used **CSS Flexbox** for layout
* Designed a clean and responsive interface
* Works across mobile and desktop devices

---

## 📂 Folder Structure

```bash
src/
│
├── components/
│   ├── EmojiGame/
│   ├── EmojiCard/
│   ├── NavBar/
│   └── WinOrLoseCard/
│
├── App.js
└── index.js
```

---

## 🧠 Key Learnings

* React **state management**
* Handling **user interactions**
* Implementing **game logic**
* **Component-based architecture**
* Building **responsive UI**

---

## 📈 Future Improvements

* Add timer ⏱️
* Add difficulty levels 🎯
* Add sound effects 🔊
* Convert to Hooks ⚛️

---

## 📌 Final Summary

**This Emoji Memory Game demonstrates React state management, event handling, and dynamic UI updates by building an interactive and engaging game.**

---
