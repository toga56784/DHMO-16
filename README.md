# DHMO-16

## A fantasy home console based loosely off of the SNES.

DHMO-16 is a fantasy home console built in Java to give FC devs a place to start and me something to work on. This is project is currently not in a useable state but it will be soon. For now check out our:

* Amazing README.md
* Specifcations further down
* And how _you_ can help.

# I will put a video covering everything here

# How to install
1. Go to the side and find the release for your OS.
2. Download and follow the installer.
3. The app will then be available for use.

# How to install (For Contributors)
Since this project is very open for people to use it as a base I would recommend you clone and rename this. If you are planning on contributing to this project then you should fork the project and then submit a pull request after you are done. See [contributor guidelines](#guidelines-for-contributors) before submitting a pull request.

# Guidelines for contributors
The following are some basic guidelines for contributors.

## Making a PR?
* File an issue that your PR resolves and reference the issue in the PR
* Make sure that when you submit a PR you squash your commits

# If you are feeling kind
Subscribe to my [youtube](https://www.youtube.com/@toga56784)

# Don't Read Me
**Warning:** Don't README unless you want to. The remainder of this README file is just notes for myself and anyone interested in helping to know exactly how the project works. It covers the specifications.

## CPU

### Registers
* The DHMO-16 uses 8 16-bit general purpose registers labeled R0-R7.
* A 16 bit Program Counter that stores the currently accessed line's index in ROM.
* A 16 bit Stack Pointer that stores the top of the stack.

### Instructions
| 
