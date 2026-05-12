<!-- INKOGN — GitHub Organization Profile README -->
<!-- Path: .github/profile/README.md -->

<div align="center">

<img src="./assets/inkogn-logo.png" alt="Inkogn" width="100" />

# INKOGN

[![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)]()
[![Firmware](https://img.shields.io/badge/firmware-open%20source-green?style=flat-square)](https://github.com/Inkognapp/firmware)
[![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-black?style=flat-square)]()

</div>

---

<table>
<tr>
<td width="50%" valign="top">

## 🇵🇱 Polski

Inkogn to gra, która dzieje się w prawdziwym świecie.

Nosisz przy sobie małe urządzenie. Wychodzisz z domu — ono się budzi, skanuje otoczenie, zbiera stworki w miejscach które odwiedzasz i automatycznie walczy z innymi graczami których spotykasz. Bez patrzenia w telefon.

Trzy gatunki na start:
**VEXOR** — elektryczny chaos · **LURK** — mistrz cienia · **GRAVN** — niezniszczalny

Dostępne na dwa sposoby:
- 📱 Aplikacja mobilna (iOS + Android)
- 🎮 Oficjalne urządzenie Inkogn z ekranem i przyciskami

Firmware urządzenia jest **open source** — możesz wgrać go na własny ESP32-S3 i dołączyć do gry.

</td>
<td width="50%" valign="top">

## 🇬🇧 English

Inkogn is a game that happens in the real world.

You carry a small device with you. When you leave home it wakes up, scans the area, catches creatures at places you visit and automatically battles other players you encounter nearby. No need to look at your phone.

Three starting species:
**VEXOR** — electric chaos · **LURK** — master of shadows · **GRAVN** — unstoppable

Available two ways:
- 📱 Mobile app (iOS + Android)
- 🎮 Official Inkogn device with screen and buttons

The device firmware is **open source** — you can flash it onto your own ESP32-S3 and join the game.

</td>
</tr>
</table>

---

## Firmware — quick start

> **Requirements:** PlatformIO · ESP32-S3 dev board

```bash
git clone https://github.com/Inkognapp/firmware
cd firmware
cp config.example.h config.h   # set your device UUID and Wi-Fi credentials
pio run --target upload
```

Full documentation → [`firmware/README.md`](https://github.com/Inkognapp/firmware)

---

<div align="center">

[inkogn.app](https://inkogn.app) · [docs.inkogn.app](https://docs.inkogn.app)

<sub>Inkogn © 2026 · Device firmware open source · Platform & game logic proprietary</sub>

</div>
