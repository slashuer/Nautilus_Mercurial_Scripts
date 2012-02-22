# Stats

Programming Language: BASH Shell Script
Source: Open Source
OS: Linux+Nautilus
Price: Free
Program Version: 2.0


# About

Nautilus Mercurial Scripts is a set of scripts to do what tortoisehg use to do.


# Install

     START=$(pwd)
     sudo apt-get install mercurial tortoisehg
     mkdir -p ~/.gnome2/nautilus-scripts/
     cd ~/.gnome2/nautilus-scripts/
     hg clone https://bitbucket.org/slashuer/nautilus_mercurial_scripts
     mv nautilus_mercurial_scripts/Mercurial/ .
     rm -R nautilus_mercurial_scripts/
     cd $START


