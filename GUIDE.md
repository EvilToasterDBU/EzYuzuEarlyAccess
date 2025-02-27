# EzYuzu Guide

## Requirements

- Latest version of [Microsoft .NET Framework](https://go.microsoft.com/fwlink/?linkid=2088631) installed.
- Administrator rights, to allow redistributables to install.

## Methodology

- Reads https://github.com/pineappleEA/pineapple-src/releases/latest
- Fetches the latest .zip URL
- Downloads & extracts it into your Yuzu root folder

## Usage

1. Browse and locate the your Yuzu Root Folder, this is the folder containing `yuzu.exe`
2. EzYuzu will automatically detect the version of yuzu.exe
3. Click on `New Install` or `Update Yuzu`

- Downloads the latest copy of yuzu-mainline & extracts it into your Yuzu Root Folder.
- Automatically checks if your standalone copy of Yuzu is up-to-date.
- `Dependencies` can be included within `Update Yuzu` by checking the option within `Options` > `General` > `Update Yuzu` > `Reinstall Visual C++`
- It shouldn't overwrite configs unless `New Install` is displayed. However, backup beforehand.
- Temp files are stored within `TempUpdate` and are deleted upon completion.

## Download Options

| Option         | Description                                                                                                                               |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| `New Install`  | Installs Yuzu & Redistributables. Resets configs & sets [optimised GPU defaults](https://github.com/amakvana/EzYuzu/tree/master/configs). |
| `Update Yuzu`  | Updates Yuzu to the latest version, excluding Redistributables but excluding configs.                                                     |
| `Dependencies` | Includes Redistributables when `Update Yuzu` is triggered.                                                                                |

## New Install

To install Yuzu Portable for the first time:

1. Create an empty folder on your device and give it a name.
2. Select your newly created empty folder.
3. The button should now change to `New Install`
4. Click on `New Install`
5. Done

## Update Yuzu

1. Select your Yuzu root folder (the folder containing `yuzu.exe`)
2. The button should now change to `Update Yuzu`
3. (Optional) Include `Visual C++ Redistributables` by checking the option within `Options` > `General` > `Update Yuzu` > `Reinstall Visual C++`
4. Click on `Update Yuzu`
5. Done

## Checking Yuzu is up-to-date

1. Select your Yuzu root folder (the folder containing `yuzu.exe`)
2. EzYuzu will automatically check if the current copy of Yuzu is up-to-date
3. If Yuzu is up-to-date, the Update button will be disabled and will state `Yuzu is Up-To-Date!`
4. Done
