# Insert
PoC **Spyware** for silently enumerating, collecting and exfiltrating data from a Debian-flavored host.
<p align="center">
  <img src="https://www.clipartmax.com/png/small/470-4701465_clip-art-freeuse-stock-hat-spy-glasses-undercover-agentfreetoedit-spy-hat-png.png" alt="Clip Art Freeuse Stock Hat Spy Glasses Undercover">
</p>

---
## About
This project was founded while thinking of creative ways to silently exfiltrate data during an assessment i performed for a friend about a year ago. I recently stumbled upon some of my source code and realized that I had the basis for my greatest project yet: localized spyware with the ability to be controlled remotely while maintaining persistence and privilege.
## To-Do:
Short Term Goals:
  - Develop a basic stub capable of exfiltrating data normally using tcp.
  - Develop a silent way to maintain persistence.
  - Enumerate local file system for log files or configuration files with credentials or sensitive information.
  - Erase Insert's entire presence from the local file system by modifying logs and process files.
