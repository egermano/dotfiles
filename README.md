# Germano's dotfiles

This is a fork of Mathias’s dotfiles customised for my use.

## Installation

### Using Git and the bootstrap script

You can clone the repository wherever you want. (I like to keep it in `~/Projects/dotfiles`, with `~/dotfiles` as a symlink.) The bootstrapper script will pull in the latest version and copy the files to your home folder.

```bash
git clone git://github.com/egermano/dotfiles.git && cd dotfiles && ./bootstrap.sh
```

To update, `cd` into your local `dotfiles` repository and then:

```bash
./bootstrap.sh
```

Alternatively, to update while avoiding the confirmation prompt:

```bash
./bootstrap.sh -f
```

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

### Sublime Text Config Files
I have many mac to dev, to sync configs of Sublime I use a [Dropbox](http://dropbox.com).

To do this you will need to create some folders (Backup, Installed Packages, Packages, Pristine Packages, Settings) in your Dropbox, edit ```sublime.sh``` with your corret folder. 

And run this:

```bash
./sublime.sh
```