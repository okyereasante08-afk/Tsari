# DayFlow
DayFlow is a sleek PWA designed to optimize your daily rhythm. Featuring an iOS-inspired glassmorphism UI, it combines habit tracking with a Dynamic Rotation System for subjects and tasks. With integrated YouTube focus streams and a Pomodoro timer, it’s built to reduce friction and keep you in flow. Master your rhythm with DayFlow.
## DayFlow: Master Your Daily Rhythm

**DayFlow** is a high-performance, minimalist habit tracker and productivity engine built as a Progressive Web App (PWA). Designed with a "system-first" mindset, it combines schedule blocking, habit tracking, and focus tools into a single, sleek "Glassmorphism" interface.

---

### 🚀 Features

* **Dynamic Subject Rotation:** Automatically cycles through study topics or project types (e.g., alternating between Python and Web Design) to balance cognitive load.
* **Integrated Focus Music:** A persistent, lightweight player to stream Lofi, Jazz, or Deep Focus audio directly from YouTube without leaving the app.
* **Interactive Focus Timer:** A built-in Pomodoro-style timer linked to your specific subjects for granular time tracking.
* **PWA Ready:** Installable on iOS, Android, and Desktop for a native-app feel with offline-first performance.
* **Intelligent "Now/Next" HUD:** A real-time hero section that keeps you focused on your current task while previewing what’s ahead.
* **Privacy Centric:** All data is stored locally in your browser—no accounts required, no tracking involved.

---

### 🛠️ Tech Stack

* **Frontend:** Vanilla HTML5, CSS3 (Custom Variables & Glassmorphism), JavaScript (ES6+).
* **Storage:** LocalStorage API for persistent, local-first data management.
* **Audio:** YouTube IFrame Player API for low-overhead background streaming.
* **UI/UX:** Inspired by Apple’s SF Pro design language for a premium, tactile feel.

---

### 📥 Installation

Since DayFlow is a PWA, you don't need an app store:

1. Navigate to the hosted URL in your browser.
2. **On iOS:** Tap the "Share" icon and select **"Add to Home Screen."**
3. **On Android/Chrome:** Click the **"Install"** button in the app banner or the browser menu.

---

### 📖 How to Use

1. **Define Your Blocks:** Set your daily routine in the `DEF_SCH` constant within the script.
2. **Customize Subjects:** Update the `DEF_SUBJ` object to track the specific tasks relevant to your curriculum or career.
3. **Stay in Flow:** Use the **Today** view to check off blocks as you complete them and the **Focus** tab to dive into deep work sessions.

---

### ⚖️ License

Distributed under the **MIT License**. See `LICENSE` for more information.
