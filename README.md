# 自動化 Windows 安裝

## Warning

防火牆已禁用，僅適用於開發測試，請勿將系統用於正式場合

## Usage

Copy `autounattend.xml` to the same directory as `setup.exe` in `windows_install.iso`

## Features

* x64
* Win11 requirements check bypass
* Allow install Win11 without internet
* Offline accounts: `Admin`, `YIJIA`, no password!
* Disable Windows Defender
* Disable UAC
* Disable Smart App Control
* Allow Powershell Script Execution
* No BitLocker
* No Copilot, Bing Search, Skype

## Source

You can generate your `autounattend.xml` on [Generate autounattend.xml files for Windows 10/11](https://schneegans.de/windows/unattend-generator/)
