# ⏳ Time Traveler

A fun **vanilla JavaScript** experiment that explores **time dilation** and speculative futures.

Time Traveler allows a user to choose how long they travel for, how fast they move relative to the speed of light, and the *style* of the response. The app simulates a journey through space and then presents a **Captain’s Log** generated via the **ChatGPT API**, describing what the world might be like when the traveler returns to Earth.

---

## 🚀 Overview

This project combines physics-inspired calculations with generative AI to create an interactive, narrative-driven experience.

At a high level, the app:

1. Accepts user input (travel time, speed, response style)
2. Calculates a return year based on **relativistic time dilation**
3. Displays a visual “travel through space” sequence
4. Requests a narrative response from the ChatGPT API
5. Presents the result as a **Captain’s Log** from the future

The goal is not scientific precision, but an engaging way to explore the *idea* of relativistic travel and its consequences.

---

## ✨ Features

* User-defined travel duration (years)
* Speed selection as a percentage of the speed of light
* Time dilation–based return year calculation
* Animated or visual travel sequence
* AI-generated **Captain’s Log** narrative
* Multiple response styles (e.g. serious, optimistic, dystopian, humorous)

---

## 🧠 Concepts Explored

* **Time dilation** and relativistic effects
* Mapping mathematical output to narrative outcomes
* Prompting and consuming the ChatGPT API
* Asynchronous JavaScript and API handling
* UI state transitions (input → travel → result)

---

## 🛠️ Built With

* **Vanilla JavaScript (ES6+)**
* **HTML5**
* **CSS3**
* **ChatGPT API** for narrative generation

No frontend frameworks are used.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/time-traveler.git
cd time-traveler
```

### API Setup

This project requires access to the **ChatGPT API**.

1. Create an API key from OpenAI
2. Add the key to your project (e.g. via environment variables or a config file)

> ⚠️ **Do not commit API keys to source control**

---

## ▶️ Running the Project

This project does not require a build step.

Open `index.html` in your browser, or use a local server:

```bash
npx serve
```

---

## 📁 Project Structure

```
/
├── index.html
├── styles.css
├── script.js
├── api/           # API interaction logic (if separated)
└── assets/        # Visuals / animations
```

---

## 📓 Captain’s Log

Each journey ends with a generated **Captain’s Log**, written from the perspective of a traveler returning to Earth after decades, centuries, or millennia have passed.

The content of the log is influenced by:

* Calculated return year
* Selected response style
* The idea of societal, technological, and environmental change

Every run produces a unique outcome.

---

## 📌 Notes

* This is a **creative and experimental project**
* Physics concepts are simplified for accessibility and fun
* AI responses are speculative and fictional

---

## 🛣️ Future Ideas

* Visual timeline of Earth history skipped
* More detailed relativistic calculations
* Save and compare past journeys
* Additional narrative roles beyond Captain’s Log

---

## 📫 Contact

For feedback or discussion, reach out via GitHub:

🔗 [https://github.com/your-username](https://github.com/your-username)

---

⭐ A playful mix of physics, programming, and speculative storytelling.
