# Steam Plus session

This project is not affiliated with Valve (wide inspiration was taken from
their work on the SteamDeck). This configuration depends on [gamescope-session](https://raw.githubusercontent.com/ChimeraOS/gamescope-session)
from the ChimeraOS project.

## Basic manual setup

Copy this repository file structure into the appropriate places and you'll be
able to start the session on any Display Manager of your choice.

# Configuration

The session sources environment from `~/.config/environment.d/*.conf` and
`~/.config/gamescope-session-plus/sessions.d/steam-plus` files.
The easiest way to configure the session is to create
`~/.config/gamescope-session-plus/sessions.d/steam-plus` and set variables there:

```
# Override entire OpenGamepadUI command line
CLIENTCMD="opengamepadui --overlay-mode -- steam"
```

Refer to the [gamescope-session](https://github.com/ChimeraOS/gamescope-session)
README for more information about overriding configuration.

# License & Contributing

The project is licensed under GPL v3 license. If you want to contribute,
just do so and thank you.
