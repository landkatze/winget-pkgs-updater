# winget-pkgs-updater
Scheduled [winget-pkgs](https://github.com/microsoft/winget-pkgs) updater for various packages (based off ttps://github.com/michidk/winget-updater).
- `updater.yml` runs every 6 hours using [Komac](https://github.com/russellbanks/Komac) to open manifest updates as pull requests.
- `keepalive.yml` runs every month checking the `KOMAC_TOKEN` is still valid and ensures schedules aren't disabled for inactivity.
- `dependabot.yml` runs every week, bumping the pinned `actions/checkout` commit if a newer release exists.

## packages
| identifier | upstream |
| --- | --- |
| `alecdotdev.Markpad` | https://github.com/sftwrdotdev/Markpad |
| `autobrr.mkbrr` | https://github.com/autobrr/mkbrr |
| `autobrr.upbrr.cli` & `autobrr.upbrr.gui` | https://github.com/autobrr/upbrr |
| `Blur009.BlurAutoClicker` | https://github.com/Blur009/Blur-AutoClicker |
| `DonutWare.Fladder` | https://github.com/DonutWare/Fladder |
| `MartinDvorak.MindForger` | https://github.com/dvorka/mindforger |
| `martinrotter.RSSGuard5` | https://github.com/martinrotter/rssguard |
| `oldj.switchhosts` | https://github.com/oldj/SwitchHosts |
| `qarmin.krokiet` & `qarmin.krokiet.vulkan` | https://github.com/qarmin/czkawka |
| `QGIS.QField` | https://github.com/opengisch/QField |
