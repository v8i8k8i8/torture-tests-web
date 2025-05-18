# torture-tests-web
Torture test suite for modern web apps — break it before users do.

The **QA Chaos Suite** is a brutally honest, unapologetically weird collection of test cases designed to push your web app to the brink of insanity.

This is not your typical happy-path test suite.  
It’s the **unholy checklist** of every bizarre, forgotten, browser-breaking scenario we’ve seen take down production.

From emoji floods to date field time travel to duplicate tab madness — this repo is where bad ideas become great tests.


## 🔥 Tests Included

| Test                     | Description                                         |
|--------------------------|-----------------------------------------------------|
| `emoji-input`            | Floods form fields with 500+ emojis.               |
| `rapid-clicks`           | Spam-clicks critical buttons at insane speed.      |
| `date-9999`              | Tests date inputs with far-future values.          |
| `duplicate-tabs`         | Performs actions in multiple tabs simultaneously.  |
| `cache-wipe`             | Clears cookies, cache, local storage mid-session.  |
| `file-overkill`          | Uploads massive files to test size limits.         |


---

🔬 Built with:  
- 🧪 Playwright (can easily adapt to Cypress or Puppeteer)  
- 💻 Browser-level chaos tools  
- ⚠️ A deep distrust of user input

---

📦 Perfect for:
- QA Engineers with a sense of humor  
- Devs who’ve been burned before  
- PMs who want to know “what could go wrong?”  
- Anyone who enjoys seeing Chrome cry

---

**Warning:** Running this suite may uncover bugs that lead to actual conversations with your dev team. Use responsibly.
## ⚙️ How to Run

```bash
npm install
npx playwright test

