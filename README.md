# Calculus 1 – Structured Notes and Visual Index (Professor Leonard Lectures)
Includes synchronized video timestamps, whiteboard snapshots, and structured MathJax-rendered notes for each lecture.


## Index

1. [Repository Overview](#1-repository-overview)  
2. [Local Use](#2-local-use)  
   2.1 [Recommended Editor: Zettlr](#21-recommended-editor-zettlr)  
   2.2 [How to Use Locally](#22-how-to-use-locally)  
3. [Remote Use (via GitHub Pages)](#3-remote-use-via-github-pages)  
4. [Motivation](#4-motivation)  
5. [Credits and License](#5-credits-and-license)


---

## 1. Repository Overview

This repository offers a highly organized and visually structured index for Professor Leonard's _Calculus 1_ lecture series. The goal is to provide a fast, reliable reference to core topics using clear timestamps, concise explanations, and visual board captures.

### Folder Structure:

- **docs/**  
  Public-facing folder used by GitHub Pages to display content online (HTML + CSS only).

- **img/**  
  Contains all board screenshots, organized by lecture. Each image is accompanied by a `.txt` _sidecar file_ storing metadata:
  ```
  image_name: 
  file_name: 
  timestamp: 
  counter: 
  folder: 
  ```

- **ytb/**  
  Plain-text timestamp notes specifically formatted for YouTube comments. Allows direct following of the lecture with minimal clutter.

- **md/**  
  Markdown versions of each lecture with clickable timestamps and embedded screenshots. Best for browsing raw notes.

- **latex/**  
  LaTeX-formatted Markdown files, with all math notation rendered clearly for structured reading. Not intended for printing, but for clarity and study.

---

## 2. Local Use

### Recommended Editor: Zettlr

These notes were created and structured using [Zettlr](https://www.zettlr.com/), a powerful open-source Markdown editor. For optimal viewing—especially indentation, custom bullet hierarchies, and image previews—Zettlr is strongly recommended.

### How to Use Locally

1. Clone or download the repository.
2. Open the following folders in Zettlr or your preferred Markdown viewer:
   - `img/`
   - `ytb/`
   - `md/`
   - `latex/`

These folders are not optimized for viewing on GitHub but provide the best experience locally.

---

## 3. Remote Use (via GitHub Pages)

To explore the notes visually online, visit the rendered HTML site via GitHub Pages:

[GitHub Pages – Calculus 1 Notes](https://igarugueri.github.io/professor-leonard-calculus-1-video-timestamps-and-notes/)

This version includes only:
- The `docs/` folder (HTML versions of the lectures).
- The `img/` folder (for loading screenshots).

Notes in `ytb/`, `md/`, and `latex/` are not meant to be read directly on GitHub due to formatting limitations.

---

## 4. Motivation

This project was born from the need to have a **fast, reliable reference** for key concepts in _Calculus 1_. Over time, even solid understanding can fade, and having a structured index with timestamps, math notation, and visuals helps reinforce or recover these ideas quickly.

This is especially useful during revision periods or while studying more advanced calculus topics.

---

## 5. Credits and License

- All lectures are by **Professor Leonard**, whose work is publicly available on YouTube.
- This project was independently created as a personal study and indexing tool.
- All timestamps, transcriptions, and formatting were generated manually by the author.
- Screenshots fall under fair use for educational purposes.

© 2025. See the LICENSE file for reuse and distribution terms (MIT License recommended).
