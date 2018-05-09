# pnutsay

This is a wrapper for [cowsay](https://en.wikipedia.org/wiki/Cowsay) dedicated to [pnut.io](https://pnut.io), made during the [2018/05/05 hackathon](https://wiki.pnut.io/5_May_2018).

## Install

Download or clone then cd in the folder.

Do `chmod +x ./pnutsay` if necessary, then do `./pnutsay -i` to install the custom .cow file and the pnutsay executable.

If all goes well, you're ready to go. 

If nothing works, you'll have to install cowsay, copy the pnut.cow file in cowsay's "cows" folder, and copy the pnutsay executable in a relevant location such as "/usr/local/bin" or equivalent.

## Usage

### Classic

    pnutsay Hello pnut :)

*Note that due to bugs, you can't pass other arguments to the classic pnutsay, only words to be used in the cow's bubble.*

### Dedicated to pnutprinter

    pnutsay -p Hello pnut :)

*Note that also due to bugs, you __can__ pass other arguments to the pnutprinter pnutsay. Example: `pnutsay -p "These pnuts are salty..." -s`*

## Tricks

### Copy to clipboard

On a Mac, add " | pbcopy" at the end of the command to send the result to the clipboard.

    pnutsay -p Hello pnut :) | pbcopy

Some applications add a space character at the end of the text when pasted, please remember to remove it before posting for pnutprinter. The last character has to be the asterisk.

### Send to Apero

If [Apero](https://itunes.apple.com/us/app/apero/id1219902108?l=fr&ls=1&mt=12) is running, send directly the pnutsay content to a new post with this command:

    open "apero://post=$(pnutsay Hello from Apero and pnutsay)"

## Screenshot

    pnutsay -p "Hello from pnutsay, guys\!"

![pnutsay](https://monosnap.com/image/5fNPlAf41BmgXNhw30TInUfKkDRd7q.png)

## Licence

The content of this repository is licenced under the MIT licence.