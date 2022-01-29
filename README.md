# AutoHotkey Script to remap Tab key to 4 Spaces

1. Install [AutoHotkey](https://www.autohotkey.com/).

2. Create a new .ahk file (Right Click -> New -> AutoHotkey Script) and edit it (Right Click on the file -> Edit Script).

3. Here is the script:
    ```ahk
    +Tab::
    Send {space 4}
    return
    ```
    The first line contains the trigger/shortcut, I used `Tab`, you can use anything you like but make sure it doesn't block any other important functionality. Refer to AutoHotkey help to find what characters are used to reference different keys.

4. Save the script, close the editing window and run it.

AutoHotkey is much more powerful, so I'd highly recommend learning more about it.

### Update

Added shortcut to insert `______________________________` by pressing `Alt + |`.
