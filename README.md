# AutoHotkey Script to insert 4 spaces in textfields

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

### Story Time XD

My Logic in Computer Science tuts require me to use https://math.typeit.org/ to type symbols for propositional logic proofs but it does not allow me to use `Tab` to indent as using `Tab` takes me out of the textfiled. Copying and pasting spaces was annoying because I also had to copy my proofs to a gform for submission. I looked for alternatives, found something called Tabinta but it didn't support my version of Firefox. So I went with the next best option, AHK.
