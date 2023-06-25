# Karabiner Elements Configuration
Configuration files for my Karabiner Elements at `~/.config/karabiner`.

### Installation
1. `cd ~/.config && git clone git@github.com:adjmunro/config-karabiner.git karabiner`
2. Homebrew: `brew install --cask karabiner-elements` ([Repo](https://github.com/pqrs-org/Karabiner-Elements))

### Current Configs
Profiles: Qwerty, Engram (Affects all keyboards)
- **Karabiner Elements - Profile Switching**
  - `[Command + Shift + Hyphen]` Switch to Qwerty Profile
  - `[Command + Shift + Equals]` Switch to Engram Profile
- **Keychron K6 Fixes**
  - `[Shift + Esc]` Type Grave Symbol (`)
  - `[Control + Esc]` Type Tilde Symbol (~)
  - `[Command + Esc]` Cycle to Next Window (Fixes `[Command + ~]`)
  - `[Command + Shift + Esc]` Cycle to Previous Window (Fixes `[Command + Shift + ~]`)
- **Keychron K6 Shortcuts**
  - `[Home]` Show Desktop.
  - `[Page Up]` Use Mission Control.
  - `[Page Down]` Use Spotlight.
- **Instant Terminal (iTerm2)**
  - `[Control + Home]` Launch/Show/Minimise iTerm2.

> Note, you cannot overwrite fn1 or lighting keys on the Keychron K6, as these are exclusive to the keyboard firmware. As such, after rearranging your keys to Engram layout, the Bluetooth buttons will remain on (qwerty -> engram): `Q -> B`, `W -> Y`, `E -> O` and the `insert`, `del`, and `end` keys remain on `P -> V`, `[ -> Z`, and `] -> /` respectively.

[Official Docs](https://karabiner-elements.pqrs.org/docs/) | [Complex Modifications](https://ke-complex-modifications.pqrs.org/)

### Engram Profile
[Engram](https://github.com/binarybottle/engram) layout is provided by simple modifications to the `Engram` profile. The purpose is to decrease typing fatigue / increase efficiency. A `Qwerty` profile is also available.
![Engram Keymap](https://github.com/binarybottle/engram/raw/master/assets/engram-800px.png?raw=true)
> Note: The simple keymappings that I have implemented are for my physically rearranged keys on the Keychron K6. This means that the punctuation does not match, nor have i moved the number row. You can still use Engram on all keyboards via touch-typing.
<img width="1046" alt="image" src="https://github.com/adjmunro/config-karabiner/assets/75865923/01042163-0bd0-48ea-8a7c-ee86149b9c7d">
