# OpenCode Remote

[العربية](README-ar.md) | English

OpenCode Remote is a dedicated desktop application designed to provide secure, remote control over the OpenCode Agent via a Telegram Bot integration. It acts as a bridge between your local development environment and your mobile device, allowing you to monitor and interact with your agent seamlessly.

> **Disclaimer:** OpenCode Remote is an independent project created by CodeMZ and is not officially affiliated with, endorsed by, or associated with the OpenCode core team.

## Download

| Platform | Architecture | Installer / File |
| :--- | :--- | :--- |
| <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_logo_black.svg" width="16" height="16"> **macOS** | Apple Silicon (ARM64) | [Download .dmg](https://github.com/MOHAMEDHAMED1S/OpenCode_remote_/releases/download/v1.0/OpenCode_Remote-1.0.0-arm64.dmg) |
| <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Windows_logo_-_2021.svg" width="16" height="16"> **Windows** | 64-bit (x64) | [Download .exe](https://github.com/MOHAMEDHAMED1S/OpenCode_remote_/releases/download/v1.0/OpenCode.Remote.1.0.0.portable.exe) |


## Key Features

* **Remote Agent Management:** Control and monitor your OpenCode Agent remotely through a secure Telegram Bot integration.
* **Professional Dashboard:** A sleek, high-density control panel designed for productivity, allowing you to manage connections, view status, and configure settings with ease.
* **Background Operation:** Runs silently in the system tray (macOS & Windows), ensuring your remote connection remains active without cluttering your workspace or taskbar.
* **Storage Management:** Includes built-in database and log management utilities. The "Safe Clean" feature allows you to securely free up storage space without losing critical connection data or settings.
* **Native Desktop Experience:** Built with Electron, ensuring native notifications, auto-start capabilities, and optimized performance.
* **Secure Architecture:** Built with privacy and security in mind, maintaining secure communication channels between the agent and the Telegram interface.

## How to Use (Step-by-Step Guide)

### 1. Installation
* **macOS:** Download the `.dmg` file, open it, and drag **OpenCode Remote** to your Applications folder.
* **Windows:** Download the `.exe` file and run it directly. It is a portable application and requires no installation.

### 2. Initial Setup (Telegram Bot)
1. Open the application. You will be greeted by the initial setup screen.
2. Open Telegram and search for **BotFather** (`@BotFather`).
3. Send `/newbot`, choose a name and username, and copy the **HTTP API Token**.
4. Paste the Token into the OpenCode Remote app and click **Connect**.
5. Once connected, the app will open the main Dashboard and minimize to your system tray.

### 3. Injecting the Agent
To allow the Telegram bot to control your local OpenCode instance, you need to inject a script into the OpenCode application:
1. Open the **OpenCode Remote Dashboard** from your system tray.
2. In the sidebar, click on **"Inject Guide"** to view your Server URL and WS Token.
3. Copy the provided injection script code.
4. Open the **OpenCode** application on your computer.
5. Open DevTools by pressing `Cmd+Option+I` (Mac) or `Ctrl+Shift+I` (Windows/Linux) and go to the **Console** tab.
6. If prompted by a security warning, type `allow pasting` and press Enter.
7. Paste the script into the console and press Enter. When prompted, enter your Server URL and WS Token.

### 4. Remote Control via Telegram
1. Go to your newly created Bot in Telegram.
2. Send the `/start` command. 
3. Go to the OpenCode Remote Dashboard > **Users Tab** and approve your Telegram account.
4. You can now chat with your agent, send commands, and monitor its status directly from Telegram!

## System Requirements

* **macOS:** macOS 10.15 (Catalina) or higher. Apple Silicon (ARM64) or Intel processor.
* **Windows:** Windows 10 or Windows 11 (64-bit).

---
*OpenCode Remote - Engineered for professional developers by CodeMZ.*
