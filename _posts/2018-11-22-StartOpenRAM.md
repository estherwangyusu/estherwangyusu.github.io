#Start with OpenRAM

## Git Clone the Source
git clone git://

## Linux
### Show Current Directory Address
pwd
### Copy document
cp source dest
### Rename document
mv filename1.ext filename2.ext
###bashrc
Bash runs the contents of bashrc file at each launch to load your preference.
This shell script is found in each user's home directory. It's used to save and load your terminal preferences and environmental variables.
set up all of the tools on mada0 by adding "source/mada/software/setup.sh to the end of your .bashrc file inyour home directory.

## Export Environment Varibles
export OPENRAM_HOME="$HOME/openram/compiler"
export OPENRAM_TECH="$HOME/openram/technology"
export PYTHONPATH="$PYTHONPATH:$OPENRAM_HOME"

**Note: it's OpenRAM not openram**

## Python3
### Find Python3 Path
which python3

### Exit Python3
Ctrl+D

## Jekyll
jekyll serve index.md

jekyll build index.md
## Vim
:w - save the file
:q - exit
:wq - save and exit

## Unit Tests
Directory:
$OPENRAM_HOME/compiler/tests
