Use the below guide to install on Windows OS.

This has **ONLY** been tested on Windows 10.

This has been tested as a local user, and works as expected.

This **WILL** bypass group policy restrictions on code execution, and UAC installation limitations.

Neither of these are permanent, and both are actions you could carry out yourself if you know how.

See the below warning, and the [license](https://nyxtryx.github.io/Mouse-Mover/mit-license) for liability limitation.

-----

# WARNING

<strong>
It is YOUR responsibility to check your company's IT policy allows you to install programs.

Please read the license; contributors to this program are NOT liable in the event of any losses.
</strong>

-----

## Installation steps
1. Download [Download Windows folder][windows-cli-download-url] and save into your downloads folder
    1. You will need a GitHub account to use this
    2. Alternatively, you can download individual files [here](https://github.com/nyxtryx/Mouse-Mover/tree/main/windows) - you will need ALL of these files
2. Double click on install_mouse_mover.ps1
    1. If the installer fails to run:
    2. Press and hold the Windows key at the same time, press R
    3. Paste this, then press enter: PowerShell.exe -ExecutionPolicy Bypass -File %USERPROFILE%\Downloads\windows\install_mouse_mover.ps1
    4. This will bypass any group policy preventing code execution, **only** for this file (ie it is not permanent)
3. Follow the installer prompts, it will tell you what to do next

Once the program is installed and running, you can close it by closing the window that opens, or selecting the window and pressing Ctrl+C

## It didn't work!

See [here](https://nyxtryx.github.io/Mouse-Mover/guides/report-a-bug)

NB. Any issues created about this page which relate to the installer will be closed - please label such issues as "Windows>CLI-Installer"

[windows-cli-download-url]: https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2Fnyxtryx%2Fmouse-mover%2Ftree%2Fmain%2Fwindows "Download Windows CLI"
