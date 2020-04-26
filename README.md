# Scheduled Scripts Setup

## Schedule automatic macOS tasks

_Scheduled Scripts Setup_ is a convenient interface for scheduling macOS scripts to run daily. It is similar in spirit to the Folder Actions Setup application.

Scheduled Scripts Setup modifies property list files in `~/Library/LaunchAgents`, which are read by `launchd` (part of the macOS system) and automatically scheduled for execution. The interface is fairly barebones, but definitely works; you can check its output by navigating to `~/Library/LaunchAgents` in Finder.
