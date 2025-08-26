# JC3248W535-3.5inch-HA-remote
Configuration for the JC3248W535 3.5-inch Home Assistant remote.
Note: earlier revisions referred to the board as JC4832W535.

## Structure

This project now uses ESPHome packages to keep the configuration modular:

- `remote-control.yaml` – entry point that pulls in other files.
- `core.yaml` – device configuration, networking and LVGL hardware.
- `ui/room_page.yaml` and `ui/house_page.yaml` – individual page layouts.

Common button properties live in `ui/button_template.yaml` and are included for each
button, reducing repetition and making it easier to add more widgets.
