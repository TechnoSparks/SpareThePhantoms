# Spare the Phantoms
This module enforces the sparing of phantom processes from being killed.

## About
Since Android 12, there is a hard limit on the number of processes a program can have and also a heuristic-based CPU usage limit. When exceeded, the system will terminate the processes whole.

For normal Android users this can cause no problems. However, if you use Linux on Termux like Andronix for example, you will quickly reach the max number of processes and Android would terminate the Termux processes.

On Android 12L and above, a feature flag has been added to disable this process termination.

Comprehensive documentation about this phenomenon [here](https://github.com/agnostic-apollo/Android-Docs/blob/master/en/docs/apps/processes/phantom-cached-and-empty-processes.md).


## Usage
- Flash and forget

### Requirements
- Magisk version 23 or newer
- Android 12L and newer

### Installing
Flash the zip (Releases section) in Magisk Manager or in recovery.

## Building
- Requires `7z` (7zip) in PATH
- Run `build.cmd` on Windows.

## Disclaimer
- Module is provided as is. No support is provided