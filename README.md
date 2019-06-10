# template_configuration_files
Contains examples of useful configuration files



# Useful Bash Shortcuts

Reference: [https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)
  
### Working with Process

```
# Interrupt (kill) the current foreground process running in in the terminal.
# This sends the SIGINT signal to the process, which is technically just a
# request—most processes will honor it, but some may ignore it.
Ctrl+C

# Suspend the current foreground process running in bash.
# This sends the SIGTSTP signal to the process. To return the process to the
# foreground later, use the fg process_name command.
Ctrl+Z

# Close the bash shell. This sends an EOF (End-of-file) marker to bash, and
# bash exits when it receives this marker. This is similar to running the exit command.
Ctrl+D
```

### Controlling the Screen

The following shortcuts allow you to control what appears on the screen

```
# Clear the screen. This is similar to running the “clear” command.
Ctrl+L

# Stop all output to the screen. This is particularly useful when running
# commands with a lot of long, verbose output, but you don’t want to stop
# the command itself with Ctrl+C.
Ctrl+S

# Resume output to the screen after stopping it with Ctrl+S.
Ctrl+Q
```

### Moving the Cursor

Use the following shortcuts to quickly move the cursor around the current line while typing a command

```
# Go to the beginning of the line.
Ctrl+A or Home

# Go to the end of the line.
Ctrl+E or End

# Go left (back) one word.
Alt+B

# Go left (back) one character.
Ctrl+B

# Go right (forward) one word.
Alt+F

# Go right (forward) one character.
Ctrl+F

# Move between the beginning of the line and the current position of the cursor.
# This allows you to press Ctrl+XX to return to the start of the line, change something,
# and then press Ctrl+XX to go back to your original cursor position. To use this shortcut,
# hold the Ctrl key and tap the X key twice.
Ctrl+XX
```


### Deleting Text

Use the following to quickly delete characters

```
# Delete the character under the cursor.
Ctrl+D or Delete

# Delete all characters after the cursor on the current line.
Alt+D

# Delete the character before the cursor.
Ctrl+H or Backspace
```

### Fixing Typos

Use the following to fix typos and undo key presses

```
# Swap the current word with the previous word.
Alt+T

# Swap the last two characters before the cursor with each other.
# You can use this to quickly fix typos when you type two characters in the wrong order.
Ctrl+T

# Undo your last key press. You can repeat this to undo multiple times.
Ctrl+_
```

### Cutting and Pasting

Some basic cut and paste features

```
# Cut the word before the cursor, adding it to the clipboard.
Ctrl+W

# Cut the part of the line after the cursor, adding it to the clipboard.
Ctrl+K

# Cut the part of the line before the cursor, adding it to the clipboard.
Ctrl+U

# Paste the last thing you cut from the clipboard. The y here stands for “yank”.
Ctrl+Y
```

### Capitalizing Characters

Convert characters to upper or lowercase

```
# Capitalize every character from the cursor to the end of the current word, converting the characters to upper case.
Alt+U

# Uncapitalize every character from the cursor to the end of the current word, converting the characters to lower case.
Alt+L

# Capitalize the character under the cursor. Your cursor will move to the end of the current word.
Alt+C
```

### Tab Completion
Tab completion is a very useful bash feature. While typing a file, directory, or command name, press Tab and bash will automatically complete what you’re typing, if possible. If not, bash will show you various possible matches and you can continue typing and pressing Tab to finish typing.

```
# Automatically complete the file, directory, or command you’re typing.
Tab
```

### Working with Your Command History

```
# Go to the previous command in the command history.
# Press the shortcut multiple times to walk back through the history.
Ctrl+P or Up Arrow

# Go to the next command in the command history.
# Press the shortcut multiple times to walk forward through the history.
Ctrl+N or Down Arrow

# Revert any changes to a command you’ve pulled from your history if you’ve edited it.
Alt+R

# Bash also has a special “recall” mode you can use to search for commands you’ve previously run:

# Recall the last command matching the characters you provide.
# Press this shortcut and start typing to search your bash history for a command.
Ctrl+R

# Run a command you found with Ctrl+R.
Ctrl+O

# Leave history searching mode without running a command.
Ctrl+G
```
