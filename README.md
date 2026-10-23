# StudyPilot — Voice-First Study Companion

StudyPilot is a responsive hackathon prototype that helps students plan tasks, focus in timed sessions, and see progress. It includes a browser-based voice-input experiment where supported.

> **Important:** This is an independent prototype, not an official Amazon product. It does not connect to Alexa+, Fire TV, Ring, Bee, or any Amazon API. Present it honestly as a concept/prototype unless you add and test a real integration.

## Features
- Add, complete, and delete study tasks
- Tasks and focus minutes persist in the browser using `localStorage`
- 25-minute focus timer, 15-minute session, and 5-minute break
- Daily completion percentage and focus-minute stats
- Optional browser speech recognition (support depends on browser/device)
- Responsive desktop and mobile layout

## Run locally
Requirements: Node.js 18+ recommended.

```bash
npm start
```

Open http://localhost:5001

No npm packages are required.

## Project structure
- `server.js` — simple Node.js static web server
- `public/index.html` — app layout
- `public/styles.css` — responsive styling
- `public/app.js` — task list, timer, progress, voice input

## Suggested next steps for the hackathon
1. Add screenshots or a short demo video to the Devpost project page.
2. If the event requires an Amazon product/service integration, implement and test the required integration before claiming it is integrated.
3. Add your own team details and a clear explanation of the problem, solution, and future plans.

## Suggested Devpost copy

### Tagline
A calm, voice-friendly study planner that helps students turn big goals into focused sessions.

### Inspiration
Students often have many things to study but struggle to decide what to do first and stay focused. StudyPilot makes planning and focused work feel simpler.

### What it does
StudyPilot lets students create a task list, mark work complete, run short focus sessions, and track daily progress. Where supported, users can add a task with browser speech recognition.

### How we built it
We used HTML, CSS, vanilla JavaScript, and a small Node.js HTTP server. The prototype stores tasks and focus totals in browser local storage, so no database or account is required.

### Challenges we ran into
We aimed to keep the experience simple while making it responsive across screen sizes. We also handled browser differences for speech recognition and made the core task and timer features work without voice support.

### What's next
We would like to test the experience with students, add reminders and account sync, improve accessibility, and explore a real voice-assistant integration if supported by the hackathon's rules and APIs.

### Built with
Node.js, JavaScript, HTML, CSS, Web Speech API (optional)
