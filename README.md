# Scratch pad

# DevEnv

## Terminal

- iTerm2
- Install [ohmyzsh](https://github.com/romkatv/powerlevel10k#oh-my-zsh)
- Install [Powerlevel10k](https://github.com/romkatv/powerlevel10k#manual)
- Preferences
    - Appearance
        - Theme: **Minimal**
        - Status bar location: **Bottom**
    - Profiles
        - Text
            - Blinking cursor: **true**
            - Cursor: **Underline**
        - Session
            - Status bar enabled: **true**
    - ~ TopBar (left to right)
        - git state
        - CPU utilization
        - Memory utilization
        - Battery level
        - Auto-rainbow**: true**
    

## Dock + Desktop

- Dock on left size
- Auto-hide
- Run these command
    - defaults write com.apple.Dock autohide-delay -float 0.0001; killall Dock
    - defaults write com.apple.finder CreateDesktop false; killall Finder
