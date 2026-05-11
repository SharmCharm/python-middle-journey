# 2026-05-11: Environment setup

## What I've Done
- Installed WSL2 + Ubuntu 24.04 LTS
- Installed build tools: build-essential, libraries for future Python builds
- Set up Git: username Sharm, email gmail, default branch main
- Generated an ed25519 SSH key and added it to GitHub
- Created the python-middle-journey repository, first commit

## What I learned
- `wsl --shutdown` fixes most WSL network glitches
- `apt update` is not the same as `apt upgrade` — the first updates the list, the second updates the packages themselves
- `git add` ≠ “save file”; it means adding to the staging area
- In Git, history is immutable thanks to SHA-1 commit hashes
- The default branch is now `main`, not `master` (since 2020)

## Issues
- WSL couldn't see the network on first launch — fixed by restarting
- The libncursesw5-dev package has been renamed to libncurses-dev in Ubuntu 24.04

## What's Next
- Installing Python 3.13 via pyenv
- Virtual environments
- Getting started with Python Fundamentals
