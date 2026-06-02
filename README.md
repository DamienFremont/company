DADA COMPANY
============

WIP

## Install

Install Requirements:

````bash
winver
# SKIP IF win 11 24H2 IS INSTALLED

git --version
# SKIP IF git 2.54.0 IS INSTALLED
# https://github.com/git-for-windows/git/releases/download/v2.54.0.windows.1/Git-2.54.0-64-bit.exe
git --version

node --version
npm --version
# SKIP IF node OpenJS.NodeJS.24 LTS IS INSTALLED
# https://nodejs.org/dist/v24.16.0/node-v24.16.0-x64.msi
Set-ExecutionPolicy RemoteSigned
Get-ExecutionPolicy
npm --version
````

## Installation

### 1. Install pnpm
````powershell
pnpm --version
# SKIP IF pnpm 11.5.0 IS INSTALLED
npm install -g pnpm
````

### 2. Install OpenCode
````powershell
npm install -g opencode-ai
````

### 3. Enable Developer Mode (Windows symlink fix)
````powershell
# Run as Administrator
reg add "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\AppModelUnlock" /t REG_DWORD /d 1 /v AllowDevelopmentWithoutDevLicense /f
````

### 4. Clone and set up Paperclip
````powershell
git clone https://github.com/paperclipai/paperclip.git
cd paperclip
git checkout v2026.529.0
mkdir ouputs
pnpm install
````

### 6. Run Paperclip
```powershell
pnpm dev
```
Open browser → http://127.0.0.1:3100

---

## Resources

- [Install Node.js on Windows](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows )
- NetworkCoder
    - [Paperclip + Qwen on Windows — Full Free Multi-Agent Setup! ](https://www.youtube.com/watch?v=dNnh0hjC4cA)
    - [PaperClip-Run-Your-Own-AI-Company](https://github.com/network-tocoder/PaperClip-Run-Your-Own-AI-Company)
