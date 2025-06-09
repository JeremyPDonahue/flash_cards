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

4. **Answer Before Flipping**
   - Type your answer in the text input box
   - Press Enter to check if your answer is correct (turns green for exact matches)
   - Click the card to flip and see the correct answer

5. **Navigate Through Cards**
   - Click the flipped card to move to the next (randomized) card
   - Use the "Stay on current card" option to review without advancing

6. **Cycle Infinitely**
   - Once you reach the end of the flashcards, the cycle repeats from the beginning

---

## 🎨 Features

- **Clean dark mode UI** for reduced eye strain
- **Mobile and desktop friendly**
- **Click-to-flip flashcard animation**
- **Answer validation** - type your answer and get instant feedback
- **Randomized shuffle** each time you generate flashcards
- **Stay on card option** - review the same card multiple times
- **Auto-clear input** - optionally clear your answer when moving to the next card
- **Visual feedback** - green border when your answer is exactly correct
- **No tracking, storage, or network required**

---

## ⚙️ Options

- **Stay on current card** - Check this to prevent automatic advancement to the next card
- **Clear answer input when card flips to front** - Check this to automatically clear your typed answer when moving to a new question

---

## 🛠 Customization

You can modify:
- Colors and fonts in the `<style>` section of the HTML
- Add new logic (e.g., card counters, keyboard shortcuts) in the `<script>` section
- Adjust answer validation logic for more flexible matching

---

## 📁 Files

- `index.html` — Main app
- `README.md` — You're here

---

## ✅ Ideal For

- **Technical study sessions** with active recall
- **Quick memory drills** with immediate feedback
- **Offline flashcard creation** with full privacy
- **Self-testing** before exams or certifications

---

## 💡 Study Tips

1. Type your answer before flipping to engage active recall
2. Use exact wording for technical terms to build precision
3. Enable "Stay on current card" to review difficult concepts
4. Generate new randomized orders by clicking "Generate Flashcards" again

---

Enjoy your focused learning! ✨