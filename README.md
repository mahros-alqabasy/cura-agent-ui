# 🎨 Cura Agent – UI/UX Design Reference

Welcome to the `ui-ux-design` branch of the **Cura Agent** project. This branch contains all design assets, style guides, screen references, and components documentation for the frontend team.

The goal of this branch is to ensure consistency, scalability, and clarity across all frontend development workflows.

---

## 🗂 Structure

```bash
ui-ux/
├── style-guide/       # Color system, typography, layout standards, themes
├── screens/           # Full screen designs (landing, dashboards, login, etc.)
├── components/        # Reusable UI element documentation (buttons, cards, inputs)
├── assets/            # Fonts, icons, PDFs, and Figma links
```

---

## 🧱 What’s Inside

### `style-guide/`
Defines our full design system:
- Light & dark themes
- Spacing and layout grid
- Typography hierarchy
- Color system references

### `screens/`
Each folder contains:
- `design.png` – the final UI mockup for the screen
- `notes.md` – states, logic, and interactions for devs

### `components/`
Reusable UI patterns:
- Buttons (sizes, states)
- Inputs (validation, icons)
- Cards
- Modals, forms, and layout primitives

### `assets/`
- Fonts and icon libraries
- Figma URLs (in `raw-figma-links.txt`)
- Exported PDFs (offline access to designs)

---

## 📌 How to Use

1. Browse `/screens` to find the layout and logic for each route.
2. Reference `/style-guide` before building any new layout or component.
3. Use `/components` to build UI primitives before composing screens.
4. Follow naming, spacing, and visual specs carefully for consistency.
5. Reach out to the design team if any asset or screen is unclear.

---

## ✍️ Contributors
For designer roles and contact info, see the [`/authors`](../screens/authors/) screen or visit: [https://cura-agent.com/authors](https://cura-agent.com/authors)

---

**This branch is reference-only.**  
All code lives in the main production or development branches.
