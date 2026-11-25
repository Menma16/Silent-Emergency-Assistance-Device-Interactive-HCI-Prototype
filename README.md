# Silent Emergency Assistance Device — Interactive HCI Prototype

An interactive Human-Computer Interaction (HCI) web prototype built for **CS212 Lab 6** at USTP. It simulates a pocket-sized, coin-scale silent emergency remote paired with an iOS companion experience for discreet distress signaling and usability evaluation.

## Key Features
- **Coin-Scale Physical Remote Simulation:**
  - Recessed right-edge blue power/standby button (`OFF` ↔ `BLUE_SEARCHING` / `BLUE_CONNECTED`).
  - Top `12 o'clock` pinhole status LED (`Dark` when off, `Blue` when powered/connected, `Green` when silent emergency & recording are active).
  - Recessed magenta center button to trigger a silent emergency alert—and press again to stop/end the alert and save the recording without powering off or re-pairing Bluetooth.
- **Interactive iPhone Companion:**
  - Starts **Screen OFF** with a side power button wake cue, waking into a **Lockscreen** with Notification Center and **swipe-up-to-unlock** animation to the **Home Screen**.
  - Swipe-down access to **Notification Center** (with swipe-to-dismiss cards and clear option) and **Control Center** (with manual Bluetooth toggle).
  - **SilentGuard** app view featuring BLE status, live GPS coordinates (with fallback), animated audio waveform, live ticking `MM:SS` recording timer, and trusted contact dispatch states, plus **Voice Memos** clip saving.
- **Evaluator & Usability Testing Tools:**
  - Built-in **Time on Task (ToT)** stopwatch, **Evaluator Guide & Task Prompts**, **Event & Timing Log** with timestamps, and a clear **Simulated vs. Implemented** disclosure.

## Disclaimer
This web application is an interactive HCI usability prototype. Bluetooth Low Energy (BLE) pairing, external contact alert dispatch, and encrypted background audio capture are simulated for evaluation and demonstration purposes.
