# 📅 [TMTBL — Your All-in-One Planner](https://tmtbl.vercel.app)
### Website: https://tmtbl.vercel.app

![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Android%20%7C%20Windows-blueviolet?logo=googlechrome)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?logo=javascript)
![Firebase](https://img.shields.io/badge/backend-Firebase-yellow?logo=firebase)
[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)
![Status](https://img.shields.io/badge/status-active-brightgreen)

> **TMTBL** is a smart, all-in-one productivity app for students — combining task management, school scheduling, smart notifications, and personal customization into a single seamless experience.

---

## Changelogs for v3.2
1. [🆕] Added a LastLoggedIn statistic to Firebase RTDB for users with a linked Key.

## Changelogs for v3.1
1. [🐞] Fixed a Bug where the `Weekly Day Off` in the Settings tab did not match with the Calendar.
2. [🆕] Added a button in Schedule tab which allows copy pasting schedules into other day types.

---

## ✨ What Makes TMTBL Different?

Most planners make you choose between a calendar, a to-do list, or a schedule. TMTBL gives you **all three, unified** — with school-aware day types, activity-level notifications, and a calendar you can actually navigate fast.

---

## 🚀 Features

### 📋 Task & To-Do Management

| Feature | Description |
|---|---|
| **Intelligent Sorting** | Separate *Active* and *Overdue* views keep priorities obvious |
| **Global Todos** | Tasks that aren't tied to any specific date live here |
| **Progress Bars** | Real-time visual completion status on the To-Do tab |
| **Task Categories** | Customizable dropdown categories to organize by subject or project |
| **Dynamic Filtering** | Toggle between active, overdue, and completed tasks on the fly |

---

### 📅 Scheduling & Calendar

- 🗓 **Flexible Day Types** — Define separate schedules for School Days, Weekends, Holidays, or any custom type you create
- 🔭 **Year-at-a-Glance View** — See an entire year's schedule with color-coded time blocks
- 📌 **Pinned Dates** — Highlight important dates with personal notes
- ⚡ **Bulk Operations** — Apply day types or settings across date ranges using *Set Range* or *Apply to Selected*
- 📆 **Interactive Calendar** — Tap any day to see its full schedule and tasks

---

### ~~🔔 Smart Notifications~~ (broken)

- ~~📚 **Homework Reminders** — Daily task alerts so nothing slips through~~
- ~~⏱ **Activity Transition Alerts** — Automatic notifications when an activity starts or ends, with duration info included~~
- ~~🌐 **Browser Notification Support** — Works even when TMTBL is running in a background tab~~

---

### 🎨 Customization & UX

- 🎨 **Custom Accent Themes** — Pick your accent color to make the app feel like yours
- 🔊 **Audio Feedback** — Subtle sound effects for tab switches, saves, and errors
- ⚙️ **Centralized Settings** — Notifications, schedule templates, day types, and preferences all in one place
- ☁️ **Profile Sync** — Your data follows you across sessions

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Backend / Sync** | Firebase (Firestore + Auth) |
| **Notifications** | Web Notifications API |

---

## 📂 Project Structure

```
TMTBL/
│
├── index.html      ← App entry point
├── style.css       ← All styling and themes
├── script.js       ← App logic, Firebase sync, notifications
├── sw.js           ← Notification handler
└── icon.png        ← App icon

```

---

## 📸 Screenshots

![Dashboard](https://i.postimg.cc/GtwbDGQ6/image.png)

![Schedule](https://i.postimg.cc/D0TK0FfZ/image.png)

![To-Dos](https://i.postimg.cc/nLG4gGsq/image.png)

![Stats](https://i.postimg.cc/XqGyjfJq/image.png)

![Settings](https://i.postimg.cc/pdWhhbTY/image.png)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.  
Feel free to use, modify, and distribute in accordance with the license terms.

---

## 💬 Feedback & Contributions

Found a bug? [Open an issue](../../issues)  
Have an idea? [Create a feature request](../../issues/new)  
Want to contribute? Pull requests are always welcome ❤️

---

<div align="center">
  <sub>Built with 💙 by <a href="https://github.com/YourUsername">kw3z</a></sub>
</div>
