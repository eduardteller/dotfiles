# 🐧 Arch Linux Dotfiles

A minimal and elegant Arch Linux desktop configuration focused on productivity and aesthetics. This setup uses Sway as the window manager with a dark theme aesthetic.

## 🖥️ Desktop Environment

### Core Components

- **OS**: Arch Linux
- **Window Manager**: [Sway](https://swaywm.org/) (Wayland compositor)
- **Status Bar**: [Waybar](https://github.com/Alexays/Waybar)
- **Application Launcher**: [Rofi](https://github.com/davatorium/rofi)
- **Terminal**: [Kitty](https://sw.kovidgoyal.net/kitty/)
- **Notification Daemon**: [Dunst](https://dunst-project.org/)
- **System Monitor**: [btop](https://github.com/aristocratos/btop)

### Theme & Appearance

- **GTK Theme**: Orchis-Dark
- **Icon Theme**: Tela-dark  
- **Cursor Theme**: Bibata-Modern-Classic
- **Font**: JetBrainsMono Nerd Font Mono
- **Color Scheme**: Dark theme with blue accent colors (#3281EA)

## 🎨 Visual Features

### Sway Configuration
- **Border Style**: 1px pixel borders
- **Gaps**: Smart gaps and borders
- **Font**: JetBrainsMono Nerd Font Mono Bold 10pt
- **Color Scheme**: Custom dark theme with blue accents
- **Wallpaper**: Custom wallpaper from wallhaven

### Waybar Setup
- **Position**: Top bar
- **Height**: 30px
- **Modules Left**: Workspaces, Sway mode
- **Modules Center**: Window title
- **Modules Right**: Network, Memory, CPU, Audio, Battery, System tray, Clock

### Kitty Terminal
- **Font**: JetBrainsMono Nerd Font Mono (12pt)
- **Theme**: Custom dark theme with extensive color collection
- **Padding**: 20px horizontal, 10px vertical
- **Features**: Bell notifications enabled

## 🔧 Key Applications & Tools

### Productivity
- **File Manager**: Nautilus (GNOME Files)
- **Text Editor**: Neovim
- **Password Manager**: 1Password
- **VPN**: Mullvad VPN

### Development
- **Editor**: VS Code
- **Terminal**: Kitty with Zsh shell
- **Font**: JetBrainsMono Nerd Font for coding

### Media & Internet
- **Browsers**: Brave, Chromium, Google Chrome variants
- **Music**: Spotify
- **Video**: VLC

### System Utilities
- **Audio Control**: PulseAudio with pavucontrol
- **Bluetooth**: Blueman
- **Network**: NetworkManager with nm-applet
- **Package Manager**: yay (AUR helper)
- **System Info**: htop, btop

## 🎯 Special Features

### Automation
- **Autotiling**: Automatic window tiling for specific workspaces
- **Polkit Agent**: GNOME authentication agent for privilege escalation
- **System Tray**: Bluetooth and network management applets

### Theme Integration
- **GTK Applications**: Consistent dark theme across all GTK apps
- **Color Scheme**: System-wide dark theme preference
- **Icons**: Cohesive icon theme throughout the desktop

### Visual Feedback
- **WOB**: On-screen display for volume and brightness changes
- **Dunst**: Elegant notification system
- **Smart Borders**: Borders only shown when necessary