# APPy Family

Mobile-first prototype designed to support parents in managing family activities,
discovering local events, and building real-life connections with other caregivers.

Originally developed as a university group project for the Human–Computer Interaction course,
this repository hosts the frontend implementation published for portfolio purposes.

---

## Project Focus

The goal of APPy Family is to reduce parents’ mental load by centralising:
- children’s activities
- shared calendars
- local events and centres
- community interaction

The project prioritises **interaction design, information architecture, and usability**
over production-level backend complexity.

---

## Design Approach

The application was developed following a user-centred design process:
- user needs identified through interviews and needfinding
- iterative prototyping (paper → mid-fi → hi-fi)
- usability-driven refinements based on heuristic evaluation

The final prototype explores how different features interact within a realistic mobile flow.

---

## Key Features & Screens

### Home (Event Discovery)
- Recommended and nearby events
- Contextual suggestions explaining why events are shown
- Join / leave events directly from the feed
- Local search and filtering
- Actions reflected across the app (e.g. Calendar)

### Calendar
- Unified view of personal activities and joined events
- Day / week / month views
- Event creation via time-slot selection
- Event details and participation management
- Colour-coded categories for visual clarity

### Community
- Browse and search other parents
- Participate in blog/forum-style discussions
- Create events or posts
- Rank system based on user connections

### Profile
- Personal information overview
- Created and joined events
- User-generated content (blogs, events)
- Social ranking based on engagement

### Global Navigation
- Persistent top navigation for notifications and messages
- Bottom navigation optimised for mobile use
- Consistent access to core features from all screens

---

## Data & Persistence

No real backend is implemented.

Application data is persisted using **localStorage** to simulate backend behaviour and enable:
- state continuity across views
- interaction testing
- usability evaluation without server-side complexity

This choice was intentional to keep the focus on UX, flows, and frontend logic.

---

## Tech Stack

- React
- React Router
- React Bootstrap
- React Big Calendar
- JavaScript (ES6)
- CSS
- LocalStorage (simulated persistence)

---

## Running the Project Locally

```bash
npm install
npm start

The app runs in development mode at
http://localhost:3000

## Notes

The application is mobile-first and designed for smartphone usage

Desktop rendering is not optimised by design

The project is intended as a prototype, not a production-ready application

## Author

Published on GitHub by Katia Grasso for portfolio and professional purposes.
