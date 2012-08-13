# QuickPass - A very simple password manager

## Overview

QuickPass is a set of 2 shell scripts that I've been using for quite
a few years to keep my passwords safe. It makes use of GPG's symmetric
encryption to store, well, passwords, and provides a simple way to
look them up--the `passlook` command.

## Usage

Set the `PASSFILE` environment variable to a file that's stored in a 
safe place (the permissions should be 600). 

To add a password, to `passadd [account name] [description]` and setup
follow the instructions.

To look up a password, `passlook [search term]` and enter your master
password.
