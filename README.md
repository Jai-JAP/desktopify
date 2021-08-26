# desktopify
Convert Ubuntu Server for Raspberry Pi into a Desktop


This is a fork of [wimpysworld](https://github.com/wimpysworld)'s [desktopify](https://github.com/wimpysworld/desktopify) with support for any Ubuntu version prior to 20.04.  
  
Also it supports apt-fast if available for faster downloads.

### For original Readme go [here](README-old.md)

## Installation

  * Put an [Ubuntu Server image for Raspberry Pi](https://ubuntu.com/download/raspberry-pi) on a SDHC card.
  * Boot the Ubuntu Server SDHC on a Raspberry Pi 2, 3 or 4.
  * Login to the Raspberry Pi; username `ubuntu` and password `ubuntu`
      * You will be prompted to change the password
  * Clone the project
    * `git clone https://github.com/Jai-JAP/desktopify`
  * Change your current directory to desktopify directory
    * `cd desktopify`
  * Convert the server to a desktop
    * See [Usage](https://github.com/Jai-JAP/desktopify#Usage)

### Usage

  `sudo ./desktopify --de <desktop environment>`

Available desktop environments are:

  ```
  lubuntu
  kubuntu
  ubuntu
  ubuntu-budgie
  ubuntu-kylin
  ubuntu-mate
  ubuntu-studio
  xubuntu
  ```

You can also pass the optional --oem option which will run a setup
wizard on the next boot.
