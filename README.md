# CrisperWhisper — Research Paper & Easy Notes

A detailed study and easy-to-understand notes on **CrisperWhisper**, an improved variant of OpenAI's Whisper designed for **verbatim speech transcription, accurate word-level timestamps, filler detection, and improved robustness against transcription hallucinations**.

This repository contains the original research paper along with simplified notes to understand the paper, its motivation, architecture, improvements over Whisper, and practical applications.

---

## 📌 About CrisperWhisper

**CrisperWhisper** is an advanced speech recognition model based on OpenAI's Whisper.

Unlike conventional speech-to-text systems that may clean up or omit parts of natural speech, CrisperWhisper focuses on producing **verbatim transcriptions** — capturing what the speaker actually says, including:

- Fillers such as `um`, `uh`, etc.
- Repeated words
- Stutters
- False starts
- Pauses and disfluencies
- More accurate word-level timestamps

The research focuses particularly on improving the accuracy of **word-level timestamps** obtained from Whisper's cross-attention scores using Dynamic Time Warping (DTW).

---

## 📄 Research Paper

### CrisperWhisper: Accurate Timestamps on Verbatim Speech Transcriptions

**Authors:**

- Laurin Wagner
- Bernhard Thallinger
- Mario Zusag

**Published:** 2024

**Conference:** INTERSPEECH 2024

**arXiv:** 2408.16589

The paper demonstrates that carefully modifying Whisper's tokenizer and training procedure can significantly improve word-level timestamp accuracy and verbatim transcription performance.

---

## 📂 Repository Contents

```text
Research-Pepar-CrishperWishper/
│
├── Crisper-Wishper.pdf
│   └── Original research paper
│
├── CrisperWhisper_Easy_Notes.docx
│   └── Simplified notes explaining the research paper
│
└── README.md
    └── Project documentation
