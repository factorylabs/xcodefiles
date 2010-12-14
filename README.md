
# Xcode Files

A collection of themes, macros, user scripts and settings for working in Xcode. The Xcode Application likes to stick files just about everywhere, so we use symbolic links to help in the management.


## Installation & Contents

Before you start symlinking your files, make sure you back up the original directories. Otherwise there is a good chance you'll overwrite your own awesomeness.

1. Clone this repository
- `cd ~/path/to/xcodefiles/`
- `bash update`
- start syncing away based on the directory contents below


### themes

Various color styles and themes for the editor. To link it up:

      cd ~/Library/Application\ Support/Xcode/
      ln -s ~/path/to/xcodefiles/themes/ Color\ Themes

**Most themes use the custom [MesloGM font](https://github.com/andreberg/Meslo-Font) which needs to be installed.**


### specifications

Macro code completion and general helpyness. To get the party started:

      cd ~/Library/Application\ Support/Developer/Shared/Xcode/
      ln -s ~/path/to/xcodefiles/specifications/ Specifications

### scripts

Installs all of your user scripts. This one is not ready yet.


### community

This directory is reserved for submodules from various community repositories and is not symlinked. Running `bash update` will pull the latest changes and copy the new files into their respective symlinked directories overwriting as necessary.

- [liyanage-macros](https://github.com/liyanage/xcode-text-macros): Macros saved to the specifications directory. Also contains a cheat sheet generator for displaying a listing of the installed macros. Check out the submodule's repository for more information.


## Todo

1. Get User Scripts setup
- Get GD's User Scripts in
- Sync up with the other F/ peops and their settings
- Finish documenting the process in the README

