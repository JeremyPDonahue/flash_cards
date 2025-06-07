# 🃏 Local Flashcard App

This is a simple, self-contained web app that lets you generate and flip through flashcards using your browser. No tracking, no accounts — just open the HTML file and go.

---

## 🚀 How to Use

1. **Open the HTML File**
   - Download or clone this repo
   - Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)

2. **Enter Flashcards**
   - In the textarea, paste question-answer pairs using the following format:

     ```
     Q: What is Terraform used for?
     A: Infrastructure as Code.

     Q: What does outputs.tf do?
     A: It defines values a module returns to its caller.
     ```

3. **Click "Generate Flashcards"**
   - This will parse the input and build interactive flashcards

4. **Click the Card to Flip**
   - First click: reveals the answer
   - Second click: moves to the next (randomized) card

5. **Cycle Infinitely**
   - Once you reach the end of the flashcards, the cycle repeats from the beginning

---

## 🎨 Features

- Clean dark mode UI for reduced eye strain
- Mobile and desktop friendly
- Click-to-flip flashcard animation
- Randomized shuffle each time you generate
- No tracking, storage, or network required

---

## 🛠 Customization

You can modify:
- Colors and fonts in the `<style>` section of the HTML
- Add new logic (e.g., card counters, keyboard shortcuts) in the `<script>` section

---

## 📁 Files

- `index.html` — Main app
- `README.md` — You're here

---

## ✅ Ideal For

- Technical study sessions
- Quick memory drills
- Offline flashcard creation with full privacy

---

Enjoy your focused learning! ✨
