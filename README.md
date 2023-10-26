# Inferno Test Builds

This repository contains GitHub workflows for ports of the
[Inferno operating system](https://inferno-os.org) to various hardware
platforms.

## Structure

Each build is defined and performed in a branch of its own, using a workflow
file with a common name. The branch name usually reflects the branch name in
the associated repository containing the Inferno sources. An alternative
approach would be to have multiple workflows in the same branch.

## Builds and rebuilding

When browsing the repository on GitHub, you can select the Actions tab on the
repository page to see recent builds.

If you want to rebuild a branch, fork the repository on GitHub, enable Actions
and trigger a rebuild manually.

## Ports

Builds are performed for the following ports:

* STM32F405
* SAMD51
* Apollo3
* Pi Pico (using [Caerwyn's port](https://github.com/caerwynj/inferno-os/tree/pico))

There is also a build for the hosted i386 version of Inferno.
