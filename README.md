DADA COMPANY
============

## Install

Install Requirements:

````bash
winver
# SKIP IF WIN 11 24H2 IS INSTALLED

git --version
# SKIP IF GIT 2.54.0 IS INSTALLED
# https://github.com/git-for-windows/git/releases/download/v2.54.0.windows.1/Git-2.54.0-64-bit.exe
git --version

node --version
npm --version
# SKIP IF NODE OpenJS.NodeJS.24 LTS IS INSTALLED
# https://nodejs.org/dist/v24.16.0/node-v24.16.0-x64.msi
Set-ExecutionPolicy RemoteSigned
Get-ExecutionPolicy
npm --version
````

Install Project:

````bash
npm install -g pnpm
npm install -g opencode-ai

cd paperclip-demo
git clone https://github.com/paperclipai/paperclip.git

mkdir ouputs

cd paperclip
pnpm install

````

## Resources

- [Install Node.js on Windows](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows )
- [Paperclip + Qwen on Windows — Full Free Multi-Agent Setup! ](https://www.youtube.com/watch?v=dNnh0hjC4cA)
