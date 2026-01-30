# π Finder (Liquid Glass)

A sleek, glass-styled web app that finds **where a given digit string first appears in π**, counting **only digits after the decimal point**.

Example:
- `14` → position **1**
- `15` → position **3**

Positions are **1-based**, starting immediately after `3.`

---

## ✨ Features

- 🔍 Search for any numeric string inside π
- 📍 Returns **one output only**: the first location after the decimal
- 🧮 Uses a **pure JavaScript spigot algorithm** (no APIs, no internet)
- 🪟 **Liquid glass UI** with blur, glow, and floating gradients
- ⚡ Runs fully client-side in the browser
- 🎯 Adjustable search depth (number of π digits generated)

---

## 🖥️ Demo Behavior

- Input: `14` → Output: `1`
- Input: `15` → Output: `3`
- Input: `141592` → Output: `1`

All positions refer to digits **after** the decimal point in π.

---

## 🚀 How to Run

1. Save the HTML file as:
   ```bash
   pi-finder.html
