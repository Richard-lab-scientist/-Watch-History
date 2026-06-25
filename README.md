# Watch History Analyses
## Project Overview
A personal data project that tracks and analyzes a year of YouTube viewing;built to see how my screen time aligns with my learning goals.

## 📊 The Dataset

**File:** `watch_history.xlsx` — sheet **Watch History**

| Column | Description |
|---|---|
| `Date Watched` | Calendar date the video was watched |
| `Day of Week` | Day name, derived from the date |
| `Video Title` | Title of the video |
| `Channel` | Creator / channel name |
| `Category` | Topic bucket (Psychology, Economics & Finance, Arts, etc.) |
| `Duration (min)` | Full length of the video |
| `Completion %` | How much of the video was actually watched 
| `Month` | Month label, for trend rollups |

**At a glance**
- **199** logged viewing sessions
- **June 2025 → June 2026** (~12.5 months)
- **120** unique videos across **25** channels
- **86.9%** average completion rate — when a video got clicked, it mostly got watched

## 🏆 Key Insights

### Where the time went, by category

<img width="1108" height="608" alt="Screenshot 2026-06-24 230406" src="https://github.com/user-attachments/assets/7b8824dd-f903-4400-bab6-06cf133e91b3" />


**Takeaway:** Finance and markets content (Economics & Finance + Markets & Investments combined) dwarfs every other topic — nearly as much time as Entertainment and Psychology combined. The "self-improvement" categories (Learning, Learning Science, Neuroscience/Productivity) round out a respectable chunk too.

### Most-watched channels
| Channel | Sessions |
|---|---|
| MoneyWeek | 28 |
| The Organic Chemistry Tutor | 15 |
| Draw Like a Sir | 15 | 
| SkySports Premier League | 12 | 
| Khan Academy | 12 | 
| 10,000 Black Intern | 11 | 

### Viewing rhythm
- **Busiest month:** January 2026 (22 sessions) — new year, new habits, apparently
- **Quietest month:** June 2025 (8 sessions) — the very start of tracking
- **Favorite day to watch:** Thursday (33 sessions), closely followed by Monday (30)

## 🗂️ Categories Tracked
`Economics & Finance` · `Markets & Investments` · `Entertainment` · `Psychology` · `Mathematics` · `Technology & AI` · `Arts` · `CV & Networking` · `Learning` · `Learning Science` · `Neuroscience/Productivity`

## 🛠️ Tools Used
- **Excel** — data entry, pivot tables, and the summary stats 


## 📁 Repo Structure
```
.
├── watch_history.xlsx     # the raw log
└── README.md               # you are here
```

