# Wavecast

Your Android phone on your Mac or PC. This repository only hosts the installers — website: https://getwavecast.com

## Download

Grab the latest build from [Releases](https://github.com/ValonHajredini/wavecast-releases/releases/latest).

| Platform | File |
| --- | --- |
| macOS 13+ (Apple Silicon) | `Wavecast_<version>_aarch64.dmg` |
| Windows 10/11 (x64) | `Wavecast_<version>_x64-setup.exe` |

## Installing on macOS

The app is not notarized yet, so the first launch needs one extra step:

1. Open the `.dmg` and drag **Wavecast** into **Applications**.
2. In Applications, **right-click Wavecast → Open**, then confirm **Open**.
   (On macOS 15+: try to open it once, then go to System Settings → Privacy & Security and click **Open Anyway**.)

After that it opens normally.

## Installing on Windows

The installer is not code-signed yet, so SmartScreen may show "Windows protected your PC".
Click **More info → Run anyway**. The installer puts Wavecast in your user folder (no admin rights needed).
