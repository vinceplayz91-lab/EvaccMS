# Evacc — Event & Access Management System

> A school-focused event participation and student records management portal.

![HTML](https://img.shields.io/badge/HTML-Single%20File-4facfe?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-Vanilla-00f2fe?style=flat-square)
![JS](https://img.shields.io/badge/JavaScript-Vanilla-f59e0b?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)

---

## 🚀 Live Demo

**[View on GitHub Pages →](https://yourusername.github.io/evacc)**
*(Replace with your actual GitHub Pages URL after deploying)*

---

## 📌 Features

### 📊 Dashboard
- Browse all public school events
- Filter by department (Arts & Sciences, Business/Accountancy, Computer Engineering, Education, Health Sciences, IT)
- Filter by event type (Academic, Seminar, Workshop, Sports, Cultural, Org, Requirement)
- Live search across event titles, descriptions, and tags
- Stats summary (total events, joined, created, pending approvals)

### 🗂️ My Documents
- **School Balance** — itemized billing ledger with paid/pending status
- **School Documents** — COE, TOR, Good Moral Certificate, Grade Slips, etc.
- **General Documents** — Medical Certificate, Birth Certificate (PSA), National ID, etc.
- **Department Requirements** — per-department document checklists with submission status

### ⭐ My Events
- View all events you've joined or created
- Weekly schedule grid view
- Manage join requests (approve / deny)
- In-event discussion chat

### ➕ Create Event
- Full event creation form with validation
- Assign to a department
- Set capacity, venue, date/time, duration
- Tag system for discoverability
- Visibility control (public or department-only)

### 🔔 Notifications
- Real-time in-app notifications
- Unread badge on sidebar and topbar
- Mark individual or all as read

### 👤 Profile
- View and edit name, bio, birthdate, age, course, department, year level
- Contact info (Gmail, phone number)
- Student ID, GWA, academic standing
- Events summary stats

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Markup | HTML5 |
| Styling | Vanilla CSS (CSS Variables, Grid, Flexbox) |
| Logic | Vanilla JavaScript (no frameworks) |
| Fonts | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts |

No build tools, no dependencies, no npm. Just one file.

---

## 📁 Project Structure

```
evacc/
├── index.html     # Entire application (HTML + CSS + JS)
└── README.md      # This file
```

---

## 🌐 Deploying to GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose **main** branch → **/ (root)** → Save
5. Your site will be live at `https://yourusername.github.io/evacc`

---

## 💡 Notes

- All data is stored in-memory (JavaScript state). Changes reset on page refresh — this is by design for a front-end only demo.
- Google Fonts requires an internet connection. The UI still functions offline but will fall back to system fonts.
- To add persistent data in the future, consider integrating [Firebase](https://firebase.google.com) or [Supabase](https://supabase.com).

---

## 📄 License

MIT — free to use, modify, and distribute.
