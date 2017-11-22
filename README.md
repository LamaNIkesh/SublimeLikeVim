## Sublime theme for Vim editor
![sample](https://user-images.githubusercontent.com/13660762/33134736-6bf7eff6-cf98-11e7-9e7a-1eeccf4ad140.png)

<a name="usage-linting"></a>
Minimalistic .vimrc file for setting up your vim editor with sublime like look.It also has powerline, numbering, syntax check and molokai theme. 

## Installation

I used Vundle to manage packages to make it easier. So, I suggest you install Vundle.
You can install it easily using the following commands:

```Execute the git clone and place it into ~/.vim/bundle/Vundle.vim
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
Add the file to your user's home directory
touch ~/.vimrc
```
Simply copy contents of .vimrc into your .vimrc file. You should have a .vimrc file in your home directory. 
Run 
```
ls -all 
```

to see all the files in current directory. 

After copying contents to your .vimrc files. Run
```
:PluginInstall
```
from .vimrc. This installs all the plugins necessary as mentioned in .vimrc file. 

## Troubleshooting
In case of "The ycmd server SHUT DOWN" error. Run the following commands
```
cd ~/.vim/bundle/YouCompleteMe
./install.py --clang-completer
```
This should resolve the issue.
