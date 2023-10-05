# Command Line Basics
## Definition
A **command line** (aka **terminal**) is a text based interface with a computer's system. This can be used instead of a graphical user interface in order to execute more complex commands and interact more directly with the computer's operating system. It utilizes a basic command structure similar to coding.

## Directories
Most OS's use a hierarchical system of directories and folders. Think of it as a complex Russian nesting doll. A folder can have a folder inside of it infinitely. 

There is a root directory, and inside the root directory are folders that organize files and sub-folders by type and purpose. Common folders are *'Downloads'*, *'Documents'*, *'Applications'* etc

### Directory Commands

- `pwd`: "Print Working Directory". typing `pwd` prints your current location within the computer directory.
- `ls`: "List". typing `ls` will list the files and folders within your current location in the computer directory. *Example: typing `ls` in **Downloads** will list all files and folders saved in **Downloads***

  - `-l` is an argument which can be added to `ls` to show more information on the files and folders listed, such as the permissions and author of a file.
- `cd`: "Change "Directory". This allows you to change locations in you computer directory. Typing only 'cd' without an argument will bring you to the root directory. A file or folder must be typed after it to change to a different location.
    - `..` is an argument that allows you to go to the directory above you in the hierarchy. adding more '.'s to it will make you go more steps backwards.

## Files
Everything is a file. Every interaction with a computer when dealing with code will ultimately be interactions with a bunch of files.

