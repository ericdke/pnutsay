# pnutsay

This is a wrapper for cowsay dedicated to pnut.io, made during the 2018/05/05 hackathon.

## Install

Download or clone then cd in the folder.

Do `chmod +x ./pnutsay` if necessary, then do `./pnutsay -i` to install the custom .cow file and the pnutsay executable.

If all goes well, you're ready to go. 

If nothing works, you'll have to install cowsay, copy the pnut.cow file in cowsay's "cows" folder, and copy the pnutsay executable in a relevant location such as "/usr/local/bin" or equivalent.

## Usage

### Classic

    pnutsay Hello pnut :)

### Dedicated to pnutprinter

    pnutsay -p Hello pnut :)

### Tricks

On a Mac, add " | pbcopy" at the end of the command to send the result to the clipboard.

    pnutsay -p Hello pnut :) | pbcopy

Some applications add a space character at the end of the text when pasted, please remember to remove it before posting for pnutprinter. The last character has to be the asterisk.

## Screenshot

    pnutsay -p "Hello from pnutsay, guys\!"

![pnutsay](https://monosnap.com/image/5fNPlAf41BmgXNhw30TInUfKkDRd7q.png)

## Licence

The content of this repository is licenced under the MIT licence.