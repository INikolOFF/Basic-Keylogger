# Auto Keyboard & Mouse Script

This Python script automates keyboard and mouse actions and demonstrates base64 encoding/decoding with subprocess execution.
It also has a GUI launch placeholder (not implemented yet).

## Features

- Simulate keyboard key presses (`W` and `S`).
- Auto-click mouse left button at a user-defined interval.
- Encode and decode payloads with `base64`.
- Run decoded commands using `subprocess`.
- Uses `threading` for future multi-threading support.

## Requirements

- Python 3.x
- `pynput` library for controlling mouse and keyboard:

```bash
pip install pynput
