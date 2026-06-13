# Calculus 1 – Structured Notes and Visual Index (Professor Leonard Lectures)

A fast-reference study tool for finding concepts quickly, revisiting the exact explanation, and reviewing Professor Leonard’s lectures without having to rewatch them in full.

This repository includes clickable video timestamps, complete whiteboard captures, structured MathJax-rendered notes, and direct navigation to specific concepts throughout each lecture.

It is designed to help students:

* find a concept quickly
* avoid losing 40 minutes searching through a lecture
* see the exact whiteboard work for a topic
* return directly to the moment where an idea is explained
* review efficiently without rewatching an entire class

## Index

1. [Repository Overview](#1-repository-overview)
2. [Local Use](#2-local-use)
   - [Recommended Editor: Zettlr](#recommended-editor-zettlr)
   - [How to Use Locally](#how-to-use-locally)
3. [Remote Use (via GitHub Pages)](#3-remote-use-via-github-pages)
4. [Motivation](#4-motivation)
5. [Credits and License](#5-credits-and-license)

---

## 1. Repository Overview

This repository provides a structured index to Professor Leonard’s Calculus 2 lecture series, combining clickable timestamps, complete whiteboard captures, and organized mathematical notes across the full lecture series.

Topics covered include:

- Functions and graphing
- Trigonometry review
- Limits and continuity
- Derivatives and differentiation techniques\
- Applications of derivatives
- Implicit differentiation
- Related rates
- Increasing/decreasing functions
- Concavity and curve sketching
- Rolle’s Theorem and the Mean Value Theorem
- Optimization
- Indefinite and definite integrals
- The Fundamental Theorem of Calculus
- Area between curves
- Volumes of solids (disks, washers, and shells)
- Arc length


### Course Numbering Note


### Folder Structure

- **docs/**  
  Public-facing folder used by GitHub Pages to display content online (HTML + CSS only).

- **img/**  
  Contains all whiteboard screenshots used throughout the project. These are not a small selection of representative images; they constitute a systematic visual capture of the lecture content and are referenced throughout the notes.

  Each image is accompanied by a `.txt` sidecar file storing metadata.

  Example:
image\_name: [12-35]IntegrationByParts.png
file\_name:[12-35]-01.png
timestamp: 12:35
counter: 01
folder: Calculus 1 Lecture 7.1

- **ytb/**  
Contains the original lightweight timestamp indexes created during the early stages of the project. These files were designed to be pasted directly into YouTube comments so that viewers could navigate the lecture while watching it. Although largely superseded by the Markdown and LaTeX versions, they are preserved as part of the project's development history.

- **md/**  
Markdown versions of each lecture containing clickable video timestamps, screenshots, and structured notes.

These files provide direct navigation between the notes and the original lecture recordings.

**Important:** the `md/` files depend on the `img/` folder. Both should be downloaded together in order to display screenshots correctly.

- **latex/**  
Enhanced versions of the Markdown notes using LaTeX notation for mathematical expressions.

These files represent the final refined version of the notes and provide improved readability and mathematical clarity compared to the original Markdown drafts.

---

## 2. Local Use

### Recommended Editor: Zettlr

These notes were created and structured using [Zettlr](https://www.zettlr.com/), a powerful open-source Markdown editor. For optimal viewing—especially indentation, custom bullet hierarchies, image previews, hyperlinks, and mathematical notation—Zettlr is strongly recommended.

### How to Use Locally

1. Clone or download the repository.
2. Open the following folders in Zettlr or your preferred Markdown editor:

 - `img/`
 - `ytb/`
 - `md/`
 - `latex/`

For the best experience, keep the original folder structure intact, since screenshots are referenced through relative paths.

---

## 3. Remote Use (via GitHub Pages)

To explore the notes visually online, visit the rendered HTML site via GitHub Pages:

[GitHub Pages – Calculus 1 (Professor Leonard Lectures)](https://igarugueri.github.io/professor-leonard-calculus-1-video-timestamps-and-notes/)

The online version includes:

- Structured HTML lecture pages
- Complete whiteboard captures
- Mathematical notation rendered with MathJax
- Direct navigation between lectures

The `ytb/`, `md/`, and `latex/` folders are intended primarily for local use and are not optimized for direct reading on GitHub.

### Additional Resources

Many lectures include supplementary references at the end of the notes. These typically point to OpenStax materials or other freely available educational resources that may help reinforce the topic being studied.

---

## 4. Motivation

This project was created to solve a practical study problem: long lectures are extremely valuable, but they are not always easy to search, revisit, or review efficiently.

The aim of this repository is not to replace Professor Leonard’s lectures, but to make them easier to use as a long-term reference tool.

Instead of forcing students to rewatch entire lectures just to relocate a single explanation, the project allows them to identify a concept quickly, jump to the exact timestamp, inspect the corresponding whiteboard work, and continue studying with minimal friction.

The notes are not literal transcripts. They are structured study notes built from the mathematical content on the board, supplemented where necessary with clarifications, explanatory remarks, and cross-references.

Each lecture was manually reviewed, indexed, timestamped, organized, and linked to a complete visual record of the original whiteboard presentation.

---

## 5. Credits and License

All lectures are by **Professor Leonard**, whose work is publicly available on YouTube.

Special thanks to Professor Leonard for his remarkable ability to teach mathematics. One of the main motivations behind this project was the clarity of his explanations, his ability to make difficult concepts approachable, and his talent for turning topics that often seem intimidating into ideas that can be understood step by step.

His lectures not only provide mathematical content, but also a model of clear and effective teaching that inspired the creation of this repository.

* This project was independently created as a personal study and indexing tool.

* All timestamps, transcriptions, formatting, indexing, image organization, and cross-references were generated manually by the author.

* Whiteboard captures consist of screenshots taken from the original lecture videos and are included under fair use for educational purposes.

* Additional references may include links to OpenStax and other freely available educational resources.

* AI-assisted tools, including ChatGPT, were used to support parts of the workflow such as HTML generation, formatting, proofreading, and repository organization. All final content, indexing decisions, screenshots, timestamps, and study notes were reviewed and curated manually by the author.

© 2026. See the LICENSE file for reuse and distribution terms.
