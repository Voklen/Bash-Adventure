# Terminal-Adventure
A interactive novel played purely through a terminal by navigating (mainly) with "cd" and interacting (mainly) with a command-line text editor.

## This game is currently work-in-progress, I would recommend coming back when it is complete

To start off on this adventure you will need:

- A terminal (I will be using the GNU/Linux one for the explanations) 
- A basic ability to use the `cd` and `less` commands (or equivelent)  

If you already have all of these, then you can begin! Just `cd` into the start directory, and open up "instructor" with you text editor to get started, they'll explain everything. Good Luck!

If not:

## Get a terminal
*NIX distro:\
Just try searching for "Terminal" in your programs and it should come up. If it doesn't... idk... search it up.

MacOS:\
Type "Terminal" into spotlight search, and it should be the first one.

Windows:\
Get a *NIX OS... Or the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about)

## How to use the `cd` command
cd stands for Change Directory (another name for folder). To use it just type `cd` followed by the directory you want to go to. By default, the terminal will start you in the home directory. So:\
`cd Desktop/`
will take you to the Desktop folder (On most operating systems, file names and commands are case sensitive) and your terminal will go from:\
`username@computername:~$`\
to:\
`username@computername:~/Desktop$`\
You can also move through multiple directories in one command. For example:\
`cd Downloads/Terminal-Adventure-main/`\
if both these folders exist you should now be at:\
`username@computername:~/Downloads/Terminal-Adventure-main$\`\
You can now use this to navigate to the folder this file is in.

## How to use the `less` command
There was once a program used to display the contents of files called `more` although it only had the ability to scroll forwards. Less allows users to scroll backwards as well, the name came from the joke of doing "backwards more.". To use it simply type `less` followed by the name of the file. For example:\
`less instructor`\
will will open up the file `instructor` (again, on most OS's, file names and commands are case sensitive). You can then scroll with the arrow keys and quit by pressing q.

## Using a command-line text editor

There are many different command-line text editors, but I am just going to cover the 3/4 most common ones.

### Vim/Neovim
Vim and Neovim are extensively configurable, cross-platform, and highly efficient, although they are quite complicated and are possibly too advanced for beginners. Both of these text editors are quite similar, and I would recommend trying both to see which one you prefer (Although Vim is already installed as vi on most *NIX systems and macOS). Overall these editors are for users who want a powerful text editor and willing to put in the time to learn it.

If you are on a *NIX distro, Vim is probably already installed as `vi`. For Neovim, https://github.com/neovim/neovim/wiki/Installing-Neovim

If you are on macOS, Vim is probably already installed as `vi`.For Neovim, https://github.com/neovim/neovim/wiki/Installing-Neovim

If you are on Windows and used my method to get the terminal, install it with:\
`sudo apt install vim`\
or\
`sudo apt install neovim`

Before starting, you will need to learn the basics of Vim (They're the same for Neovim): https://peertube.su/videos/watch/def600cf-6a79-45d3-ad62-da122ddabd37 \
Or if you prefer a more interactive option: https://www.openvim.com \
And if you want to read the docs: https://www.vim.org/docs.php and https://neovim.io/doc

### GNU Emacs
Just like Vim/Neovim, Emacs is extensively configurable, cross-platform, and efficient. One difference is that you can use Emacs for everything from a calendar, to a web browser, to an organisation tool, and everything in between (There are even games for Emacs!). Despite this, Vim/Neovim is quicker to use than Emacs if you're just quickly opening, reading/editing and closing files (Which is what you'll be doing most of the time in this adventure).

If you are on a *NIX distro, https://www.wikemacs.org/index.php/Installing_Emacs_on_GNU/Linux 

If you are on macOS, https://www.emacswiki.org/emacs/EmacsForMacOS 

If you are on Windows and used my method to get the terminal, install it with:\
`sudo apt install emacs`

Before starting, you will need to learn the basics of Emacs: https://www.linuxfordevices.com/tutorials/linux/emacs-editor-tutorial
And if you want to read the docs: https://www.gnu.org/software/emacs/documentation.html

### Nano
The other three editors have been extremely customisable and flexible with **steep** learning curves. Nano is the exact opposite. If you want simplicity and only need to create & edit text files (Which is all you'll need for this adventure), nano is the editor for you.

If you are on a *NIX distro,is probably already installed as `nano`.

If you are on macOS, nano is probably already installed as `nano`.

If you are on Windows and used my method to get the terminal, install it with:\
`sudo apt install nano`

Before starting, you will need to learn the basics of Nano (which isn't much): https://peertube.su/videos/watch/8cf32759-994f-42e3-aa1a-fadf661bbec5
And if you want to read the docs: https://www.nano-editor.org/docs.php
