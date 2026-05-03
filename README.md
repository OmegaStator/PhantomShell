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

|Requirement        |Required    |Reccomended                                      |
|-------------------|------------|-------------------------------------------------|
|System Architecture|AMD64, ARM64|                                                 |
|CPU                |2 Cores     |4 Cores                                          |
|GPU                |Yes         |GPU with proper drivers (AMD, Intel, Qualcomm...)|
|RAM                |2Gb         |4Gb                                              |

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
dunst

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
- [x] Working notifications
- [ ] Common Hyprland fixes
    - [x] Fix QT theme _(edits need to be made through qt6ct)_
    - [ ] Fix mouse cursor theme
    - [ ] Fix dolphin file associations
- [ ] Installation script
- [ ] Make things look better (like notifications)
- [ ] Fully automated setup