# Costumized-conky-for-fedora

Minimal Conky system monitor config for Linux desktop customization — free to use, modify, and redistribute (Unlicense)

# Features
- **CPU Monitoring:** Total usage + per-core tracking with visual bars.
- **Memory & Swap:** Percentage and usage bars.
- **Disk Usage:** Tracks `/`, `/home`, and `/mnt/storage` (Data).
- **Network:** Real-time upload and download speeds.
- **Top Processes:** Live tracking of resource-heavy applications.

# Prerequisites
To ensure the theme renders correctly, you need the following:
* **Conky:** `sudo apt install conky-all` (on Debian/Ubuntu)
* **Font:** `DejaVu Sans Mono` (usually included in most Linux distros)

# If you don't have a conky config directory, create one:

bash:
# mkdir -p ~/.config/conky/
# cp conky.conf ~/.config/conky/conky.conf

launch:
# conky -c ~/.config/conky/conky.conf &

# Network Interface: 
If your speeds show 0, change wlp2s0 in the NETWORK section to your actual interface (found via ip link show).
Disk Paths: Update the /data section if your storage is mounted elsewhere.

## Preview

<p align="center">
  <img src="screenshot.png" width="700">
</p>
