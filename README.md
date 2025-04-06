# Eventify-Smart-Event-Scheduler-React.JS---Project

Eventify is a smart, responsive event scheduling web application built with React.js, where users can plan and organize their daily tasks and events with ease. The app intelligently suggests time slots based on priority, duration, and availability — helping users optimize their day effectively.

🎯 Features
------------
✅ Add/edit/delete tasks/events

✅ Drag & drop scheduling

✅ Calendar view (daily/weekly)

✅ Smart time slot suggestions based on priority

✅ Reminders & alerts (browser notifications)

✅ Event color tags (work, personal, urgent, etc.)

✅ Offline support (using localStorage or IndexedDB)


📂 Project Structure
---------------------
eventify/

│── public/

│── src/

│   ├── components/       # Reusable components (EventCard, Modal, Button)

│   ├── pages/            # Views like CalendarPage, AddEventPage

│   ├── context/          # Global state providers

│   ├── hooks/            # Custom hooks (e.g., useEventManager)

│   ├── utils/            # Helper functions

│   ├── services/         # (Optional) Firebase or notification services

│   ├── App.js

│   ├── index.js

│── README.md

│── .env

│── package.json



🛠 Tech Stack
--------------
Layer	-- Tools & Libraries

Frontend	-- React.js, Tailwind CSS, React DnD, Day.js

State Mgmt	-- React Context API or Redux

Calendar	-- UI	react-big-calendar or FullCalendar.io

Notifications	-- react-toastify, Web Notifications API

Date Handling	-- Day.js or date-fns

Persistence	-- localStorage / IndexedDB / Firebase

Deployment	-- Vercel / Netlify


🎯 Action Plan & Development Phases
------------------------------------
📌 Phase 1: Project Setup
--------------------------
✅ Create project using create-react-app or Vite

✅ Install dependencies:

✅ Configure Tailwind CSS

✅  Set up routing with React Router


📌 Phase 2: UI/UX Design & Wireframing
---------------------------------------

✅ Design layout with mobile-first responsiveness

✅ Use Tailwind for utility-based styling

✅ Create wireframes (Figma or Adobe XD)

🔹 Pages to Include

• Navbar + Sidebar

• Calendar view

• EventCard

• Add/Edit Event Modal

• Time Slot Suggestion UI


📌 Phase 3: Implementing Components
------------------------------------
✅ Show calendar with react-big-calendar

✅ Allow users to create, update, and delete events

✅ Implement event drag-and-drop functionality

✅ Show smart time suggestions based on:

• Free slots

• Event priority

• Duration


📌 Phase 4: Animations & Interactivity
---------------------------------------
✅  Manage events using Context API or Redux

✅  Store events in localStorage (or Firebase for advanced use)

✅  Trigger toast or browser notification before event start


📌 Phase 5: SEO Optimization & Performance
-------------------------------------------
✅  Theme toggle (light/dark mode)

✅  Add filters (e.g., show only Work or Personal events)

✅  Add reminder settings

✅  Polish responsiveness and animations


📌 Future Enhancements
-----------------------
🔹 Google Calendar integration

🔹 User authentication (login/signup)

🔹 Team collaboration (shared events)

🔹 AI suggestions (e.g., “Best time to take a break”)

🔹 Voice input to create events
