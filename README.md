# ![PhantomX](https://github.com/user-attachments/assets/3faa74fd-e006-4455-8cf9-80848a830445) PhantomX

[![Release](https://img.shields.io/github/v/release/Agnivesh-Anil-Warrier/PhantomX?color=blue&style=for-the-badge)](https://github.com/YourUsername/PhantomX/releases)
[![License](https://img.shields.io/github/license/Agnivesh-Anil-Warrier/PhantomX?color=green&style=for-the-badge)](LICENSE)
[![Issues](https://img.shields.io/github/issues/Agnivesh-Anil-Warrier/PhantomX?color=yellow&style=for-the-badge)](https://github.com/YourUsername/PhantomX/issues)
[![Last Commit](https://img.shields.io/github/last-commit/Agnivesh-Anil-Warrier/PhantomX?color=red&style=for-the-badge)](https://github.com/YourUsername/PhantomX/commits/main)

---

**PhantomX** is a lightweight desktop utility that automatically converts `.pptx` and `.docx` files to `.pdf` and opens them in a preview viewer. No terminal commands are required as a system tray icon provides easy access.

---

## Features

* Automatically previews PDFs in your browser.
* Works entirely offline.
* Minimal setup  just download, make executable, and set up.

  ##  Lite vs Full Version

| Feature | Lite Version | Full Version (PhantomX) |
|---------|:-----------:|:----------------------:|
| `.pptx` → PDF Conversion | ✅ | ✅ |
| `.docx` → PDF Conversion | ❌ | ✅ |
| Handling of PDFs if they are placed in inbox | ❌ | ✅ |
| System Tray Icon | ❌ | ✅ |
| Automatic Browser Preview | ✅ | ✅ |
| Offline Functionality | ✅ | ✅ |
| Easy Installation (Desktop Entry) | Optional | ✅ |
| Minimal Setup | ✅ | ✅ |


---

## Installation

1. Download the desired file from the ***Releases*** section.

2. **Lite Version:** ![Lite](https://img.shields.io/badge/Lite-Yes-blue)  

   * Make the AppImage executable and run it:

   ```bash
   chmod +x Phantom-Lite.AppImage
   ./Phantom-Lite.AppImage
   ```

   * Setup is complete. You can either run the command everytime to open the app or create a desktop entry (with terminal=True) in your desired location.

3. **X Version Full Version:** ![Full](https://img.shields.io/badge/Full-Yes-red)

   * Extract the downloaded folder.
   * Inside the folder, run the installer:

   ```bash
   chmod +x install.sh
   ./install.sh
   ```

   * The app will be installed to `~/.local/share/PhantomX` and a desktop entry will be created.

4. **PhantomX** will be available from your applications menu.

---

## Usage

**PhantomX (Full Version)**

1. Launch **PhantomX** from your applications menu.
2. Place `.pptx` or `.docx` files into the **Inbox** folder on your Desktop:

   ```
   ~/Desktop/PhantomX/Inbox
   ```
3. The app will automatically convert the files to PDF and open them in your default browser.
4. Use the system tray icon to quit the application when done.

**Phantom-Lite Version**

1. Run **Phantom-Lite** once.
2. A folder named `ppt-auto-preview` will be created on your Desktop.
3. Place `.pptx` files into the `Inbox` folder inside this directory.
4. The app will automatically convert and open the PDFs in your default browser.
5. Close the app using `Ctrl+C` in the terminal when finished.

---

## Uninstallation

Simply remove the app folder and desktop entry:

```bash
rm -rf ~/.local/share/PhantomX
rm ~/.local/share/applications/PhantomX.desktop
```

---

## Dependencies (Most likely your system satisfies these)

* Linux desktop environment with system tray support.
* `LibreOffice` installed for document conversion.

---

## License

GPLv3 License
