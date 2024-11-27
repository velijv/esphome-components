# ESPHome Custom Components


[contributors-shield]: https://img.shields.io/github/contributors/velijv/esphome-components?style=flat-square](https://img.shields.io/github/contributors/velijv/esphome-components?style=flat-square&color=rgba(24,188,242,0.1)&labelColor=rgba(0,200,83,0.2)&logo=gitconnected&logoColor=rgb(0,200,83)
[contributors-url]: https://github.com/velijv/esphome-components/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/velijv/esphome-components?style=flat-square](https://img.shields.io/github/forks/velijv/esphome-components?style=flat-square&color=rgba(0,184,212,0.1)&labelColor=rgba(0,184,212,0.2)&logo=gitextensions&logoColor=rgb(0,184,212)
[forks-url]: https://github.com/velijv/esphome-components/network/members

[stars-shield]: https://img.shields.io/github/stars/velijv/esphome-components?style=flat-square](https://img.shields.io/github/stars/velijv/esphome-components?style=flat-square&color=rgba(255,171,0,0.1)&labelColor=rgba(255,171,0,0.2)&logo=Githubsponsors&logoColor=rgb(255,171,0)


[stars-url]: https://github.com/velijv/esphome-components/stargazers
[issues-shield]: https://img.shields.io/github/issues/velijv/esphome-components?style=flat-square](https://img.shields.io/github/issues/velijv/esphome-components?style=flat-square&color=rgba(213,0,0,0.1)&labelColor=rgba(213,0,0,0.2)&logo=Github&logoColor=rgb(213,0,0)
[issues-url]: https://github.com/velijv/esphome-components/issues



[![Espressif](https://img.shields.io/badge/Espressif-e7352c.svg?logo=Espressif&logoColor=e7352c&labelColor=rgba(0,0,0,0)&color=rgba(231,53,44,0.1)&style=flat-square
)](https://github.com/espressif/) [![ESPHome](https://img.shields.io/badge/ESPHome-000?logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTI5IiBoZWlnaHQ9IjEyNSIgdmlld0JveD0iMCAwIDEyOSAxMjUiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTIwLjY4OSAxMjQuNjdDMTI1LjA4NCAxMjQuNjcgMTI4LjY4OSAxMjEuMDY1IDEyOC42ODkgMTE2LjY3SDEyOC42NzhWNjguNjdDMTI4LjY3OCA2NC4yNzU0IDEyNi4xNCA1OC4xMzE0IDEyMy4wMjUgNTUuMDE2N0w3MC4zNDIzIDIuMzM0MDVDNjcuMjI3NiAtMC43ODA2MiA2Mi4xMzk2IC0wLjc4MDYyIDU5LjAyNSAyLjMzNDA1TDYuMzQyMyA1NS4wMTY3QzMuMjM4MyA1OC4xMjA3IDAuNjg4OTY1IDY0LjI3NTQgMC42ODg5NjUgNjguNjdWMTE2LjY3QzAuNjg4OTY1IDEyMS4wNjUgNC4yOTQzIDEyNC42NyA4LjY4ODk2IDEyNC42N0g0MC4xNTU2VjQ1LjAyMjNDNDAuMTU1NiA0My4yNTE2IDQxLjU4NSA0MS44MjIzIDQzLjM1NTYgNDEuODIyM0g4Ni4wMjIzQzg3Ljc5MyA0MS44MjIzIDg5LjIyMjMgNDMuMjUxNiA4OS4yMjIzIDQ1LjAyMjNWNTcuODIyM0M4OS4yMjIzIDU5LjU5MjkgODcuNzkzIDYxLjAyMjMgODYuMDIyMyA2MS4wMjIzSDU5LjM1NTZWNjcuNDIyM0g4Ni4wMjIzQzg3Ljc5MyA2Ny40MjIzIDg5LjIyMjMgNjguODUxNiA4OS4yMjIzIDcwLjYyMjNWODMuNDIyM0M4OS4yMjIzIDg1LjE5MjkgODcuNzkzIDg2LjYyMjMgODYuMDIyMyA4Ni42MjIzSDU5LjM1NTZWOTMuMDIyM0g4Ni4wMjIzQzg3Ljc5MyA5My4wMjIzIDg5LjIyMjMgOTQuNDUxNiA4OS4yMjIzIDk2LjIyMjNWMTA5LjAyMkM4OS4yMjIzIDExMC43OTMgODcuNzkzIDExMi4yMjIgODYuMDIyMyAxMTIuMjIySDU2LjE1NTZDNTQuMzg1IDExMi4yMjIgNTIuOTU1NiAxMTAuNzkzIDUyLjk1NTYgMTA5LjAyMkM1Mi45NTU2IDEwNy4yNTIgNTQuMzg1IDEwNS44MjIgNTYuMTU1NiAxMDUuODIySDgyLjgyMjNWOTkuNDIyM0g1Ni4xNTU2QzU0LjM4NSA5OS40MjIzIDUyLjk1NTYgOTcuOTkyOSA1Mi45NTU2IDk2LjIyMjNWODMuNDIyM0M1Mi45NTU2IDgxLjY1MTYgNTQuMzg1IDgwLjIyMjMgNTYuMTU1NiA4MC4yMjIzSDgyLjgyMjNWNzMuODIyM0g1Ni4xNTU2QzU0LjM4NSA3My44MjIzIDUyLjk1NTYgNzIuMzkyOSA1Mi45NTU2IDcwLjYyMjNWNTcuODIyM0M1Mi45NTU2IDU2LjA1MTYgNTQuMzg1IDU0LjYyMjMgNTYuMTU1NiA1NC42MjIzSDgyLjgyMjNWNDguMjIyM0g0Ni41NTU2VjEyNC42N0gxMjAuNjg5WiIgZmlsbD0iIzE4QkNGMiIvPgo8L3N2Zz4K&logoColor=808080&labelColor=rgba(0,0,0,0)&color=rgba(33,33,33,0.1)&style=flat-square)](https://github.com/esphome/esphome) [![Home Assistant](https://img.shields.io/badge/Home%20Assistant-03A9F4?logo=HomeAssistant&logoColor=1abcf2&labelColor=rgba(0,0,0,0)&color=rgba(26,188,242,0.1)&style=flat-square)](https://my.home-assistant.io/redirect/config_flow_start/?domain=esphome)

![GitHub repo file or directory count](https://img.shields.io/github/directory-file-count/velijv/esphome-components?style=flat-square&color=rgba(24,188,242,0.1)&labelColor=rgba(24,188,242,0.2)&logo=Github&logoColor=18BCF2) ![GitHub repo size](https://img.shields.io/github/repo-size/velijv/esphome-components?style=flat-square&color=rgba(24,188,242,0.1)&labelColor=rgba(24,188,242,0.2)&logo=Git&logoColor=18BCF2) ![GitHub commit activity](https://img.shields.io/github/commit-activity/y/velijv/esphome-components?style=flat-square&color=rgba(24,188,242,0.1)&labelColor=rgba(24,188,242,0.2)&logo=GithubActions&logoColor=18BCF2) [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url] [![Github Sponsor](https://img.shields.io/github/sponsors/velijv?logo=githubsponsors&label=Sponsors&style=flat&labelColor=rgba(234,74,170,0.2)&logoColor=rgb(234,74,170)&color=rgba(234,74,170,0.1) "for jsut 1 doolar you can lead a por man to fish")](https://github.com/sponsors/velijv)

## serial_fake
> To make Arduino-only external components, like [SensorLib](https://github.com/lewisxhe/SensorLib) work in esp-idf without:

> [!WARNING]
> _Serial was not defined in this scope_


## nvs_nuke
> empty device nvs
