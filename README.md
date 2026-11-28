# Blynx

Blynx is a turn signal and brake controller for kit cars and custom motorcycles:
self-canceling turn signals, hazards, brake lights with a backup circuit, running lights and
lamp-out warnings, set up over USB.

**Setup page: https://lewisfab.github.io/blynx/**

**Demo (no controller needed, any browser): https://lewisfab.github.io/blynx/?demo**

The page is one self-contained file (`index.html`): it loads nothing from the internet and talks
to the controller directly over USB-C (Web Serial). You can also save it and open it offline.

## Browser support

| Browser | Setup over USB | Instructions |
|---|---|---|
| Chrome or Edge on a Windows, Mac or Linux computer | yes | yes |
| Chrome 148+ on Android, USB-C to USB-C data cable | yes (not yet tested with a board) | yes |
| iPhone and iPad (any browser), Firefox, Safari | no | yes, view only |

## Report a problem

Use **Report a problem** at the bottom of the setup page (or "Still stuck?" at the end of
Troubleshooting in the instructions). It opens a new issue here with a short template and a
Details block already filled in: the page version, the controller's firmware, protocol and
hardware revision and its current faults (if connected), the vehicle type, and your browser and
operating system. It never includes your settings or the controller's serial number. You can
read and edit everything before you submit. You need a free GitHub account.

You can also open an issue directly: https://github.com/lewisfab/blynx/issues/new/choose
("Report a problem").

This repository holds only the published page; it is updated from the project's private
repository.

## License

Copyright (c) 2026 Lewis Fabrication LLC. All rights reserved. You may use the page and save
a copy for your own use with your own Blynx controllers; see [LICENSE](LICENSE).
"Blynx" and the Blynx logo are trademarks of Lewis Fabrication LLC.
