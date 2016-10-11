# lgc-hooks
My pacman hooks.

* deleted_files.hook - lists processes using deleted or older version of system files (similar to 'zypper ps'), requires lsof
* paccache.hook - cleans up pacman's cache, by default keeping up to 2 versions of each package
* pacdiff.hook - lists pacnew and pacsave files
* reflector.hook - uses reflector to find best mirrors after each pacman-mirrors update, requires reflector
* upgrade_news.hook,upgrade_stamp.hook - records a timestamp of an upgrade operation and displays Arch Linux news published after recorded timestamp, requires rsstail
