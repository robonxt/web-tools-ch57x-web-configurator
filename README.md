# CH57x WebHID Keypad Configurator

Standalone, single-file browser tool to configure, live-test, and flash macro keypads built on WCH CH57x / CH552 microcontrollers (e.g., 3-key + 1-knob keypads, USB VID `0x1189`).

No native executable or driver installation required. Runs directly in Chrome and Edge using WebHID.

## Features
- **WebHID Flashing:** Directly programs hardware layers over USB vendor interface (`0xFF00:0x0001`).
- **Live Key Detection:** Real-time keypress and rotary encoder tracking.
- **LED Backlight Control:** Switch onboard lighting modes (Off, Backlight, Breathing, Shock, Strobe).
- **YAML Mapping Support:** Compatible with mapping files from [`ch57x-keyboard-tool`](https://github.com/kriomant/ch57x-keyboard-tool).
- **Custom Keys & Actions:** Keys, modifiers, mouse actions, media controls, chords, and custom key codes (`<100>`).

## Usage
Open `index.html` in Google Chrome or Microsoft Edge.
