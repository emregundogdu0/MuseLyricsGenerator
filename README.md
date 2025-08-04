# Muse Lyrics Generator 🎵

This is an LSTM-based text generation project that creates song lyrics in the style of the band **Muse**.  
It uses TensorFlow/Keras and is trained on a dataset of Muse lyrics.

---

## 🚀 Features

- Tokenizes Muse lyrics and trains a word-level language model.
- Uses a bidirectional LSTM with embedding for sequence prediction.
- Supports text generation given a custom seed phrase.

---

## 📁 Project Structure

📦 Muse_Lyrics_Generator/
 ┣ 📄 muse_all_songs.txt         ← Raw lyrics (one line per lyric)
 ┣ 📄 muse_lyrics_generator.py   ← Main training and generation script
 ┣ 📄 README.md                  ← This file

---

## 🧠 Model Architecture

- Embedding Layer
- Bidirectional LSTM (150 units)
- Dropout
- LSTM (100 units)
- Dense layer with softmax activation

---

## 📝 Example Usage

You can generate lyrics by changing the `seed_text` in the script:

```python
seed_text = "your sentence"
next_words = 100
```

---

## 📌 Notes

- This model is trained on a small dataset, so outputs may be repetitive.
- You can improve it by training with more data or fine-tuning hyperparameters.

---

## 🤘 Created with love for Muse fans!
