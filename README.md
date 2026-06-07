# Hebrew Flashcards

A web app for studying Hebrew vocabulary using your own word lists. Free to use — just sign up and upload an Excel file to get started.

🔗 **[Try it live](https://dashing-trifle-f1c761.netlify.app)**

---

## Features

- Upload your own Excel vocabulary list
- Filter by category, choose how many cards, and pick random or newest-first order
- Flip cards, mark correct or incorrect, then drill the ones you missed
- Press **A** to hear the Hebrew word read aloud
- Flag cards as "Want to Review" — they save across sessions
- Your word list is saved so you don't re-upload every visit

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` | Flip card |
| `↑` | Got it |
| `↓` | Missed it |
| `A` | Hear Hebrew aloud |
| `S` | Flag as Want to Review |

---

## Excel format

Download the **[demo file](demo.xlsx)** to see an example, or create your own:

| Column | Content |
|--------|---------|
| A | English |
| B | Hebrew |
| C | Transliteration *(optional)* |
| D | Category *(optional)* |

The app reads your header row to detect which columns are present. Add new words at the bottom — this lets you study your newest vocabulary first.

---

## Built with

- [Supabase](https://supabase.com) — auth and database
- [Netlify](https://netlify.com) — hosting
- [SheetJS](https://sheetjs.com) — Excel parsing in the browser
- Web Speech API — Hebrew text-to-speech
