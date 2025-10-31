
---

## 💻 Running on a Computer

1. Make sure all your audio files are in the `audio` folder.
2. Double-click `index.html` — it should open in your default browser.
3. Click “Hear Sound” to listen to the pronunciation.

> Works completely offline.

---

## 📱 Running on iPhone or iPad

### Option 1 — Open in Safari
1. Save `index.html` and the `audio` folder to **Files → On My iPhone → FrenchFlashcards**.
2. In **Files**, long-press `index.html` → tap **Quick Look** → **Share** → choose **Safari**.
3. Safari opens your flashcard app.
4. Tap **Share → Add to Home Screen** to make it a standalone app.

### Option 2 — iCloud Drive
1. Upload the folder to **iCloud Drive**.
2. On your iPhone, open **Files → iCloud Drive → FrenchFlashcards**.
3. Tap `index.html` → **Share → Open in Safari**.

---

## 🔉 Downloading the Sounds (Optional)

If you haven’t already downloaded the French alphabet MP3s, you can use this Terminal command on Mac:

```bash
mkdir -p audio
for l in {a..z}; do
  curl -s -o "audio/$l.mp3" "https://phraseguides.com/French/audio/$l.mp3"
  echo "Downloaded $l.mp3"
done
