# mutt-config
mutt-config is the [mutt](http://www.mutt.org/) configuration used by me.
It is copied and stolen piece by piece from the internetz.
Contains the very nice [solarized] (https://github.com/altercation/mutt-colors-solarized.git) color theme as a submodule.


## Requirements

* [mutt 1.5.21] (http://www.mutt.org/)
* a couple of programms (mainly stuff that is in [mailcap] (jangingnicht/mutt-config/blob/master/mailcap)
* urlview

## Installation

Install mutt and do

    cd
    git clone https://jangingnicht@github.com/jangingnicht/mutt-config.git .mutt
    ln -s .mutt/muttrc .muttrc
    touch .mutt/alias #my alias file is excluded and mutt will be looking for it
    cd .mutt
    git submodule init
    git submodule update
