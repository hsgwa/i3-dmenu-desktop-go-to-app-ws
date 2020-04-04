# i3-dmenu-desktop-go-to-app-ws

## Overview
The i3-dmenu-desktop wrapper script that adds a jump alias to the specific running application workspaces.

## Requrements
- i3
- i3-dmenu-desktop
- jq

## Installation
1. git clone `https://github.com/hsgwa/i3-dmenu-desktop-go-to-app-ws.git` 
2. edit ./i3/config.
```
# launch dmenu-dekstop-go-to-app-ws
bindsym $mod+space exec --no-startup-id [path-to-i3-dmenu-desktop-go-to-app-ws]

# rotate last selected application workspaces.
bindsym $mod+n exec --no-startup-id /tmp/i3-last-go-to-app
```

## Usage
1. press `$mod+space` .
2. select `Go to ****`.
2. press `$mod+n` to rotate application workspaces.

