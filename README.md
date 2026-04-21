# PhantomShell
Hyprland dotfiles optimized for 2in1 laptops and phones

# Features
- Virtual keyboard with hyprkbd
- Touch-screen gestures with hyprgrass
- Practical keybinds (_Big thanks to the team behind Caelestia Shell_)
- Designed with ARM64 and low-power devices in mind (~1.5GB ram usage at idle)

# Requirements and dependencies
## Requirements
*Note : requirements can change at any moment*

**CPU** : At least 2 cores, AMD64 or ARM64

**GPU** : Yes

**RAM** : At least 2Gb, 4Gb is the minimum reccomended to be usable

## Dependencies
*Note : this might not include all recursive dependencies*
```
hyprland
hyprlock
hyprkbd
kitty
mpris-proxy
hyprlight
playerctl
fsel
hyprshot
app2unit
hyprgrass
glm
iio-hyprland

# Build dependencies for hyprgrass
meson
ninja
```

## Recommended apps
```
# Wallpaper selection
waypaper
```


# Roadmap
- [x] Working hyprland setup
- [x] Working touchscreen gestures
- [x] Working waybar _(using ashell)_
- [x] Working app menu _(using fsel on kitty)_
- [ ] Common Hyprland fixes
    - [x] Fix QT theme _(edits need to be made through qt6ct)_
    - [ ] Fix mouse cursor theme
    - [ ] Fix dolphin file associations
- [ ] Installation script
- [ ] Make things look better (like notifications)
- [ ] Fully automated setup