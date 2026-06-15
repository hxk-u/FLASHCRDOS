# 汉字学习 – Chinese Vocabulary Flashcards

A mobile-friendly flashcard app for learning Chinese vocabulary, with daily streaks, swipe gestures, and JSON import.

## Features

- 📂 **Import JSON files** with your daily vocabulary
- 🃏 **Swipe flashcards** — right = know it, left = forgot it
- 🔥 **Day streak tracking** with a 28-day calendar view
- 🔁 **Retry forgotten words** at the end of each session
- 💾 **Saves your data** locally on your device (localStorage)
- 📱 **Installable** as a home screen app on iPhone & Android

## JSON Format

```json
[
  {
    "hanzi": "你好",
    "pinyin": "nǐ hǎo",
    "meaning": "Hello",
    "example": "你好，我叫小明。"
  },
  {
    "hanzi": "谢谢",
    "pinyin": "xiè xie",
    "meaning": "Thank you"
  }
]
```

The `example` field is optional. The app also accepts `character`, `word`, `pronunciation`, `definition`, `translation`, `english`, and `sentence` as alternative field names.

## Usage

1. Go to **Import new words** and upload or paste a JSON file
2. Tap **Save as today's session**
3. Go to **Study sessions** and tap your session
4. Tap the card to reveal the meaning, then swipe right (know) or left (forgot)
5. At the end, retry forgotten words or go back to home

## Hosting on GitHub Pages

1. Create a new GitHub repository (e.g. `chinese-vocab`)
2. Upload `index.html`, `manifest.json`, and `icon.svg`
3. Go to **Settings → Pages → Source → main branch → / (root)**
4. Your app will be live at `https://yourusername.github.io/chinese-vocab/`

## Install on your phone

**iPhone (Safari):**
1. Open the GitHub Pages URL in Safari
2. Tap the Share button → "Add to Home Screen"
3. Tap Add — the app appears on your home screen

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the three-dot menu → "Add to Home screen"
3. Tap Add
