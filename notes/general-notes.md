Here’s a concise set of notes that you can save in your working folder:

---

### **GL4000 MIDI Mapping Notes**

#### **General Information**
- **Source**: MIDI Client `24:0`
- **Channel**: All messages are on **Channel 1**.
- **Events**:
  - **Note On**: Sent when a control is activated (e.g., button pressed, fader toggled).
  - **Note Off**: Sent when the control is deactivated.
- **Velocity**: Fixed at `63` (medium intensity).

---

#### **MIDI Note Mapping**
- **Notes and Corresponding Controls**:
  - `24 (C1)`: Channel 1 Toggle
  - `25 (C#1)`: Channel 2 Toggle
  - `26 (D1)`: Channel 3 Toggle
  - ...
  - `87 (D6)`: Channel 64 Toggle

- **Octave Ranges**:
  - Notes `24-35`: Channels 1-12
  - Notes `36-47`: Channels 13-24
  - Notes `48-59`: Channels 25-36
  - Notes `60-71`: Channels 37-48
  - Notes `72-87`: Channels 49-64

---

#### **Usage**
- Use these MIDI notes to:
  - Map controls in a DAW or lighting software.
  - Debug channel toggles and fader actions.
  - Automate tasks by triggering these notes via software.

---

#### **Quick Example**
- If you see:
  ```
  Note on 0, note 48, velocity 63
  ```
  It means **Channel 25 Toggle Activated**.
- If you see:
  ```
  Note off 0, note 48
  ```
  It means **Channel 25 Toggle Deactivated**.

---

Copy and save this in your working folder for easy reference. Let me know if you'd like further refinements!
