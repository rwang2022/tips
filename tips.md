# Guidelines
### if unspecified, commands will work on both Git Bash and Terminal
<br>

# VSCode<br>
* `path/to/folder $ code .` <br>
    opens that folder in VSCode 

* `'path/to/folder $ code file.txt'` 
    opens that file in VSCode <br>
    if it doesn't exist, VSCode will open anyway and you can save it 

* `Ctrl+Shift+X` shows your extensions 
* `Ctrl+Shift+P` brings up Command Palette
* `Ctrl+,` brings up settings editor

# Git Bash <br>
## miscellaneous
`pwd` <br>
`$ echo $HOME` to figure out home directory<br>

## move
`path/to/ $ mkdir folder2` to make dir <br>
`path/to/ $ mv foo.txt folder2/` to move to folder2 <br>

## delete
`path/to/folder $ rm -r folder2` deletes `folder2` and all nested (due to `-r`) <br>
`rm filename` to delete `filename` <br>
`rm -i venv/*` to delete all files in `venv` one by one 

# Terminal <br>
`path\to\folder $ rd /s folder2` removes folder2 and all nested inside folder (due to `/s`) <br>
`open `

## Issues:
* originally `python` didn't work in Git Bash (follow https://stackoverflow.com/a/36530750)
    * you basically just add the alias to `.bashrc`. Idk what `touch` means
* `~` means home directory
* you might need to `pip install virtualenv`

# General Tips
* to read files, use `cat` (Linux) or `type` (windows)