# Ellty Frontend Test – Round 1: Form Styling

This repository contains my implementation for **Ellty's Frontend Test (Round 1)**.  
The task was to **replicate a UI component** from Figma with pixel-perfect accuracy using **HTML, CSS, and JavaScript**.

---

## 🎯 Objective

To recreate a single dropdown component that matches the provided Figma design in both **style and layout precision**, including:

- Typography (Montserrat, 14px, line height 130%)
- Exact spacing, padding, and dimensions
- Proper border radius, shadow, and colors
- Custom-styled checkboxes
- Interactive "Done" button

---

## 🖼️ Figma Reference

**Frame Name:** `Frame 8445891`  
**Width:** `370px`  
**Height:** `326px`  
**Border radius:** `6px`  
**Shadow:** `0px 8px 15px rgba(20, 20, 20, 0.12)`  
**Font:** `Montserrat, Regular, 14px`  
**Colors:**
| Element | Color | Hex |
|----------|--------|------|
| Background | White | `#FFFFFF` |
| Text | Black | `#1F2128` |
| Divider lines | Gray | `#E3E3E3` |
| Button | Yellow | `#FFCE22` |
| Checkbox border | Gray | `#E3E3E3` |
| Checkbox checked | Black | `#1F2128` |

---

## 🧱 Project Structure

ellty-form-test/
│
├── index.html # Main HTML file
├── styles/
│ └── style.css # Core styles (layout, typography, interactivity)
├── scripts/
│ └── main.js # Simple interactivity for the Done button
└── README.md # Documentation

yaml
Copy code

---

## ⚙️ Tech Stack

- **HTML5** – semantic structure
- **CSS3** – pixel-perfect styling and component precision
- **Vanilla JavaScript** – basic interactivity for the button
- **Montserrat** – imported from Google Fonts
- **GitHub Pages** – for live deployment

---

## 🧩 Component Breakdown

### 1. Dropdown Section

- Title: "All pages"
- Checkbox aligned right
- 4 list items (Page 1–4)
- Each line: horizontal layout with text and checkbox  
- Divider line between items (1px #E3E3E3)

### 2. Button

- Label: “Done”  
- Color: `#FFCE22`
- Text color: `#1F2128`
- Border-radius: 4px  
- Hover state: lighter yellow (`#FFD84E`)

### 3. Container

- Centered vertically and horizontally  
- White background  
- Rounded corners  
- Subtle shadow for depth

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/goal-super-dev/ellty-form-test.git
   cd ellty-form-test
Open index.html directly in your browser.

or, for live server auto-refresh:

bash
Copy code
npx live-server
🌐 Deployment
Deployed using GitHub Pages.

Live URL:
👉 https://goal-super-dev.github.io/ellty-form-test/

📋 Notes
Component width: 370px

Card height: auto (adapts based on items)

Follows all spacing and layout rules from the provided Figma

No external UI frameworks or libraries were used

Code kept clean, semantic, and easy to extend

👤 Author
Mark Jarvier
Frontend Developer Candidate — Ellty
📧 shaunblair117@gmail.com
🌐 https://github.com/goal-super-dev

🧠 Reflection
This task tested:

Visual precision and attention to layout details

CSS structuring for maintainability

Recreating custom UI states (checkbox, hover, shadow)

Reproducibility across screen sizes