# Lightning talk - Some cool tools

* I recently changed jobs, in the process I discovered a few new tools

## Keybase

* Easy to use crypto commands (cf. GPG)
* Saltpack (NaCl + MessagePack)
* Integrated with social media
* Not optimaised for perfromance
* Under heavy developement (go)

### KBFS

* Uses FUSE
* Public, Private and Team folders
* Use case, tansfering and syncing files between machines
* Use case, sharing secrets with others

### Private git repos

* Is a git remote helper
* Use case is private git repos you want on more than one machine

### Social crypto

* Teams
* Slack

## RipGrep

* Ack style grep utility
* Fast for ack use cases (filtering then grepping in a large repo)
* Fast for grep use cases (searching for pattern in large file or many files)
* Written in rust
* Faster than silversurfer (ag)

## Vim Pathogen

* Pathogen makes it super easy to install plugins and runtime files in their own private directories.

## Vim Airline Tabline extension

* Airline is a statusline plugin for vim similar to powerline
* Tabline is an Airline extension for showing tabs and buffers
* If you are using vim tabs then switch now!

## Asciinema

* A terminal recorder that records and plays back terminal sessions.
* Uses a pseudoterminal
* Inspired by script
* Running now

## Grip

* Preview GitHub Markdown files locally before committing them.
* Uses GitHub markdown API to render locally
* Makes the html page available via an http server
* You can see how it will look in github/gitlab before pushing
