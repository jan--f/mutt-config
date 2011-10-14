# mutt-config
mutt-config is the [mutt](http://www.mutt.org/) configuration used by me.
It is copied and stolen piece by piece from the internetz.
Contains the very nice [solarized] (https://github.com/altercation/mutt-colors-solarized.git) color theme as a submodule.


## Dependencies

* [mutt 1.5.21] (http://www.mutt.org/)
* a couple of programms (mainly stuff that is in [mailcap] (jangingnicht/mutt-config/blob/master/mailcap))
* urlview
* [msmtp] (msmtp.sourceforge.net) as a sendmail replacement
* [fetchmail] (http://www.fetchmail.info/) to receive mail; mailboxes is
  expected to be in "~/.mail" (see [muttrc] (https://github.com/jangingnicht/mutt-config/blob/master/muttrc))
* [maildrop] (http://www.courier-mta.org/maildrop/) as an MDA and your own ~/.mailfilter file
* [antiword] (http://www.winfield.demon.nl/) for viewing .doc (and the like) attachments inline
* [lynx] (http://lynx.browser.org/) to unannoy html mails

## Installation

Install mutt and do

    cd
    git clone https://jangingnicht@github.com/jangingnicht/mutt-config.git .mutt
    ln -s .mutt/muttrc .muttrc
    cd .mutt
    touch alias #my alias file is excluded and mutt will be looking for it
    touch mailinglists #same as above
    git submodule init
    git submodule update

and change the personell stuff in muttrc 

