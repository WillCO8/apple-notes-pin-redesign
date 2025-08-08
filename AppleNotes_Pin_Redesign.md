# 📝 Apple Notes Pin/Unpin Redesign Project Framework

> “Fixing one small pain point that interrupts millions of workflows.”

---

## 🔍 Overview

This document outlines the planning process for a UX/UI redesign project focused on improving the **Quick Pin/Unpin Note** feature within the Apple Notes application.

Millions of users rely on Apple Notes for focus, task capture, and idea organization. However, one core function — pinning a note — remains frustratingly hidden behind multiple taps. This redesign brings that feature into the light, making it intuitive, accessible, and lightning-fast.

---

## ▶️ Live Prototype

You can **view and interact with the Figma prototype** here:  
👉 [Figma: Apple Notes Pin/Unpin Redesign](https://www.figma.com/make/WwxkA9J5atwMjfCTjaYoi2/Apple-Notes-Pin-Unpin-Redesign?node-id=0-1&p=f&t=Brabhwa47nAekSQU-0&fullscreen=1)

> 💡 Tip: Use the “Present” mode link when sharing. It creates a distraction-free, full-screen experience ideal for demos and user testing.

---

## 🧠 Step 1: Project Framework

### 🔧 Feature to Redesign  
Apple Notes — Quick Pin/Unpin a note from within an **open note** view.

---

### 🧩 Problem Statement (McKinsey Framework)

- **Situation**: Apple Notes users frequently work within individual notes and often need to quickly prioritize or de-prioritize them.

- **Complication**: The current pin/unpin flow requires tapping a "More" (three dots) menu, then selecting "Pin Note" or "Unpin Note." This multi-step interaction adds unnecessary friction and cognitive load. Additionally, because this option is buried in a menu, many users may not even know it exists — or forget it does.

- **Key Question**:  
  _How might we redesign the in-note pinning/unpinning interaction to be a single-tap, intuitive action, thereby improving user efficiency and focus?_

---

## 💡 Solution

Introduce a **prominent, always-visible "Pin/Unpin" button** in the toolbar/header of each open note — eliminating the menu entirely.

✅ Design clear visual feedback (e.g., icon toggle, brief toast message) to confirm action, without requiring more navigation or interruptions.

---

## 🎯 Value Proposition

For Apple Notes users, this redesign offers:

- A **faster, one-tap workflow** to pin or unpin notes.
- Improved **discoverability** of a powerful organization feature.
- Greater **flow and focus** during note-taking or idea capture.

---

## 📦 MVP Scope

### ✅ What's Included:

- **Screen 1: Open Note – Unpinned State**  
  → Displays a static note with a new, unpinned icon (outlined pushpin).

- **Screen 2: Open Note – Pinned State**  
  → Same note, but the pin icon shows a filled state.

- **Screen 3: Confirmation Toast**  
  → Temporary overlays for messages like "Note Pinned!" or "Note Unpinned!"

- **Figma Interactions**:  
  → Tapping the pin icon shows toast and navigates between screens.

---

### 🚫 What's Out of Scope:

- Real dynamic logic (e.g. pinned notes moving to top of list).
- Backend logic or data persistence.
- Animations beyond basic transitions.
- Redesigning other parts of the app (list view, formatting, etc.).

---

## 🧪 Assumption to Test

We believe that:

> **Users will find a direct, single-tap pin/unpin button significantly faster and more intuitive than the current multi-tap method.**  
This will increase satisfaction, usability, and awareness of the pin feature.

---

## 🧬 Testing Plan

### 🔍 Usability Testing (Moderated)

- Ask users:  
  “You’re in this note. Show me how you’d pin it.”  
  Then: “Now unpin it.”

- Observe:  
  Speed, hesitation, confidence, understanding of icon meaning.

---

### 🗣 Qualitative Feedback

- “How did this compare to how you normally pin/unpin notes?”
- “Was it clear what the button did and what happened?”
- “Would this improve your day-to-day note-taking workflow?”
- “Were you aware of the pin feature before this?”

---

## 🧭 GitHub Repo Setup

This redesign is tracked and versioned at:  
👉 [https://github.com/williamchonortega/apple-notes-pin-redesign](https://github.com/williamchonortega/apple-notes-pin-redesign)

---

## 🧰 Git Commands (for reference)

If you need to recreate or re-push this repo:

```bash
git init
git add .
git commit -m "Initial commit: case study and redesign plan"
git branch -M main
git remote add origin https://github.com/WillCO8/apple-notes-pin-redesign.git
git push -u origin main
