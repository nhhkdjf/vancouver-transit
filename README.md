# 🌊 Vancouver Transit Dashboard

> An all-in-one trip planning system built specifically for Vancouver — live weather, real-time transit, local events, smart route planning, and an AI-powered day generator.

🔗 **Live demo:** [vancouver-transit.netlify.app](https://vancouver-transit.netlify.app)

---

## 📸 Screenshots

> *(Add screenshots here after uploading — drag images directly into the README editor on GitHub)*

---

## ✨ What makes this different from Google Maps

| Feature | Google Maps | Vancouver Transit |
|---|---|---|
| Live transit status | ✅ | ✅ |
| Weather-aware routing | ❌ | ✅ |
| Event crowding warnings | ❌ | ✅ |
| TransLink rush hour buffer | ❌ | ✅ |
| Multi-stop trip planner | ❌ | ✅ |
| Generate full day itinerary | ❌ | ✅ |
| Local Vancouver events | ❌ | ✅ |
| Vancouver vibe suggestions | ❌ | ✅ |
| Share trip via link | ❌ | ✅ |
| 11 languages | ❌ | ✅ |

---

## 🚀 Features

### 🌧 Live Weather
- Real-time temperature, feels like, rain chance, UV index
- Sunrise & sunset times
- Hourly forecast
- Smart advisory ("Bring an umbrella — rain expected today")
- **Vancouver Vibe Suggestions** — rainy day? The app recommends VPL, Kafka's Coffee, or the VAG. Sunny? Kits Beach and the Seawall.

### 🚇 Transit Status
- Live status for all major lines — Expo, Canada, Millennium, Evergreen
- B-Lines: 99, R4, R5
- Bus routes: 49, 25
- SeaBus & West Coast Express
- Highlights routes used when you search a trip

### 🎟 Events Today
- Real Vancouver events from Ticketmaster — concerts, Canucks games, theatre
- Filtered to remove internal/irrelevant records
- Transit impact badges — know when to expect crowds
- **Hyper-local events** — free farmers markets, UBC museum Tuesdays, Granville Island, Lynn Canyon

### 🗺 Route Planner
- Google Maps autocomplete for any Vancouver location
- Live transit directions drawn on a dark navy map
- Step-by-step instructions with bus/SkyTrain lines
- **Delay prediction** — risk score based on weather + rush hour + events
- **TransLink Buffer** — automatically adds extra time at busy hubs like Commercial-Broadway during rush hour

### 🗓 Trip Planner Calendar
- Monthly → Weekly → Daily zoom levels
- **Day briefing** — weather forecast + events for your specific planned date
- Add multiple stops with From, To, leave time, arrive time, bus route
- **Auto-suggested route** — type From & To, app fills in the best transit route and arrive time automatically
- **Suggested leave time** with "Use this time" button
- Numbered stops shown on a map with routes in different colors
- Full step-by-step directions for each leg of your trip
- Set reminders 5, 15, or 30 minutes before each stop
- Save plan — shows as green dot on calendar
- **Share trip** — generate a link, friends open it and see your exact plan

### ✨ Generate My Trip
- Pick your time window, starting location and vibe
- Vibes: 🌿 Outdoor · ☕ Cafe & study · 🎨 Culture · 🍜 Food tour · 🎭 Events · 🏖 Chill
- App generates a full Vancouver day automatically
- Weather-aware — rainy day gets indoor suggestions, sunny day gets outdoor spots
- Transit-timed — every stop includes which bus/SkyTrain to take
- **Plan confidence score** — 0–100% based on weather, rush hour, and events
- One click to add the generated itinerary to your trip stops

### 📱 Mobile App Layout
- Completely different layout on mobile — feels like a native app
- Bottom navigation bar — Transit · Weather · Map · Events
- Big readable cards, no zooming required
- Full route planner on mobile with autocomplete

### 🌏 11 Languages
English · French · Chinese (Simplified) · Chinese (Traditional) · Japanese · Korean · Vietnamese · Filipino · Punjabi · Spanish · Farsi

---

## 🛠 Built with

| Technology | Purpose |
|---|---|
| HTML · CSS · JavaScript | Core — no frameworks, built from scratch |
| OpenWeatherMap API | Live Vancouver weather |
| Ticketmaster Discovery API | Real Vancouver events |
| TransLink Open API | Transit status |
| Google Maps JavaScript API | Interactive map + directions |
| Google Places API | Location autocomplete |
| Netlify | Hosting + deployment |

---

## 📂 Project structure
```
vancouver-transit/
├── index.html        ← Main dashboard
├── planner.html      ← Trip planner calendar
├── about.html        ← About & how it works
├── morning.avif      ← Morning background photo
├── afternoon.avif    ← Afternoon background photo
├── evening.avif      ← Evening background photo
└── night.avif        ← Night background photo
```

---

## 🏃 How to run locally

No build process needed — just open the file!

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/vancouver-transit.git
```

2. Open `index.html` in Chrome using Live Server (VS Code extension)

3. That's it — no npm install, no setup, no terminal commands needed

---

## 🧠 What I learned building this

This was my **first ever coding project** — built from zero experience.

Over the course of building it I learned:
- HTML structure and semantic markup
- CSS layouts — flexbox, grid, responsive design, glassmorphism
- JavaScript — functions, async/await, fetch, APIs, localStorage
- How to read API documentation and connect real data sources
- Debugging with Chrome DevTools
- Deploying a real website with Netlify
- Product thinking — how to identify a real user problem and build toward solving it

---

## 💡 The problem this solves

Planning a day out in Vancouver means opening 5 different apps:
1. Weather app — will it rain?
2. TransLink app — is my bus running?
3. Google Maps — how do I get there?
4. Eventbrite/Ticketmaster — what's on?
5. Google Calendar — when do I need to leave?

**Vancouver Transit combines all of this into one place** — and adds intelligence that no single app has, like knowing that a Canucks game at Rogers Arena will pack the Expo Line, or that the 99 B-Line runs slow in rain, or that you should leave 15 minutes earlier during rush hour at Commercial-Broadway.

---

## 🌊 Built with ❤️ for Vancouver

*vancouver-transit.netlify.app*
