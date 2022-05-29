# Purpose

This repo is simply a place for me to keep my dot-files for linux and mac machines. 

# dot-files

## .bash_profile

This file is often left unused on fresh modern linux installs. However it is
still used on login as normal.

So here is where I keep all my command line customizations for interactive 
terminal sessions. 

## .inputrc

Interactive intepreters like `python3`, `irb` or the `mysql` client 
use Readline to control their behavior.  Readline checks `.inputrc` 
when starting up. 

I like to have basic `vim`-like behavior on the terminal for quick and dirty
research so I can edit in a familiar way.

# References

* Interactive interpreter behavior - [stackoverflow](https://stackoverflow.com/questions/6636124/how-do-i-make-vi-editing-mode-work-in-irb-when-using-rvm)