![GitHub release (latest by date)](https://img.shields.io/github/v/release/jumping2000/notifier?style=for-the-badge) ![GitHub Release Date](https://img.shields.io/github/release-date/jumping2000/notifier?style=for-the-badge) ![GitHub Releases](https://img.shields.io/github/downloads/jumping2000/notifier/latest/total?color=purple&label=%20release%20Downloads&style=for-the-badge) ![GitHub All Releases](https://img.shields.io/github/downloads/jumping2000/notifier/total?color=orange&label=Total%20downloads&style=for-the-badge)

# Appdaemon Notifier for Home Assistant
[![Buy me a coffee](https://cdn.buymeacoffee.com/buttons/bmc-new-btn-logo.svg)](https://www.buymeacoffee.com/jumping)<span style="margin-left:15px;font-size:28px !important;">Buy me a coffee</span></a>

### [Support our work with a donation](https://paypal.me/hassiohelp)

Notifier Centre for Home Assistant [jumping2000](https://github.com/jumping2000/appdaemon/commits?author=jumping2000)<br>
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/jumping2000/notifier)](https://github.com/jumping2000/notifier/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/jumping2000/notifier)](https://github.com/jumping2000/notifier/releases)
[![Hass.io][img-hassio]][link-hassio]
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg)](https://https://github.com/jumping2000/notifier/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/jumping2000/notifier)](https://github.com/jumping2000/notifier/issues)

Package-Notification-HUB-AppDaemon<br>
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/caiosweet/Package-Notification-HUB-AppDaemon)](https://github.com/caiosweet/Package-Notification-HUB-AppDaemon/releases)
![GitHub Release Date](https://img.shields.io/github/release-date/caiosweet/Package-Notification-HUB-AppDaemon)
[![Hass.io][img-hassio]][link-hassio]
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg)](https://github.com/caiosweet/Package-Notification-HUB-AppDaemon/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/caiosweet/Package-Notification-HUB-AppDaemon)](https://github.com/caiosweet/Package-Notification-HUB-AppDaemon/issues)

*Notifier is an [AppDaemon](https://github.com/home-assistant/appdaemon) app which works togheter with [Centro Notifiche](https://github.com/caiosweet/Package-Notification-HUB-AppDaemon) to sends text (Telegram, Push, WhatsApp), TTS Google and Alexa, VoIP notifications to you and/or your devices like PC, smartphone, pad, etc..*

<b>The app works with Appdaemon v4.x.-5.x</b>

## Installation

Steps to follow:
- Install [Appdaemon Container](https://hub.docker.com/r/acockburn/appdaemon) or [Appdaemon addon](https://github.com/hassio-addons/addon-appdaemon);
- enable [Appdaemon in HACS](https://hacs.xyz/docs/categories/appdaemon_apps#enable-appdaemon-apps-in-hacs);
- add [this repository in HACS](https://hacs.xyz/docs/faq/custom_repositories/);
- click the button below.

[![image](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=jumping2000&repository=notifier&category=appdaemon)

(👆 remember the <b>[my:](https://www.home-assistant.io/integrations/my/)</b> integration)



## Remember it!
The app doesn't work standalone but togheter with [Centro Notifiche](https://github.com/caiosweet/Package-Notification-HUB-AppDaemon)

<br>

**Ti piace questo package? Lascia una stella su Github e supportami per realizzarne altri!** <a href="https://www.buymeacoffee.com/jumping"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" height="20"></a>

<div align=center><img width = "450" src="img/star.png"/></div>

<br>

[img-hassio]:https://img.shields.io/badge/config_for-Hass.io-53c1f1.svg?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyLDE1LjVBMy41LDMuNSAwIDAsMSA4LjUsMTJBMy41LDMuNSAwIDAsMSAxMiw4LjVBMy41LDMuNSAwIDAsMSAxNS41LDEyQTMuNSwzLjUgMCAwLDEgMTIsMTUuNU0xOS40MywxMi45N0MxOS40NywxMi42NSAxOS41LDEyLjMzIDE5LjUsMTJDMTkuNSwxMS42NyAxOS40NywxMS4zNCAxOS40MywxMUwyMS41NCw5LjM3QzIxLjczLDkuMjIgMjEuNzgsOC45NSAyMS42Niw4LjczTDE5LjY2LDUuMjdDMTkuNTQsNS4wNSAxOS4yNyw0Ljk2IDE5LjA1LDUuMDVMMTYuNTYsNi4wNUMxNi4wNCw1LjY2IDE1LjUsNS4zMiAxNC44Nyw1LjA3TDE0LjUsMi40MkMxNC40NiwyLjE4IDE0LjI1LDIgMTQsMkgxMEM5Ljc1LDIgOS41NCwyLjE4IDkuNSwyLjQyTDkuMTMsNS4wN0M4LjUsNS4zMiA3Ljk2LDUuNjYgNy40NCw2LjA1TDQuOTUsNS4wNUM0LjczLDQuOTYgNC40Niw1LjA1IDQuMzQsNS4yN0wyLjM0LDguNzNDMi4yMSw4Ljk1IDIuMjcsOS4yMiAyLjQ2LDkuMzdMNC41NywxMUM0LjUzLDExLjM0IDQuNSwxMS42NyA0LjUsMTJDNC41LDEyLjMzIDQuNTMsMTIuNjUgNC41NywxMi45N0wyLjQ2LDE0LjYzQzIuMjcsMTQuNzggMi4yMSwxNS4wNSAyLjM0LDE1LjI3TDQuMzQsMTguNzNDNC40NiwxOC45NSA0LjczLDE5LjAzIDQuOTUsMTguOTVMNy40NCwxNy45NEM3Ljk2LDE4LjM0IDguNSwxOC42OCA5LjEzLDE4LjkzTDkuNSwyMS41OEM5LjU0LDIxLjgyIDkuNzUsMjIgMTAsMjJIMTRDMTQuMjUsMjIgMTQuNDYsMjEuODIgMTQuNSwyMS41OEwxNC44NywxOC45M0MxNS41LDE4LjY3IDE2LjA0LDE4LjM0IDE2LjU2LDE3Ljk0TDE5LjA1LDE4Ljk1QzE5LjI3LDE5LjAzIDE5LjU0LDE4Ljk1IDE5LjY2LDE4LjczTDIxLjY2LDE1LjI3QzIxLjc4LDE1LjA1IDIxLjczLDE0Ljc4IDIxLjU0LDE0LjYzTDE5LjQzLDEyLjk3WiIgZmlsbD0iI2ZmZmZmZiIgLz48L3N2Zz4K&maxAge=86400


[link-hassio]:https://home-assistant.io/hassio/
