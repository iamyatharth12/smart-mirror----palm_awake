Minimal smart mirror software with palm-based wake detection. The UI stays hidden like a normal mirror and appears only when a palm is detected, with edge-aligned widgets and a clean, distraction-free design.

What I Built

A presence-aware smart mirror UI

Palm-based wake-up logic (no gestures or touch)

Minimal interface with widgets only on the edges

Blank center area to preserve the mirror feel

Auto-hide after inactivity

This project focuses only on software, not physical mirror construction.

How It Works

The browser accesses the camera

If a palm/hand is detected → UI becomes visible

If no hand is detected for ~5 seconds → UI hides

No complex gestures (pinch, drag, etc.) are used to keep it stable

UI Design

Center of the screen is intentionally empty

Widgets are aligned to the left and right edges

Uses a subtle cyan accent color

No RGB effects or heavy animations

Static widgets for better performance on low-end hardware

Tech Stack

HTML

CSS
