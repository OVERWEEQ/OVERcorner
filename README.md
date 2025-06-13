# __OVERcorner__ - Windows Task View Enhancer

![logo](https://github.com/user-attachments/assets/6071a947-e1cc-4a4e-ac16-4902b7e6de3e)


A lightweight utility that improves Windows' Win+Tab and Win shortcuts, inspired by GNOME's workflow.

✨ Features
*Hot corner activation - Move your cursor to the top-left corner to open Task View (Win+Tab)

* Quick search - Start typing while in Task View to instantly open Windows Search with your text

* Right-click shortcut - Press RMB in the hot corner to open the Start Menu (Win)

* Pause/resume - Toggle the script with the Home key or via the system tray icon

* Multi-monitor support - Works correctly on all connected displays

* Tray icon control - Pause or exit the app via the system tray

* Customizable - Adjust the hot corner size and cooldown in the script

## 🛠 Installation
- Download the latest release from Releases

- Run OVERcorner.exe (no installation required)

OR

- Build from source
  Clone the repository:

  ```git clone https://github.com/yourusername/OVERcorner.git```
- Install dependencies:

  ```pip install pyautogui keyboard pystray Pillow pywin32```
- Build the executable:

  ```pyinstaller --onefile --noconsole --icon=icon.ico --name OVERcorner OVERcorner.py```
  
## 🔧 Usage
- Move cursor to top-left corner → Opens Task View (Win+Tab)

- Start typing → Activates Windows Search with your input

- Right-click in the corner → Opens Start Menu (Win)

- Press Home → Toggle pause/resume

- Right-click tray icon → Exit or pause the app

## 📝 Why I Made This

Windows' Win+Tab and Win shortcuts are useful, but not as fluid as GNOME's hot corner workflow. 
This script adds:

  ✔ Instant Task View (like GNOME Activities)

  ✔ Seamless search (start typing right away)

  ✔ Better multi-monitor handling

⚠️ Notes
  Works on Windows 10/11

  Runs in the background (minimal CPU usage)

  No admin rights required
