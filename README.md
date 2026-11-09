# Awesome-Task-Management-To-Do-Tracking

# Awesome Task Management & To-Do Tracking

> A curated list of top Task Management and To-Do Tracking platforms — both SaaS/Hosted commercial solutions and open-source alternatives for capturing, organizing, and completing personal and team tasks.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Todoist](#todoist)
  - [TickTick](#ticktick)
  - [Microsoft To Do](#microsoft-to-do)
  - [Things 3](#things-3)
  - [Any.do](#anydo)
  - [Google Tasks](#google-tasks)
  - [Habitica](#habitica)
  - [Trello](#trello)
- [Open-Source Software](#-open-source-software)
  - [Vikunja](#vikunja)
  - [Super Productivity](#super-productivity)
  - [Jotter](#jotter)
  - [Planka](#planka)
  - [OpenHabitTracker](#openhabittracker)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Task Management and To-Do Tracking platforms. These are not open-source but are included as reference points for feature comparison.

### Todoist
**Type:** Natural language task capture with cross-platform sync
Todoist is one of the most widely adopted personal task managers, known for its natural language input (type "Submit report tomorrow 5pm" and it parses date, time, and task). It supports projects, labels, priorities, filters, and shared projects for small-team collaboration. A free tier covers core task management, while paid plans add reminders, file uploads, and productivity tracking.

### TickTick
**Type:** All-in-one task manager with calendar and Pomodoro
TickTick combines to-do lists, a calendar view, Pomodoro timer, and habit tracking in a single app. It is often compared to Todoist for task capture but differentiates with built-in time management tools. Available across web, desktop, and mobile platforms.

### Microsoft To Do
**Type:** Task management within Microsoft ecosystem
Microsoft To Do (formerly Wunderlist) provides simple task lists with My Day, due dates, reminders, and subtasks. It integrates with Microsoft 365 and Outlook Tasks, making it the natural choice for organizations already using Microsoft productivity tools.

### Things 3
**Type:** Premium task manager for Apple platforms
Things 3 is a polished, design-focused task manager exclusive to Apple platforms (Mac, iPad, iPhone). It is known for its elegant interface, Today/Upcoming/Anytime views, and deep integration with Apple's ecosystem. A one-time purchase rather than subscription-based.

### Any.do
**Type:** Simple task management with calendar integration
Any.do provides a clean task list with My Day, reminders, and calendar integration. It is positioned for users wanting a straightforward task manager with a gentle learning curve, available across web and mobile.

### Google Tasks
**Type:** Task capture within Google Workspace
Google Tasks integrates with Gmail, Google Calendar, and Google Workspace, allowing users to create tasks from emails and view them alongside their calendar. It is lightweight and best suited for users already embedded in the Google ecosystem who need basic task tracking.

### Habitica
**Type:** Gamified habit and task tracking
Habitica treats tasks and habits as part of an RPG where completing them earns XP, gold, and gear. It is uniquely motivating for users who respond well to gamification, with parties and quests adding social accountability [citation:4]. The core game is free, with a cosmetic subscription at $4.99/month.

### Trello
**Type:** Kanban-based task and project tracking
Trello popularized the Kanban board metaphor for task management, with cards moving through lists. While often used for project management, its simplicity makes it a popular choice for personal to-do tracking with a visual workflow. Power-Ups add calendar views and automation.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Task Management and To-Do Tracking tools. The open-source ecosystem offers strong options across different philosophies: lightweight Todoist-style managers, time-tracking-focused apps, and local-first data ownership tools.

### Vikunja
**Stack:** Go / Vue.js / SQLite or PostgreSQL | **License:** AGPLv3
Vikunja is the closest open-source equivalent to Todoist, offering tasks, projects, subtasks, labels, priorities, due dates with reminders, and recurring tasks [citation:5][citation:12]. It supports four views (List, Kanban, Gantt, Table) and **CalDAV sync**, turning it into a calendar-integrated productivity hub [citation:5]. Native importers exist for Todoist, Trello, and Microsoft To Do, making migration straightforward [citation:5]. It runs as a single binary with SQLite and can be self-hosted or used via Vikunja Cloud (~$5/month) [citation:12]. **Trade-off:** Smaller community and fewer third-party integrations than Todoist [citation:12].
**Best for:** Individuals and teams wanting a feature-rich, self-hosted Todoist alternative with multiple views, CalDAV sync, and easy migration from popular tools.

### Super Productivity
**Stack:** Electron / Angular | **License:** MIT
Super Productivity is a task manager with **integrated time tracking and timeboxing**, positioned as a free replacement for TickTick, Trello, and Toggl [citation:9][citation:15]. It provides a to-do list core with subtasks, attachments, tags, and due dates, plus a Pomodoro timer, daily planner, Kanban board, and Eisenhower Matrix [citation:6][citation:15]. It integrates natively with GitHub, GitLab, Jira, Redmine, and OpenProject, pulling issues into your task list [citation:6]. **No telemetry, no accounts required**, with optional sync via WebDAV, Dropbox, or CalDAV [citation:13]. MIT-licensed and free forever [citation:13]. **Trade-off:** Desktop-centric (though mobile apps exist); more focused on individual deep work than team collaboration.
**Best for:** Developers, freelancers, and anyone wanting task management tightly coupled with time tracking, Pomodoro focus tools, and developer tool integrations.

### Jotter
**Stack:** Python / SQLite / Markdown | **License:** Open Source
Jotter is a **local-first, privacy-focused** task manager modeled as a Markdown Kanban board [citation:1][citation:2]. Tasks are stored as human-readable `.md` files in Open Knowledge Format, with an optional Git repository for versioning and sync [citation:1]. Features include Kanban, list, Eisenhower Matrix, and time views; smart task creation with keywords; Excel/CSV import/export; and **MCP support** for AI assistant integration [citation:1]. It runs via `pipx` or as a standalone executable, with an Android app that works offline on local Markdown files [citation:1][citation:10]. **Trade-off:** Requires comfort with local file management and optional Git workflows; not a cloud-first collaborative tool.
**Best for:** Privacy-conscious users and PKM (personal knowledge management) enthusiasts wanting full data ownership with Markdown files, Git sync, and AI assistant integration.

### Planka
**Stack:** Node.js / React / PostgreSQL | **License:** Fair-code (Community)
Planka is a clean, self-hosted Kanban board positioned as a Trello alternative, with 11,000+ GitHub stars and 7M+ Docker pulls [citation:7][citation:14]. It supports projects, boards, lists, cards, labels, due dates, checklists, attachments, real-time updates via WebSockets, and OIDC single sign-on [citation:14]. The Community edition is free to self-host with all core features; a Pro edition adds scalability and advanced features [citation:7]. **Trade-off:** Kanban-only (no list, Gantt, or table views), and the license is Fair-code rather than OSI-approved open source.
**Best for:** Teams wanting a focused, self-hosted Trello replacement with real-time collaboration and a clean interface, particularly those already comfortable with Kanban workflows.

### OpenHabitTracker
**Stack:** (Check repository) | **License:** GPL-3.0
OpenHabitTracker is a **Habitica alternative without the RPG**, designed for users who want habit and task tracking without gamification, penalties, or accounts [citation:4]. It stores data locally on your device, works offline, and offers native apps for Windows, macOS, Linux, Android, and iOS [citation:4]. Instead of XP and damage, it shows **urgency percentages** based on how overdue a habit is relative to its desired interval, with color-coded badges [citation:4]. Tasks support sub-items, Markdown notes, and reminders. Optional self-hosted sync is available via Docker [citation:4].
**Best for:** Users who liked Habitica's core concept but want a calmer, offline-first approach without gamification penalties or cloud accounts.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Views | Time Tracking | Self-Hosted | Best For |
|----------|---------|-------|-------|---------------|-------------|----------|
| **Todoist** | Proprietary | Cloud | List, Board | ❌ | ❌ | Natural language capture |
| **TickTick** | Proprietary | Cloud | List, Calendar | ✅ Pomodoro | ❌ | All-in-one task + time |
| **Microsoft To Do** | Proprietary | Cloud | List | ❌ | ❌ | Microsoft 365 users |
| **Things 3** | Proprietary | Apple only | List, Timeline | ❌ | ❌ | Apple ecosystem polish |
| **Habitica** | Proprietary (core free) | Cloud | List | ❌ | ❌ | Gamified motivation |
| **Vikunja** | AGPLv3 | Go/Vue/SQLite | List, Kanban, Gantt, Table | ❌ | ✅ | Todoist alternative + CalDAV |
| **Super Productivity** | MIT | Electron | List, Kanban, Matrix | ✅ Deep | ✅ (Desktop) | Time tracking + dev tools |
| **Jotter** | Open Source | Python/Markdown | Kanban, List, Matrix | ❌ | ✅ (Local) | Markdown + Git ownership |
| **Planka** | Fair-code | Node.js/Postgres | Kanban only | ❌ | ✅ | Clean Trello replacement |
| **OpenHabitTracker** | GPL-3.0 | (Check) | List | ❌ | ✅ (Optional) | Habit tracking without RPG |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Task Management or To-Do Tracking tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between Todoist-style managers (Vikunja), time-tracking-focused apps (Super Productivity), local-first/Markdown tools (Jotter), and Kanban boards (Planka). Vikunja is the most direct Todoist replacement, Super Productivity is the strongest choice for developers wanting integrated time tracking, and Jotter is notable for users prioritizing full data ownership via Markdown and Git.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
