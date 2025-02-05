Alero Command

Alero Command is a lightweight simulated operating system made purely in Python. It has its own CLI, commands, and package manager.
Also folders are called places.

The Current version of Alero Command is 1.0 beta. so "Alero Command 1.0 Beta". it is a LOT better than the testing release. i promise.

« NEW STUFF »

- New package manager: I added a new package manager (apm) that lets you install packages. It's offline, so no internet is needed!
- New coloration: Some commands and inputs are now colored using ANSI escape codes. If your terminal doesn’t support them, Alero will ask if you want to disable them.
- New package commands: Packages can now add new commands to the commandexec() function, which is a great addition!
- Alero Command

I hope you like these additions!

« NEW COMMANDS »

- main – Not a command itself, but similar to sudo in Linux. If you don’t know what that is, read this: https://en.wikipedia.org/wiki/Sudo
- rst – Resets Alero Command. Great for updating the system seamlessly or just resetting.
- apm – A new package manager for installing packages.
- cacs – A calculator program for quick calculations.
- sysinfo – Outputs the name, type, version, and special info about Alero Command (can be installed via apm).
- test – A testing package command (will be removed in the future).

I hope you like these new commands!
« HOW TO USE »

Alero Command doesn’t have many dependencies, but here’s how to install what’s needed:
『 INSTALLATION 』

First, you'll need to install Python (version 3.x). You can download it from python.org or install it via terminal:
Windows:
<pre><code> winget install Python.Python </code></pre>
MacOS:
<pre><code> brew install python </code></pre>
Debian/Ubuntu-based:
<pre><code> sudo apt update sudo apt install python3 sudo apt install python3-pip </code></pre>
Arch Linux-based:
<pre><code> sudo pacman -Syu python sudo pacman -S python-pip </code></pre>
Fedora-based:
<pre><code> sudo dnf install python3 sudo dnf install python3-pip </code></pre>
openSUSE:
<pre><code> sudo zypper install python3 </code></pre>
Void Linux:
<pre><code> sudo xbps-install -S python3 </code></pre>
Alpine Linux:
<pre><code> sudo apk add python3 </code></pre>  New file build: Alero now has a custom file build, which you can find in the file section.

Then you can install the Zip file (whatever version you want) and extract it into somewhere. and use it however you like!
 
『 USAGE 』
I bet you dont know how the commands work, lemme help you with that!
okay so, this is a list of commands and how to use them:
* help: you can type out "help" in the terminal and it will display a help guide of what every command does.
* crt: by typing out crt, you are creating a new file. first type "crt" and press enter, then the file and and file contents and done!
* read: reads a file, you type "read" in the terminal and press Enter, then enter the file name of your file, and then it will output its contents.
* lsx: lists all the files and places in your main system. type "lsx" and it will list all the files in your current directory, and places.
* del: deletes a file, you type "del" and hit Enter, then enter the file name of the file you wanna delete. and press enter. you can also delete the entire system be typing /main but be carefull with that thing!
* wrt: writes to a file. type "wrt" then press Enter and enter the name of the file you wanna edit. then put in the thing you want, and press enter. then it asks you if you wanna append. type y for yes or anything else for abortion.
* ren: renames a file. type "ren" then press Enter, enter the current name of the file, hit Enter, enter your new name. and done!
* echo: echoes a string. you can type "echo" and type the string you want to print out after it. no pressing Enter this time :)
* time: you can tell the time by typing out "time" and pressing Enter.
* apm: the Alero Package manager is a bit more complex. but well go throught it. type out "apm" and press enter. then type new to install a new package, or del to delete a package. then just type the package name (in lower-case) and then type y to confirm and n to cancel.
*  /apm: list of all the avaible packages: test, sysinfo.
Package commands:
* sysinfo: type out "sysinfo" and hit enter to review your current type, version and other info about your OS.
* test: does completely nothing. only prints out "This is a testing package. It will eventually be removed.", its still good for debbuging tho.

『 FILE BUILD 』
the current Alero Command file build is kinda lame. but here it is:

    "main": {
        "files": {},
        "packages": {}
    }
the "main" place is like the root of the system, it holds everything.
the "files" place inside main if the place youre going to actually use your files and stuff.
and the "packages" place is used for storing packages, it doesnt work. yet.

and thats it! enjoy Alero command, and if you encounter any bugs or issues, please report it in the issues thing in Github. thanks.
Also if you have any suggestions, just contact me, however you want idc. but Github is good.
Have a good time using Alero!
