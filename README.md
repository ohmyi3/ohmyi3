# Ohmyi3


Ohmyi3 provides a dynamic template engine for your i3 configs providing variable
and conditional driven i3 settings.

Ideal for those that use i3 on many of their systems and want to maintain a single
global repository that morphs to each computers environment based on hostname, user
and any other dynamic variable.


## Features
- Single `~/.config/ohmyi3/config.py` to dynamic variables to i3 configs
- One set of configs morphs based on your hostname, desktop environment or any variable you care to define.
- Uses python jinja2 templates to add variables and conditions to your i3 [or any] configs
- Plugins and hooks allow you to control all aspects of your system from a single config
    - Not only can you template dynamic i3 configs, but you can also:
    - Template alacritty, polybar, nitrogen, feh and anything else...its all python and jinja2, limitless


## Installation

1. Install from Pypi https://pypi.org/project/ohmyi3/ with `pip`
```
pip install ohmyi3
```

2. Initialize a fresh ohmyi3 config.  This creates a `~/.config/ohmyi3` and
populates it with a good set of default you can work with.
```
i3ctl init
```

3. Modify the stock `~/.config/ohmyi3/config.d/*` i3 configs to suit your needs.
Add any `*.conf` file you want.  They are all picked up in alphabetical order.

4. The `theme` variable picks the theme from `~/.config/ohmyi3/themes` folder.
Bring your own themes.

4. **NOTICE:** Review and modify stock `~/.config/ohmyi3/config.py` configuration.  This is
just a stock example.  **DO NOT run it as is.**  You need to tune this to fit your
system.  All of the variables defined in that file will be available as jinja2
variables when templating i3 and the rest of your system.

    Pay special attention to the `after_generate` hooks.  You will want to comment
    those out and use them as needed.  To review the plugin code see the
    `~/.config/ohmyi3/plugins` directory.  Plugins are very simple system
    modification scripts.  Please review and write your own to suit your needs.

5. Once you have tuned your variables, you can see the resulting dictionary
```
i3ctl info
```

6. If you like all the variables, and have **used the plugins with caution**
you can now run the generator to template `~/.config/ohmyi3/config.d/*` i3 configs
which will output a new i3 file to `~/.config/i3/config` (it WILL save a backup
to that same folder before it overrides a new file)

7. Reload i3
