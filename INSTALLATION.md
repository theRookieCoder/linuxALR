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
7. Add `export PATH="/usr/local/share/rsi/idl/bin:$PATH"` to the _end_ of the file
8. Go to terminal and type in `chmod +x ~/bin/macALR`
9. Then type in `linuxALR`
10. If see this, `linuxALR: Fatal: No input file specified` skip to step 12
11. Else, type in `python3` and `nasm` and ensure that they do not give command not found errors
12. Now you are ready to use macALR! Be reminded that the `macALR` you type into terminal is not case sensitive (you can type in `macalr` and it will work just fine)
13. For information on how to use the script, read the `README.md` or type in `macALR -h`
