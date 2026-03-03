# ![PhantomX](https://github.com/user-attachments/assets/3faa74fd-e006-4455-8cf9-80848a830445) PhantomX

[![Release](https://img.shields.io/github/v/release/Agnivesh-Anil-Warrier/PhantomX?color=blue&style=for-the-badge)](https://github.com/YourUsername/PhantomX/releases)
[![License](https://img.shields.io/github/license/Agnivesh-Anil-Warrier/PhantomX?color=green&style=for-the-badge)](LICENSE)
[![Issues](https://img.shields.io/github/issues/Agnivesh-Anil-Warrier/PhantomX?color=yellow&style=for-the-badge)](https://github.com/YourUsername/PhantomX/issues)
[![Last Commit](https://img.shields.io/github/last-commit/Agnivesh-Anil-Warrier/PhantomX?color=red&style=for-the-badge)](https://github.com/YourUsername/PhantomX/commits/main)

---

**PhantomX** is a lightweight desktop utility that automatically converts `.pptx` and `.docx` files to `.pdf` and opens them in a preview viewer.

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
| Automatic Browser Preview | ✅ | ✅ |
| Offline Functionality | ✅ | ✅ |
| Easy Installation (Desktop Entry) | ✅ | ✅ |
| Minimal Setup | ✅ | ✅ |


---

## Installation

1. Download the desired file from the ***Releases*** section.


2.
   * Extract the downloaded folder.
   * Inside the folder, run the setup:

   ```bash
   chmod +x <setupname.sh>
   ./<setupname.sh>
   ```

   * The app will be installed to `~/.local/share` and a desktop entry will be created.

4. **PhantomX / Phantom-Lite** will be available from your applications menu.

---

## Usage of **PhantomX Version**


1. Launch from your applications menu.
2. Place `.pptx` or `.docx` files into the **Inbox** folder on your Desktop:

   ```
   ~/Desktop/PhantomX/Inbox
   ```
3. The app will automatically convert the files to PDF and open them in your default browser.
4. Use CTRL+C to quit.

**Phantom-Lite Version**

. Similar steps

---

## Uninstallation

Simply remove the app folder and desktop entry.

---

## Dependencies (Most likely your system satisfies these)

* Linux distribution with `LibreOffice` installed for document conversion.

---

## License

GPLv3 License
