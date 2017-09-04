# This project is dedicated to renewing the ability for Minecraft servers to use native bukkit plugins along with Forge mods.

# Phoenix

![Phoenix](Phoenix_icon.png)

[![Build Status](https://travis-ci.org/djoveryde/Phoenix.svg?branch=master)](https://travis-ci.org/djoveryde/Phoenix)

## Building Phoenix
* Checkout project
  * You can use IDE or clone from console:
  `git clone https://github.com/djoveryde/Phoenix.git`
* Setup
  * Setting up submodules:
  `git submodule update --init --recursive`
* Building
  * Build the project for Linux:
  `./gradlew build`
  * or for Windows:
  `./gradlew.bat build `

All builds will be in `build/distributions`