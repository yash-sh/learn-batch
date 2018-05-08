# learn-batch

## Batch file
- A batch file is a kind of script file in DOS, OS/2 and Microsoft Windows. It consists of a series of commands to be executed by the command-line interpreter, stored in a plain text file.
- Open any text editor, create a new file and save it with **.bat extension** (for e.g. fileName.bat).
- You can open .bat files by double clicking the left mouse key.
- .bat files by default open in Command Prompt (Command-line interpreter on Windows NT, Windows CE, OS/2 and eComStation operating systems).
  - Press **`WindowsKey+R`** to open **RUN** box.
  - Type **`cmd`** and hit **`Enter`**.
  - Command Prompt will open with cursor blinking after the path **`C:\Users\profileName>`** where `C` is the drive where Windows is installed, `Users` is the directory where data of all users are saved and `profileName` is the directory of the logged in User.
  - We will learn command to change directory (change root directory) but till now there is an another shortcut to open CMD with path to specific directory by **holding `Shift`+ {clicking `Right mouse key` or `F10`} then {clicking `Open command window here` or press `W` and hit `Enter`}**.
- We can input commands in CMD or can run a batch file containing set of commands.

## Commands
- **`md or mkdir`**
  - Task - make directory
  - Syntax
    - **`md newDirecory`**  :  Creates a directory with name `newDirectory`.
    - **`md path\to\newDirecory`**  :  Creates a directory with name `newDirectory` in `path\to\` if `path` and `to` already exist or create the tree `path\to\newDirectory` if `path` and `to` does not exist.
- **`cd`**
  - Task - change directory
  - Syntax
    - **`cd newDirecory`**  :  Change directory to `newDirectory` if it exists there.
    - **`cd path\to\newDirecory`**  :  Change directory to `newDirectory` in `path\to\` if `path` and `to` exist.
