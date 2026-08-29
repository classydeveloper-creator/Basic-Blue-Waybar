# Basic Blue Waybar
#### -Bare bones basics just to function (Built for hyprland)-
---
## Built for [YumHyprConfig](https://github.com/classydeveloper-creator/YumHyprConfig) ⚙️
#### You should edit this to your theme design!
---
This Includes:
- Tray
- Bluetooth
- Hyprland active window
- Media Control
- Audio Control
- Clock
---
## Waybar Example:
![example](https://github.com/classydeveloper-creator/BlueYum-waybar/blob/main/WaybarExample.png?raw=true)
---
## Needed Software:
- **hyprland/window**:	Displays the title of the currently active window on the left side of the bar.
- **tray:**	System tray area holding background app icons *(like a network manager or Discord)*.	Built into Waybar
- **bluetooth:**	Shows your Bluetooth connection status and device states; opens Blueman when clicked.	blueman, bluez, bluez-utils
- **mpris:**	Centers media playback info *(artist/title)* for active media players *(like Spotify or web browsers or etc.)*.	playerctl
- **wireplumber:**	Displays your current audio volume percentage and opens PulseAudio Volume Control *(pavucontrol)* on click. wireplumber, pavucontrol
- **clock:**	Shows the current time and opens a terminal-based calendar (Calcurse) inside Konsole when clicked.
---
Needed Programs Install Command:
```bash
sudo pacman -S --needed waybar calcurse pavucontrol blueman bluez bluez-utils playerctl
```
---
#### YumDev 🎩 *Intented for (hyprland + cachyos)* **@2026**