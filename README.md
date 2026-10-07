# 📱 Kiranbjadhav - Mobile Utility Hub

> A lightweight, single-file, 100% viewport-fitted 5-in-1 multi-tool Progressive Web App (PWA) designed specifically for Android smartphones.

---

## 🌟 Overview

**Kiranbjadhav** is an ultra-responsive, mobile-first utility hub engineered to give users the feel of a native Android application directly inside the browser. It locks to the exact height of the mobile display (`100dvh`), eliminating unwanted page bounces, horizontal scrollbars, and body jitter.

Whether you need quick calculations, comprehensive age and date insights, a scratchpad for your thoughts, a reliable offline alarm, or a millisecond-precision stopwatch, this app bundles it all into one zero-dependency file.

---

## ✨ Features

### 1. 🧮 Smart Calculator
- **Full Viewport Auto-Fit:** The 5×4 keypad dynamically expands to fill 100% of the available vertical screen space without scrolling.
- **Arithmetic Engine:** Addition, subtraction, multiplication, division, percentage (`%`), decimal support, and instant backspace.
- **History Drawer:** Keep track of recent calculations with one-tap recall and clear functionality.

### 2. 🎂 Age & Date Suite (5 Sub-Calculators)
- **Exact Age & Life Stats:**
  - Chronological breakdown: Years, Months, and Days.
  - Live ticking counter down to the exact second.
  - Western Sun Sign & Chinese Zodiac animal with personality traits.
  - Next birthday countdown and weekday predictions for the next 5 years.
  - Biological lifetime statistics: total heartbeats, breaths taken, and estimated hours spent sleeping.
- **Age Comparison:** Compare two birthdates side-by-side to see who is older, the precise gap in years/months/days, and total difference in days.
- **Date +/- Calculator:** Add or subtract days, weeks, months, or years to any date with instant target date generation.
- **Life Milestones:** Computes your 6-month half-birthday, 10,000th and 20,000th days on Earth, 1-billionth second landmark (~31.7 years), and milestone adult birthdays (18, 21, 50, 60).
- **Pet Age Converter:** Specialized age converters for Dogs (Small, Medium, Large breed growth curves) and Cats into human-equivalent years, along with life stage classifications.

### 3. 📝 Smart Notepad
- **Instant Search:** Filter your notes in real time by title or body text.
- **Persistent Storage:** Auto-saves automatically to the browser’s `localStorage`—no login or internet needed.
- **Pin & Organize:** Pin high-priority notes to the top of the list.
- **One-Tap Clipboard Copy:** Copy note content directly to your clipboard with haptic feedback.

### 4. ⏰ Alarm Clock
- **Live Digital Clock:** Prominent 12-hour AM/PM real-time display with current date.
- **Custom Scheduling:** Set multiple labeled alarms with individual active toggles.
- **Zero-Asset Sound Engine:** Uses the HTML5 **Web Audio API** to synthesize an escalating multi-tone chime—rings reliably offline without requiring external MP3 files.
- **Ringing Screen & Vibration:** Full visual ringing interface with Dismiss/Snooze controls and native vibration support on compatible Android devices.

### 5. ⏱️ Stopwatch & Lap Timer
- **High-Precision Counter:** Tracks hours, minutes, seconds, and milliseconds (`00:00:00.00`).
- **Ergonomic Controls:** Large Start, Pause, Resume, Reset, and Split Lap buttons.
- **Visual Lap Analytics:** Color-codes your fastest lap (green) and slowest lap (red) automatically.

---

## 📱 Mobile-First Architecture

- **`100dvh` Viewport Locking:** Respects mobile dynamic address bars and virtual keyboard resizing.
- **Safe Area Inset Support:** Padded for devices with camera notches, punch-holes, and gesture navigation bars (`env(safe-area-inset-top)` / `env(safe-area-inset-bottom)`).
- **Contained Tab Scrolling:** Only the active tool content scrolls internally (`overflow-y-auto no-scrollbar`); headers and bottom navigation remain fixed in place.
- **Haptic & Visual Feedback:** Touch ripple scale transforms on buttons (`active:scale-95`) and Android `navigator.vibrate()` integration.

---

## 🚀 Quick Start / Installation

Because the application is packaged as a single self-contained HTML file, no installation, compilation, or server setup is required.

### Method 1: Run Locally
1. Download or clone this repository:
   ```bash
   git clone [https://github.com/your-username/kiranbjadhav-utility-hub.git](https://github.com/your-username/kiranbjadhav-utility-hub.git)
