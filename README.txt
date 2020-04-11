# Multiplayer Setup Instructions

Unzip `PhotonServerV3.rar`. Folders `_xp` are for Windows XP.

For 64-bit Windows 10, use `bin_Win64`.

Run `PhotoControl.exe`. Max players is 20, or get a license from `dashboard.photonengine.com` for 100.

Port forwarding, same public and local ports:
1. 5055-5057 (UDP)
2. 4530-4532 (TCP)
3. 4520 (TCP)
4. 843 (TCP)

In the taskbar (bottom right, where WiFi is), open PhotonServer. Hit
"Game Server IP Config" and click "Set Public IP". Then go to "LoadBalancing"
and hit "Start as application".

For host, go to LAN and enter `127.0.0.1` (localhost) and enter port 5055.
For others, use the router public IP and port 5055.
