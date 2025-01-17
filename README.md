# 💹 Downtime

## 💬 How to use ?

0. Fork this repository and enable GitHub actions on it
1. Edit [config.yml](config.yml) to add your hosts and settings
2. (optional) Go to repository `settings` and enable GitHub pages

You're done !

## ✨ Features

* Use default `GITHUB_TOKEN` (no need to create a any token, so no security risks for your account, yay 🎉)
* Status displayed with SVG images will auto-update auto-magically
* Connection tests history is stored as JSON for easy reuse
* Private repositories are supported with GitHub Pages enabled
* Easily deployed, easily tweakable
* Supports multiple commands
  * Use `curl` for your web endpoints to get both status and response time
  * Use `ncat` for any host/port/protocol to get both status and response time
  * Use `telnet` for any host/port/protocol to get status

See [USAGE.md](USAGE.md) for more informations.

## 🚥 Current status

<!-- <downtime-status> -->
![Google](status/google.com-443.svg)
![Downtime repository](status/github.com-lowlighter-downtime-443.svg)
![Google DNS](status/8.8.8.8-53.svg)
![Unavailable website](status/unavailable.website.com-443.svg)
<!-- <downtime-status/> -->
