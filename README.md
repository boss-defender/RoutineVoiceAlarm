# 🎙️ RoutineVoice (Android 12 - 15+)

A breathtaking, un-ignorable daily routine alarm application built with Flutter. Unlike standard alarms that just beep, **RoutineVoice** acts as a hybrid between a native system alarm and a background music streaming service to ensure your tasks are literally shouted out loud—even if your phone is in a deep sleep.

Featuring a premium **Liquid Glass (Glassmorphism)** user interface, this app ensures you never miss a daily commitment again.

---

## 🌟 What Makes It Special? (The Hybrid Secret)
Most modern routine apps fail because Android aggressively forces background apps to go to sleep. **RoutineVoice** completely bypasses this block by using a genius workaround: it acts like a **Music Player Foreground Service** (think Spotify) combined with an **OS Kernel Alarm Manager**. 

When it's time for a task, the app gains total clearance to wake your screen up, bypass the lock screen, and scream your tasks at maximum volume!

---

## 🔥 Key Features

* **🗣️ Multi-Lingual Male Voice Alarms:** Standard ringtones are boring. RoutineVoice recites your exact task title in a clear, high-volume male voice. It automatically detects and supports both **English** and **Bangla (বাংলা)** text.
* **🔁 The 0.7-Second Infinite Loop:** When an alarm triggers, it screams your task -> pauses for exactly 0.7 seconds -> screams it again. This cycle loops relentlessly for **3 minutes** or until you hit the cancel button.
* **💎 Liquid Glass UI:** A stunning visual experience utilizing premium frosted-glass containers (`BackdropFilter`), soft glowing border gradients, and ultra-smooth animations.
* **☀️/🌙 Dynamic Theme Switcher:** Features a smooth Light/Dark mode toggle. The icon dynamically morphs between a **Sun** (in light mode) and a **Moon** (in dark mode).
* **⏰ 1-Minute Precision Picker:** Full freedom over your schedule! No rigid 5-minute block restrictions. Supports a clean 12-hour format with clear AM/PM selection.
* **🛡️ Swipe-Away Armor:** Even if you swipe the app out of your recent tasks/background tray or reboot your device, the system alarms stay registered in the phone's memory.

---

## 📲 Required Permissions
To function exactly like your phone's built-in hardware clock, the app will request the following system keys on its first launch:
1. **Schedule Exact Alarm** – For pinpoint precision timing.
2. **Ignore Battery Optimizations** – To stop Android from putting the app into a deep sleep.
3. **System Alert Window** – To pop up gracefully in front of other active apps.
4. **Wake Lock & Turn Screen On** – To wake up a completely black, locked screen.
5. **Post Notifications** – To show a beautiful media control window on your lock screen.

---

## 🛠️ How To Use It

1. **Launch & Allow:** Open the app and grant all the requested system permissions (this is crucial for the background alarm system to function!).
2. **Set a Task:** Click the add button, write your routine task (in English or Bangla), and select your exact time using the 12-hour AM/PM picker.
3. **Choose Your Vibe:** Tap the **Sun/Moon icon** at the top right to instantly switch between a gorgeous frosty light layout or a futuristic glowing dark layout.
4. **The Alarm Experience:** When the clock hits your scheduled time, your phone screen will light up, a full-screen glass window will appear, and the male voice will start looping your task. Tap **"Cancel"** to hush the assistant!

---

## 🏗️ Technical Stack

* **Framework:** Flutter (Cross-platform)
* **Target OS:** Android 12 to Android 15+ 
* **State Management & Background:** Android Alarm Manager Plus & Text-to-Speech (`flutter_tts`) Engine
* **Design Philosophy:** Glassmorphism / UI Acrylic Blur

---


