# urxvt-espeak
A Perl extension to urxvt to enable automatic/manual speech of selection in the urxvt terminal

## Description

If you use the urxvt terminal and your system has the espeak command, this perl extension can speak the selection automatically or manually.   

To play manually you will simply have to use the CTRL+Right click menu of urxvt and choose item "Espeak selection".  

## Prerequisites

- Urxvt
- espeak
- Perl

## How to install and load

1. Copy this file to your urxvt perl directory, e.g. in $HOME/.urvxt/perl/ 
2. Add this to your urxvt resource file, e.g. in .Xresources: 
	URxvt.perl-ext:           default,espeak 

(optional) If you do not wish to have selection automatically speaked on
selection, change the variable below to false (look for the text SET TO false BELOW IF (..), and set it to false instead of true, in that case you will have to use the menu).


