# 🧾 Screen Notes: Doctor Dashboard

This document contains UI/UX notes and logic breakdown for the **Doctor Dashboard** screen in the Cura Agent hospital system. It serves as a reference for frontend developers and QA to implement or review this screen accurately.

---

## 🧠 Purpose
A doctor’s personal dashboard that allows them to manage their appointments, access patient records, write prescriptions, and interact with the AI assistant.

---

## 🎯 Key Functional Areas

### 1. **Welcome Header**
- Displays the doctor’s name and profile picture.
- Optional: Notification icon (e.g., unread messages or tasks).

### 2. **Appointments Overview**
- Today’s and upcoming appointments listed in order.
- Fields: Patient Name, Time, Visit Type, Status
- Actions: "Start Consultation", "View Details"

### 3. **My Patients Table / Cards**
- Searchable list of recent or assigned patients.
- Fields: Name, Age, Last Visit, Condition Summary
- Actions: View Full Record, Chat, Add Notes

### 4. **Quick Actions / Shortcuts**
- Button-based links to:
  - Create Prescription
  - Open EMR
  - Access AI Assistant

### 5. **Embedded Assistant Preview (optional)**
- Inline box or sidebar prompt with suggested voice/text queries.
- Example prompts: “What was the latest lab result for John?”

---

## 🎨 UI Notes
- Light Theme only
- Primary Green: `#4CB269`
- Border/Divider: `#E0E0E0`
- Card Background: `#FFFFFF`
- Use clear spacing and visual groups (e.g., section headers)

---

## 📐 Responsive Behavior
- On small screens, tables turn into stacked card layouts.
- Quick Actions collapse into dropdown or toolbar.
- Assistant access stays visible or pinned for convenience.

---

## ✅ Validation Rules
- Actions should be disabled unless data is complete (e.g., can't start consult without patient info).
- Assistant queries should be scoped to doctor's permissions only.

---

## 📎 Developer Notes
- Component reuse: appointments, patient list, buttons
- Must support loading and empty states
- Add visual feedback (e.g., success toast after saving notes)

---

_Last updated: May 2025_
