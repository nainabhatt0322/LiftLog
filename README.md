# LiftLog 💪

> Train. Track. Recover.

A clean, simple and installable workout tracker built as a Progressive Web App (PWA).

LiftLog is designed to make tracking workouts effortless — no complicated dashboards, no unnecessary data entry. Just open your workout, complete your exercises, use the rest timer, and keep your training history.

## ✨ Features

- 🏋️ 5-day workout plan
- ☑️ Mark exercises as completed
- ⏱️ Built-in rest timers
- 📅 Choose a specific workout date
- 📖 Permanent dated workout history
- ⏭️ Skip a workout day
- ↩️ Unskip a skipped day
- 🗑️ Delete history by date
- 🔄 Reset completed exercises without deleting history
- 📱 Installable on mobile as a PWA
- 💻 Responsive desktop interface
- 📴 Offline support after the first load
- 💾 Local browser storage
- 🎨 Clean, minimal interface

## 📱 Install LiftLog

### Android

Open LiftLog in Chrome and choose:

**Install app / Add to Home Screen**

### iPhone

Open LiftLog in Safari:

**Share → Add to Home Screen**

### Desktop

Open LiftLog in a supported browser and use the install option in the address bar or browser menu.

## 🗓️ Workout Tracking

LiftLog uses a calendar-based system so workouts are tied to their actual dates.

For example:

| Date | Workout | Status |
|---|---|---|
| Aug 10 | Day 1 | ✅ Completed |
| Aug 11 | Day 2 | ⏭️ Skipped |
| Aug 13 | Day 3 | ✅ Completed |
| Aug 14 | Day 4 | 🔄 In progress |

Resetting completed exercises does **not** erase your previous workout history.

Individual dates can also be deleted from the history when needed.

## 🏋️ Workout Split

### Day 1
**Lower A**
- Squat
- Hip Thrust
- RDL
- Leg Press
- Leg Extension
- Core

### Day 2
**Upper A**
- Pull-up progression
- Bench Press
- Lat Pulldown
- Seated Row
- Shoulder Press
- Lateral Raises
- Arms

### Day 3
**Lower B**
- Deadlift
- Hip Thrust
- RDL
- Leg Press
- Leg Extension
- Core

### Day 4
**Upper B**
- Pull-up progression
- Incline Dumbbell Press
- Lat Pulldown
- Seated Row
- Pec Deck
- Shoulders
- Arms

### Day 5
**Full Body**
- Goblet Squat
- Hip Thrust
- Dumbbell RDL
- Lat Pulldown
- Dumbbell Bench Press
- Lateral Raises
- Core

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Progressive Web App (PWA)
- Service Worker
- Web App Manifest
- LocalStorage

No backend or database is required.

## 🔒 Privacy

LiftLog does not require an account.

Workout data is stored locally in the browser using `localStorage`.

Your workout history is not sent to a server.

## 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/liftlog.git
