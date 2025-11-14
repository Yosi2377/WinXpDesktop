# WinXpDesktop

This project simulates a comprehensive Windows XP desktop environment in the browser with multiple applications and features.

## Applications

### Productivity Apps
- **📝 Notepad** - Full-featured text editor with save/load functionality using localStorage
- **🔢 Calculator** - Complete calculator with all basic math operations
- **🎨 Paint** - Drawing application with color picker, brush size control, and canvas tools

### Games
- **💣 Minesweeper** - Classic minesweeper game with flag support and mine detection
- **🃏 Solitaire** - Traditional Windows Solitaire card game

### Media & Internet
- **🎵 Windows Media Player** - Media player with YouTube embed support
- **🌐 Google Chrome** - Embedded browser window
- **🎮 PSP Emulator** - PSP game emulator integration

### System Tools
- **My Computer** - Browse system drives
- **My Documents** - Access document folders
- **Recycle Bin** - Manage deleted files
- **Control Panel** - System settings
- **Internet Explorer** - Classic IE browser

## Features

### Window Management
- Multiple draggable windows with smooth animations
- Minimize, maximize, and close controls
- Double-click window header to maximize/restore
- Resize windows with drag handles
- Window animations (fade-in, minimize effects)
- Active window highlighting

### Desktop Features
- Start menu with organized application list
- Taskbar with running application indicators
- Desktop icons with hover effects and tooltips
- Ability to add custom applications
- Draggable desktop icons

### Customization
- **Color Themes** - Choose between Classic Blue, Olive Green, or Silver themes
- **Wallpaper** - Change desktop background via context menu
- **Window Sizes** - Set default window dimensions
- **Clock Format** - Toggle between 12/24 hour display with full date tooltip
- **Menu Button** - Movable menu button with position reset

### Advanced Features
- **localStorage Persistence** - Saves preferences, notepad content, and theme settings
- **Screensaver** - Animated screensaver activates after 5 minutes of inactivity
- **Sound Effects** - Windows XP-style sounds for opening/closing windows
- **Context Menu** - Right-click anywhere or use Menu button for quick access
- **Smooth Animations** - CSS transitions for professional window effects
- **Responsive Design** - Adapts to different screen sizes

### Context Menu Options
- Refresh page
- Toggle menu on top
- Set window size
- Change theme
- Move menu button
- Change wallpaper
- About information
- Minimize/Close active window
- Reset menu position
- Toggle clock format

## Technical Details

- Built with pure HTML, CSS, and JavaScript (no external dependencies)
- Single-file application for easy deployment on GitHub Pages
- Uses Web Audio API for sound effects
- Canvas API for Paint application
- localStorage for data persistence
- Smooth CSS animations and transitions
- Israel timezone for clock display
