### cshmarks is a shell script that allows you to save and jump to commonly used directories. It supports tab completion.
#### It is inspided by [bashmarks](https://github.com/huyng/bashmarks) but it is not compatible with it.

## Install

    $ git clone https://github.com/panosdim/cshmarks.git ~/.cshmarks
    $ echo "source ~/.cshmarks/cshmarks" >> .cshrc

## Shell Commands

    s <bookmark_name> - Saves the current directory as "bookmark_name"
    g <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    d <bookmark_name> - Deletes the bookmark
    l                 - Lists all available bookmarks
    
## Example Usage

    $ cd /var/www/
    $ s webfolder
    $ cd /usr/local/lib/
    $ s locallib
    $ l
    $ g web<tab>
    $ g webfolder

## Where Bashmarks are stored
    
All of your directory bookmarks are saved in a file called ".cdirs" in your HOME directory.
