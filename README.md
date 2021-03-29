# Scheduled Scripts Setup

## Schedule automatic macOS tasks

_Scheduled Scripts Setup_ is a convenient interface for scheduling macOS scripts to run daily. It is similar in spirit to the Folder Actions Setup application.

Scheduled Scripts Setup modifies property list files in `~/Library/LaunchAgents`, which are read by `launchd` (part of the macOS system) and automatically scheduled for execution. The interface is fairly barebones, but definitely works; you can check its output by navigating to `~/Library/LaunchAgents` in Finder.

Scripts scheduled for daily execution can be written in any [hashbang](https://en.wikipedia.org/wiki/Shebang_(Unix))-compatible language, including BushelScript, sh/Bash/Zsh, Python, Ruby, etc., etc. AppleScript scripts will work if saved in plain text (`.applescript`) format and `#!/usr/bin/osascript` is at the top of the file.

## Get started

Scheduled Scripts Setup requires BushelScript English v0.3.0, which is available [here](https://github.com/BushelScript/BushelScript/releases).

To run Scheduled Scripts Setup, first download [Scheduled Scripts Setup.bushel](https://github.com/BushelScript/Scheduled-Scripts-Setup/raw/master/Scheduled%20Scripts%20Setup.bushel). Then either open it in BushelScript Editor and click Run, or run `bushelscript path/to/Scheduled\ Scripts\ Setup.bushel` from a CLI shell.
