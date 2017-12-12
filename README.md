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
1. Import json - link to master and enable rules
