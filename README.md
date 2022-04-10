# KioskPi

A tool based on [pi-gen](https://github.com/RPi-Distro/pi-gen)
to build simple Raspberry Pi OS images for Web-Based Kiosks.

Uses GTK-WebKit on plain X, without any desktop environments or Chromium for performance.

Also listens to TV's remote signals via HTMI-CEC and translates them as key strokes, simple for web app to understand.

## Usage

Use Ubuntu or other Debian-based systems

```bash
git clone --depth 1 https://github.com/deltazero-cz/kiosk.pi.git
./init.sh
# make changes to config (file)
# make changes to stage2-kiosk
sudo ./build.sh
```

For further details refer to:
- pi-gen: https://github.com/RPi-Distro/pi-gen
- my article: https://medium.com/@deltazero/making-kioskpi-custom-raspberry-pi-os-image-using-pi-gen-99aac2cd8cb6

## Enjoy 🥂
