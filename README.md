# GShield

This script is written with idea that if your desktop pc serves multiple users, it is much slower, so the script aims to get everyone off your lawn.
Script will be mostly beneficial to gamers, it is not meant for bussines or corporate enviroments.
On the off chance you are a high profile target, this script is also recommended.

So what does the script do?

1. Applies multiple hardening tweaks. Policies, firewall rules, software execution restrictions (you need to run things as admin, otherwise they wont run at all)
2. It scans the filesystem for new files and files modifications and it does this to local drives, removable drives and network drives.
3. It removes unsigned library files (.dll) and also suspicious signed dll files (everyone will try to infect you with one to leech off of your gpu)
4. It sets performance tweaks for a very big number of video games, system perf tweaks, and network latency and perf tweaks.
5. It denies mounting of image files (iso for example) so that nobody can mess with the user from a mounted image. If the user insists, it can install 3rd party software such as wincdemu to mount isos, which should be safe if setup correctly.
6. It searches for any known webserver files and kills the webserver. Many spyware uses webservers to control their victim.
7. It tries to detect screen overlays and terminates them if found.
8. It tries to detect keyloggers and terminates them if found.
9. It sets telemetry to full, so msft can use diagnostic data to improve users device.
10. It reduces ram workingsets and standbylist every 10 secs so user has more ram if need be and to minimize chances of memory leaks.
11. It secures popular browsers from remote connecting to them.
12. It secures all known accounts from remote connecting to them
13. It prevents remote thread execution attempts.
14. It sets audio echo cancellation and noise suppression on all audio devices
15. It does minor cosmetic tweaks, such as setting seconds and date in tray.
16. It attempts to retaliate attacks by attempting to format intruders drive
17. It restricts access to sensitive system files
18. It detects and terminates rootkits

Pls make sure you are admin and only user on your home pc as this is who the script is meant for. 
Also, create a restore point prior to executing this script, as there is no uninstall.
You run this script at your own risk. I take no responsibility if any damage is caused.
