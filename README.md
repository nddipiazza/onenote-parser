# onenote-parser

# How to build

## Mac OSX

* install jansson `brew install jansson`
* build with `make one_note_to_json`
* The executable `one_note_to_json` will be created.

## Linux

* install jansson `sudo apt install libjansson4`
* build with `make one_note_to_json`
* The executable `one_note_to_json` will be created.

## Windows 

* Install Mysys and MinGW
* Launch mysys.bat
* Download the jansson latest source tar file
* Untar it in a folder then cd to that folder from the mysys bash window
* Run `./configure --prefix=/c/MinGW && make && make install`
* Cd to this project's folder
* `make one_note_to_json`
