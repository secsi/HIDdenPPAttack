# HIDdenPPAttack
Attack walkthrough located here https://simpleinfosec.com/2018/01/09/the-hidden-pp-attack-a-non-administrative-remote-shell-for-data-exfiltration/

The idea is to create a Powershell loop which constantly checks for updates to a PS1 file in a mutually shared location. It then collects and executes. Administrative privellages are NOT required for this to function as a remote shell!!!!

This was initially designed as a PoC that breaching domain admin accounts is not the only way to access and exfil sensitive data. 

[+] 9th January
- Added Example powershell payloads file
- Added initial Teensy one liner payload script

[+] 8th January 2018

- Added "Teensy_Exfil_Cached_Creds_Through_Outlook_As_Attachement" - Script to exfil data through Outlook as an attachment

- Added "Teensy_Lock_Your_Screen" - Script to display cached creds on screen as a shock treatment to end users to lock their machines
