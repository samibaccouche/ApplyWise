# 🧠 ApplyWise

### AI-Powered Cover Letter Generator & Critique Assistant

[![Made with Gemini](https://img.shields.io/badge/Powered%20by-Gemini-4285F4?logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20with-TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![ApplyWise Screenshot](https://via.placeholder.com/1000x500?text=ApplyWise+Dashboard+Preview)

---

## ✨ The Problem

> You send 100 applications. Hear back from 5. Interview with 2. Get 0 offers.

Generic, forgettable cover letters die in HR software. **ApplyWise** changes that.

## 🚀 The Solution

**ApplyWise** is a web app that:
- ✍️ **Generates high-impact cover letters** using Gemini AI with few-shot prompting (learns from perfect examples)
- 🔍 **Critiques your letters** with real-time keyword analysis + Google Search grounding
- 📄 **Exports to PDF** — ready to send in one click

No more writer's block. No more bland "I am very motivated" templates.

---

## 🎯 Features

| Feature | Description |
|--------|-------------|
| **Few-Shot Generation** | Gemini learns from proven letter templates (data scientist, project manager) and adapts to your profile |
| **AI Critique** | Analyzes style, clarity, structure, grammar, and **job-relevant keywords** |
| **Web-Grounded Analysis** | Uses Google Search to verify industry keywords (via Gemini grounding) |
| **PDF Export** | One-click download as professional PDF |
| **File Upload** | Upload existing `.txt` cover letters for critique |
| **Live Editing** | Modify generated letters directly in the editor |

---

## 🖼️ Screenshots

| Input Panel | Letter Editor | AI Critique |
|------------|--------------|--------------|
| ![Inputs](https://via.placeholder.com/300x200?text=Job+Details) | ![Letter](https://via.placeholder.com/300x200?text=Letter+Editor) | ![Critique](https://via.placeholder.com/300x200?text=AI+Critique) |

---

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML/CSS + TailwindCSS
- **AI Engine**: Google Gemini API (`gemini-2.5-flash-preview`)
- **Features**:
  - Few-shot prompting
  - System instructions for tone control
  - Google Search grounding for keyword validation
- **PDF Generation**: `html2pdf.js`

---

## 🏁 Quick Start

### 1. Clone & Open
```bash
git clone https://github.com/yourusername/applywise.git
cd applywise
open index.html
