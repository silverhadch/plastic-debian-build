# Plastic Debian Package Build

We developed an automatic way to build .deb packages in the plastic repo so this is archieved.

This repository contains the files and configurations needed to build a Debian package for **Plastic**, an NES emulator built in Rust.

## Repository Contents

- **Control Files**: Essential metadata and control files required for packaging.
- **Build Scripts**: Scripts and configurations to compile and package the application.
- **Man Page**: The `plastic.1` man page for command-line reference.
- **Icons and Desktop Entry**: Icons and a `.desktop` file for seamless application menu integration.
- **`.deb` Package**: Pre-built Debian package for easy installation.

## Building the Package

To build the Debian package manually, use the following command in the root of the repository:

```bash
dpkg-deb --build plastic
