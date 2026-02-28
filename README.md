# PhantomX

**PhantomX** is a lightweight desktop utility that automatically converts `.pptx` and `.docx` files to `.pdf` and opens them in a preview viewer. No terminal commands are required — a system tray icon provides easy access.

---

## Features

* Converts **PowerPoint (.pptx)** and **Word (.docx)** files to PDF.
* Automatically previews PDFs in your browser.
* System tray icon for easy access and control.
* Works entirely offline.
* Minimal setup  just download, make executable, and install.

---

## Installation

1. Download the latest `PhantomX.AppImage` and `PhantomX_512x512.png`.
2. Place them in the same folder as the `install.sh` script.
3. Run the installer:

```bash
chmod +x install.sh
./install.sh
```

4. The app will be installed to `~/.local/share/PhantomX` and a desktop entry will be created.
5. Search for **PhantomX** in your applications menu to launch.

---

## Usage

* Launch PhantomX from the applications menu.
* Place `.pptx` or `.docx` files in the **Inbox** folder on your Desktop:

  ```
  ~/Desktop/PhantomX/Inbox
  ```
* The app will automatically convert and open the PDF in your default browser.
* Use the system tray icon to quit the app.

---

## Uninstallation

Simply remove the app folder and desktop entry:

```bash
rm -rf ~/.local/share/PhantomX
rm ~/.local/share/applications/PhantomX.desktop
```

---

## Dependencies

* Linux desktop environment with system tray support.
* `LibreOffice` installed for document conversion.
* Python 3 (for AppImage, if using development version).

---

## License

MIT License — free to use, modify, and distribute.

---

If you want, I can also **write a version optimized for GitHub**, with **screenshots, badges, and usage GIFs** — it would make your repository look much more professional.

Do you want me to do that next?
