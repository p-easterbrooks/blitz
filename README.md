# Brightspot Local Installation Tool

Installs and configures local development instances of Brightspot from existing projects

The autogenerated directory structure is as follows

                    |Main Project Directory|
                   /                        \
                  /                          \ 
      |Brightspot Project|            |Tomcat Directory|

## Minimum Requirements
* Unix-like operating system (i.e. OSX/macOS, Linux)
* Bash 3.2 or greater (`bash --version` to check)
* MySQL 5.6.* or greater (must be running when executing install script). MySQL MUST BE ON YOUR PATH. An alias will fail
* [GNU Wget 1.18](https://www.gnu.org/software/wget/), this will install itself for Mac users with [Homebrew for macOS](https://brew.sh/) installed. Otherwise, Wget can be found using `apt-get install wget` on most Linux flavors that do not natively include it or through download links

## Installation
For macOS users, an option to install via Homebrew is available. Simply execute `brew install p-easterbrooks/blitz/blitz`

If you choose to not use Homebrew or are on a Linux machine, download the release files and move `blitz` to a directory where you normally execute scripts from (i.e. `/usr/local/bin` or `/home/YOUR_USERNAME/bin` on Linux).

## Using the Installer
From the directory you typically install Brightspot projects in, run `blitz` and follow the prompts. The script will download and configure all necessary resources.

## [Frequently Asked Questions](https://github.com/p-easterbrooks/blitz/wiki/Frequently-Asked-Questions)
