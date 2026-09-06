# 📚 BookVerse

BookVerse is a web-based **library management system** that brings the entire day-to-day workflow of running a library — catalog, members, circulation, fines, reservations, and reporting — into one organized platform, replacing spreadsheets and paper logs.

## Overview

Libraries typically juggle books, member records, borrowing/return logs, and overdue tracking across disconnected tools. BookVerse consolidates all of it into a single system with role-based access for **Admins**, **Teachers**, and **Students**, so everyone interacts with the parts of the library relevant to them.

## Key Features

### 📖 Catalog Management
- Smart book catalog — search by title, author, or ISBN
- Filter by category or availability
- Live status per copy (Available / Borrowed / Maintenance)
- Categories & shelf organization
- Multi-copy tracking for titles with several physical copies

### 👥 Member Management
- Individual member profiles with contact info and membership status
- Active loans and due dates at a glance
- Full borrowing history per member

### 🔄 Circulation
- **Book Issue** — select member, book, and due date to issue in a few clicks
- **Book Return** — automatic overdue and fine calculation on return
- Due-date and overdue tracking with live counts (Due Today / Due Soon / Overdue / Active Loans)

### 💰 Fines & Reservations
- Automatic fine calculation for overdue books
- Paid/unpaid fine tracking
- Reservations & holds queue — members are notified when a held book becomes available

### 📊 Dashboard & Reports
- Library-wide stats: total books, total members, active loans, overdue books
- Borrowing activity trends over time
- Most-borrowed titles and category popularity
- Issued vs. returned circulation balance

### 🔔 Notifications
- Reminders for books due soon
- Overdue alerts
- Reservation-availability notifications

### 🔐 Role-Based Access
- **Admin** — full control over catalog, members, and reports
- **Teacher** and **Student** — dedicated portals for their own borrowing activity
- Auth module with login/register flows

## Project Structure

| Folder/File | Purpose |
|---|---|
| `admin/` | Admin dashboard and management views |
| `teacher/` | Teacher-facing portal |
| `student/` | Student-facing portal |
| `auth/` | Login and registration pages |
| `assets/` | Images and static assets |
| `styles/` | CSS stylesheets |
| `scripts/` | JavaScript files |
| `index.html` | Landing page |
| `about.html` | About/mission page |
| `product.html` | Full features overview |
| `contact.html` | Contact page |

## Tech Stack

Built with plain **HTML, CSS, and JavaScript** — no framework dependency, using Font Awesome for icons and Google Fonts (Poppins) for typography.

## Getting Started

```bash
git clone https://github.com/thisIsAyushFr/BookVerse.git
cd BookVerse
```

Open `index.html` in a browser, or serve locally:

```bash
npx serve .
```

Then register or log in via `auth/register.html` / `auth/login.html` to access the role-based dashboards.

## Status

This is a fork of [AgrimJoshi1/BookVerse](https://github.com/AgrimJoshi1/BookVerse).

