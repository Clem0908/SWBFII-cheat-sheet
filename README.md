# LAN gaming through VPN - tested on a Freebox server
- Set up the OpenVPN server (bridged mode) on the Freebox
- Download the .ovpn files corresponding to users created
- Edit and append to the file `ifconfig 192.168.0.A 255.255.255.0` with A being a valid local IP address
- Add `script-security 2`
- Add `up route.sh`: with route.sh a script setting a route for sending broadcast through the VPN tunnel
- `sudo openvpn [file].ovpn`

# Command line arguments
A list of command line arguments `BattlefrontII.exe` can take:
- /nointro - skips the intro
- /win - windowed
- /resolution 320 240 - max recommended: 1280 720
- /[no]framelock - disable V-Sync

Dedicated Server options & more right [here](https://pastebin.com/ZRtgg6Dd)

# Team-up with AI
- Modify controls: Squad commands
- Aim an ally and press the shortcut, the AI ally will follow you
