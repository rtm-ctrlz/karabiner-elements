## First of all
Many thanks goes to [Takayama Fumihiko](https://github.com/tekezo) for Seil, Karabiner and [Karabiner-Elements](https://github.com/tekezo/Karabiner-Elements)

## Ruleset

- Language
  - CapsLock - toggle En<->Ru
  - Browsers force language to "En" for:
    - Command_L+T
    - Command_L+L
  - Spotlight (Command+Space) force language:
    - Command_L+Space - to "En" (for apps/files/etc)
    - Command_R+Space - to "Ru" (for contacts/mail/etc)
- Mouse control, based on [mouse.simple rev 1](https://github.com/pqrs-org/KE-complex_modifications/blob/master/docs/json/mouse_keys_simple.json)
  - added Shift_R+Alt_R+[WASD] with 30% speed
  - moved buttons:
    - q - button1 (left)
    - e - button2 (right)
- PC-like russian "ё" fix: grave_accent_and_tilde->backslash (ansi keyboard)
- Double Command_L+Q to quit browsers (Firefox/Chrome/Safari)

## Install

1. Karabiner-Elements - [from git](https://github.com/tekezo/Karabiner-Elements) or [from site](https://pqrs.org/osx/karabiner/)
1. Install rules
   - download to [ruleset.json](https://github.com/rtm-ctrlz/karabiner-elements/blob/master/ruleset.json) to `~/.config/karabiner/assets/complex_modifications`
   - OR
   - navigate your browser to `karabiner://karabiner/assets/complex_modifications/import?url=https%3A%2F%2Fraw.githubusercontent.com%2Frtm-ctrlz%2Fkarabiner-elements%2Fmaster%2Fruleset.json`, you have to Copy-Paste link, since Markdown doesn't support custom URI-schemes
1. Import rules: `Karabiner Elements Preferences -> Complex Modifications -> Rules -> Add rule`
1. Enable rules (one, all or none)
