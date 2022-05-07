# MacOS Useful Commands
A collection of some neat tricks to improve MacOS usability that I've come across on interwebz.

## 1. Moving a macOS window by clicking anywhere on it (like on Linux)

Enable (log off required): 
```bash
defaults write -g NSWindowShouldDragOnGesture -bool true   
```

Disable
```bash
defaults delete -g NSWindowShouldDragOnGesture  
```

Usage: <kbd>cmd</kbd>+<kbd>ctrl</kbd>+ click

Source: https://mmazzarolo.com/blog/2022-04-16-drag-window-by-clicking-anywhere-on-macos/
