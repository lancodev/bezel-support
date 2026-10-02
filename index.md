---
title: Bezel support
---

# Bezel for Stream Deck

Bezel controls your monitor from Stream Deck over DDC/CI. It covers input source, brightness, contrast, volume, color presets and power. On monitors that support them, it also handles picture-by-picture / picture-in-picture layouts and USB/KVM switching.

- [Get help or report a bug](https://github.com/lancodev/bezel-support/issues/new/choose)
- [Privacy policy](privacy.html)
- [End User License Agreement](eula.html)

## Requirements

- Stream Deck app 7.5 or later
- macOS 13 or later (Apple silicon or Intel), or Windows 10 or later (x64 or Arm64)
- A monitor with DDC/CI enabled in its on-screen menu, connected directly or through a dock/adapter that passes DDC/CI through

## Troubleshooting

**Keys show an error or never update**
1. Open your monitor's on-screen menu and make sure **DDC/CI** is turned on.
2. Connect directly to the monitor if you can. Some docks, KVMs, HDMI adapters and DisplayLink devices don't pass DDC/CI through.
3. If you have more than one monitor, open the key's settings and pick the display explicitly instead of **Default display**.
4. Restart the Stream Deck app.

**PiP/PbP or USB/KVM keys do nothing**
These features use manufacturer-specific commands and only work on monitors that support them. The USB/KVM key only works while picture-by-picture or picture-in-picture is on. With it off, the monitor's USB ports follow the primary input.

**A value on a key is out of date**
Bezel polls the monitor in the background and watches for changes made from the monitor's own buttons. Touching a Stream Deck + dial or pressing the key forces a refresh. You can change the poll interval in any key's settings.

## Reporting a problem

Please [open an issue](https://github.com/lancodev/bezel-support/issues/new/choose) and include:
- your operating system and Stream Deck app version
- your monitor model and how it's connected (cable, dock, adapter)
- what you pressed, what you expected, and what happened
- the plugin log files, if you can. They're in the `logs` folder inside the plugin folder:
  - macOS: `~/Library/Application Support/com.elgato.StreamDeck/Plugins/com.lancodev.bezel.sdPlugin/logs`
  - Windows: `%APPDATA%\Elgato\StreamDeck\Plugins\com.lancodev.bezel.sdPlugin\logs`

Issues are public, so please don't post personal information. Most issues get a response within 2 business days.

Bezel is an independent product. It is not affiliated with, endorsed by, or sponsored by any monitor manufacturer. All product names and trademarks belong to their respective owners.
