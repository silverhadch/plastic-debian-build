# Plastic Debian Package Build

This repository contains the necessary files and configurations to create a Debian package for **Plastic**, an NES emulator built in Rust.

## Contents

- **Control Files**: Metadata and control files for packaging.
- **Build Scripts**: Scripts and configuration for compiling and packaging.
- **Man Page**: `plastic.1` man page for command-line usage.
- **Icons and Desktop Entry**: Icons and `.desktop` file for application menu integration.

## Building the Package

To build the Debian package, use the following command in the root of the repository:

```bash
dpkg-deb --build plastic
