# OS2025  Add dynamic theme color customization to xv6 via an interactive table menu.

## Overview
This project modifies the xv6 operating system to support dynamic theme changes, allowing users to customize the foreground and background colors of the entire screen via an interactive table menu.  
The new functionality is integrated carefully to ensure it does not interfere with normal system operations or performance.

## Features
- **Display/Hide Theme Table:** `ALT + T`  
- **Navigate Table:** 
  - `w` – move up  
  - `s` – move down  
- **Color Combinations:**  
  1. Light Gray + Black (`lgr blk`)  
  2. Magenta + White (`mgt WHT`)  
  3. Red + Bright Cyan (`red CYN`)  
  4. White + Yellow (`WHT YWL`)  
- **Highlighting:** Selected item shows black text on green background.  
- **Persistence:** Last selected theme is remembered and pre-selected on reopening.  
- **Dynamic Positioning:** Table appears near the cursor, adjusting left/right if needed.

## 🚀 How to Build & Run

```bash
# Clone your assigned repository
git clone https://github.com/TheVucko98/xv6-color-theme-change-with-menu.git

cd projectName
make qemu-nox
