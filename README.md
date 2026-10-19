# JK BMS Dashboard

Web viewer for the JK BMS monitor (ESP32 → EMQX Cloud MQTT).

- Connects over WebSocket (wss) to the EMQX broker and live-renders both battery packs (SOC, total voltage, current, power, 16 cell voltages, temperatures, flags, switches).
- The MQTT password is entered once in your browser and stored only in that browser's localStorage — it is never part of this repository.
- Subscribe-only; this hosted variant has no control (switch toggle) actions.

Hosted via GitHub Pages.