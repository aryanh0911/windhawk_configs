## Modified DockLike theme with the following features -
- Floating Dock ([github link](https://github.com/ramensoftware/windows-11-taskbar-styling-guide/blob/main/Themes/DockLike/README.md#make-the-taskbar-float-tweak:~:text=Make%20the%20taskbar%20float%20(tweak)))
- Translucent bg ([reddit thread](https://www.reddit.com/r/Windhawk/comments/1j97c8h/comment/mu4i51w/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button))
  1. Target: Grid#RootGrid
      - Styles: Background:= `<WindhawkBlur BlurAmount="30" TintColor="#4D000000" />`
  2. Target: Grid#SystemTrayFrameGrid
      - Styles: Background:= `<WindhawkBlur BlurAmount="30" TintColor="#4D000000" />`


## Bugs:
- Show-desktop button on the right side of the system tray got cut off visually although it is present and functions properly.
