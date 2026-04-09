# Task: Voice-Controlled Smart Home App UI
**Project:** Responsive Voice Interface for "Aura Smart Home"
**Objective:** Designing intuitive UX for commands like "Turn off the lights".

---

## 1. UX Design Principles (Kyun Aisa Banaya?)
* **Visibility of System Status:** A dynamic soundwave animation (GIF/Lottie) appears when the user says "Hey Aura," confirming the app is listening.
* **Minimalist Design:** Only essential controls (Temperature, Lighting) are visible above the fold, to keep focus on the voice input.
* **Feedback & Confidence:** After a command, the app displays a confirmation text and plays a subtle sound (e.g., "Lights OFF, Aditya").

## 2. Dynamic Interaction Flow (User Journey)
1. **Trigger:** User says "Hey Aura" (App switches to listening mode).
2. **Command:** User says "Set thermostat to 22°C" (Voice is transcribed to text on-screen).
3. **Execution:** The 'Thermostat' card component animates from current temp to 22°C with a 'Green' color highlight.
4. **Conclusion:** Voice feedback says "Thermostat is now set to 22 degrees."

## 3. Top Voice Commands Handled
* **"Turn ON/OFF the kitchen lights."** (Triggering Relay Component)
* **"Increase volume by 10%."** (Media Slider Component)
* **"Run the 'Good Morning' scene."** (Macro/Sequence Component)

---
**Designed By:** Aditya Tripathi  
**Tools:** Figma Professional (Prototype)
**Status:** Interactive Voice Flow Complete
