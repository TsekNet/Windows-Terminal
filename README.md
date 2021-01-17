# TsekNet's Terminal

My personal, heavily customized [Windows Terminal profile](https://docs.microsoft.com/en-us/windows/terminal/customize-settings/global-settings).

![Terminal](terminal.png)

## Installation

1. Install the Cascadia Code PL font ([download Link](https://github.com/microsoft/cascadia-code/releases) / `choco install cascadiacodepl`)
2. Execute the following command in PowerShell:
    ```powershell
    iwr 'https://github.com/TsekNet/Windows-Terminal/raw/master/settings.json' -Out "$env:LOCALAPPDATA\Microsoft\Windows Terminal\settings.json"
    ```

## What's included

The following Windows Terminal profiles come pre-configured:

1. PowerShell 5
1. PowerShell Core or newer
1. CMD
1. WSL

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
