# linuxALR Installation Guide

Before starting, make sure you have python3 and the netwide assembler installed  
Latest Python download: <https://www.python.org/downloads/>  
Latest NASM download: <https://www.nasm.us/>

1. Clone this repo
2. Open a file explorer and navigate to your home directory
3. If you see a folder named _exactly_ 'bin', skip to the next step. Else create a new file called 'bin' and make sure to _not use any capital case letters_
4. Move or copy-paste the 'linuxALR' bash script to the 'bin' folder
5. Open terminal and type in `chmod +x ~/bin/macALR`
6. Then search for a file called `.bachrc` and open it using any text editor
7. Add `export PATH="~/bin:$PATH"` to the _end_ of the file
8. Then type in `linuxALR`
9. If see this, `linuxALR: Fatal: No input file specified` skip to step 11
10. Else, type in `python3` and `nasm` and ensure that they do not give command not found errors
11. Now you are ready to use macALR! Be reminded that the `linuxALR` you type into terminal is case sensitive (if you can type in `linuxalr` and it will not work
12. For information on how to use the script, read the `README.md` or type in `macALR -h`
