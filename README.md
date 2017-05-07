# RCFILES

My own collection of rcfiles for UNIX shells.

**NOTE:** This is provided AS IS. No guaranties. I'm not responsible if this eats your files, or lunch, does anything you don't like, etc. Use at your own risk.

## What is this?

This is a collection of rcfiles (or dotfiles) that I use for my shell environments (currently Linux, Mac OS, and Cygwin).

These collections of files started as a fork of [puppetlabs/puppetlabs-rcfiles](https://github.com/puppetlabs/puppetlabs-rcfiles), but has grown into its own thing over time.

## What does it do?

Mainly, it configures bash and vim. It also contains configurations for screen, tmux and rubygems. Be aware that the tmux configuration is untested as I stick to screen for availability reasons (same reason I stick to bash instead of zsh).

## How do I use it?

I recommend creating your own fork as you will probably want to change this to suit your preferences.

The install process is simple, clone into a directory (I use $HOME/src/rcfiles), then run the install script. Done

The install script tries to preserve the existing files. But you should definitely check the script before running it.

After installing the rcfiles, you need to reload your environment (just run `exec bash`).

## Why not use some more advanced shell prompt?

Because I tend to install this on every account, even temporary ones. So I don't what to depend on any external package. It has to work on Ubuntu, Debian, Gentoo, SLES, Mac OS, Cygwin. On current versions as well as old ones.


## Why not use plugin manager for Vim?

Because I tend to install this on every account. I want to keep it as simple to install as possible.




