**📸 QuickSnip - Screenshot Tool for Windows 10**  
[RU] Простая и быстрая утилита для создания скриншотов, которая имитирует поведение Windows 11 на старых версиях системы, добавляя автоматическое сохранение и удобное редактирование.  
**✨ Features**  
  Global Hotkey: Work by pressing Print Screen (or your custom key) even when minimized.  
  Auto-Save: Automatically saves images to Pictures/Screenshots folder.  
  Clipboard Support: Copies the screenshot to your clipboard instantly for quick sharing (Ctrl+V).  
  Auto-Edit: Automatically opens the screenshot in the Windows "Snip & Sketch" editor.  
  Settings Menu: Change the hotkey, save path, and toggle auto-start with Windows.  
  Tray Mode: Runs quietly in the background without cluttering your taskbar.   
**🛠 Tech Stack**  
  Language: C#  
  Framework: .NET Framework / WinFormsAPI: Win32   
  API (user32.dll) for global hotkeys.  
**⚙️ Configuration**  
  The app creates a config.txt file in its directory to store your custom hotkey code.  
  Default Key: Print Screen  
  Path: %USERPROFILE%\Pictures\Screenshots  
**📌 Note:** Если программа не реагирует на Print Screen, убедитесь, что в настройках Windows выключена опция "Использовать кнопку Print Screen для запуска фрагмента экрана".  
**🚀 How to Use / Как использовать**  
[RU] Инструкция:  
**Запуск:** Скачайте архив из раздела Releases и запустите файл Win11.exe(путь - ScreenShoots-main/screenshot improved(Извлечь всё)/Win11/Win11/bin/Release).  
**Фоновый режим:** После запуска программа автоматически свернется в трей. Окно настроек при этом не откроется — это нормально.  
**Снимок:** Нажмите кнопку Print Screen (или ту, которую вы настроили). Скриншот мгновенно сохранится в папку Изображения/Screenshots, скопируется в буфер обмена.  
**Настройки:** Чтобы изменить кнопку или папку, нажмите правой кнопкой мыши на иконку камеры в трее и выберите "Настройки".  
**Смена клавиши:** В меню настроек нажмите кнопку выбора клавиши, затем нажмите любую кнопку на клавиатуре. Программа автоматически обновит привязку.  
[EN] Instructions:  
**Launch:** Download the executable from the Releases section and run Win11.exe(path - ScreenShoots-main/screenshot improved(extract everything)/Win11/Win11/bin/Release).  
**Background Mode:** The app starts minimized in the system tray. No window will appear on startup — this is intended.  
**Take a Shot:** Press Print Screen (or your custom hotkey). The screenshot will be saved to Pictures/Screenshots, copied to the clipboard, and opened in the editor.  
**Settings:** Right-click the tray icon and select "Settings" to change the save path or hotkey.  
**Rebind Key:** Click the key selection button in the menu, then press any key on your keyboard to update the hotkey.
