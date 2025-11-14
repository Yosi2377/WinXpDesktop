# WinXpDesktop

This project simulates a comprehensive Windows XP desktop environment in the browser with multiple applications and features.

## Applications

### Productivity Apps
- **📝 Notepad** - Full-featured text editor with:
  - Save/load functionality using localStorage
  - Search and find text
  - Word count with character and line statistics
  - Real-time word/character counter
- **🔢 Calculator** - Complete calculator with:
  - All basic math operations (+, -, *, /)
  - Memory functions (M+, M-, MR, MC)
  - Backspace and clear functions
- **🎨 Paint** - Drawing application with:
  - Multiple tools: Brush, Rectangle, Circle, Eraser
  - Color picker and brush size control
  - Fill and clear canvas functions
  - Real-time drawing preview for shapes

### Games
- **💣 Minesweeper** - Classic minesweeper game with flag support and mine detection
- **🃏 Solitaire** - Full drag-and-drop Solitaire game with:
  - Complete card deck (52 cards in 4 suits)
  - Drag and drop functionality
  - Stock, waste, foundation, and tableau piles
  - Win detection and game reset
- **🐍 Snake** - Classic Snake game with:
  - Arrow key controls
  - Score tracking and high score
  - Collision detection
  - Increasing difficulty
- **⭕ Tic-Tac-Toe** - Two-player Tic-Tac-Toe with win detection

### Media & Internet
- **🎵 Windows Media Player** - Media player with YouTube embed support
- **🌐 Google Chrome** - Embedded browser window
- **🌐 Internet Explorer** - Fully functional browser with:
  - URL navigation bar
  - Back/forward navigation
  - Refresh and home buttons
  - Embedded iframe for web browsing
- **🎮 PSP Emulator** - PSP game emulator integration

### System Tools
- **My Computer** - Browse system drives
- **My Documents** - Access document folders
- **Recycle Bin** - Manage deleted files
- **Control Panel** - System settings with:
  - Appearance and themes configuration
  - Display settings (window size)
  - Sound settings
  - System information viewer
  - Storage management
  - Date and time (clock format toggle)
- **📧 Outlook Express** - Email client interface with:
  - Inbox, sent items, drafts, and trash folders
  - Compose new email functionality
  - Sample emails for demonstration
- **📋 Task Manager** - View and manage open windows with:
  - List of all running applications
  - Close individual or all windows
  - Refresh window list
- **📝 Sticky Notes** - Desktop sticky notes with:
  - Persistent storage using localStorage
  - Save, load, and clear functions
- **📅 Calendar** - Interactive calendar with:
  - Month navigation (previous/next)
  - Today highlighting
  - Jump to current date
  - Full date display
- **🖼️ Photo Viewer** - Image viewer with:
  - Load images from URL
  - Auto-fit to window size
  - Error handling for invalid URLs

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
- **Color Themes** - Choose from 6 different themes:
  - Classic Blue (default Windows XP)
  - Olive Green
  - Silver
  - Luna (deep blue)
  - Royale (medium blue)
  - Zune (orange)
- **Wallpaper** - Change desktop background via context menu
- **Window Sizes** - Set default window dimensions via Control Panel
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
