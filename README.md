# Brightspot Local Installation Tool

Installs and configures local development instances of Brightspot from existing projects

The autogenerated directory structure is as follows

                    |Main Project Directory|
                   /                        \
                  /                          \ 
      |Brightspot Project|            |Tomcat Directory|

## Minimum Requirements
* UNIX-based operating system (i.e. OSX/macOS, Linux)
* Bash 3.2 or greater (`bash --version` to check)
* MySQL 5.6.* or greater (must be running when executing install script). Make sure MySQL is on your PATH
* [GNU Wget 1.18](https://www.gnu.org/software/wget/), can be found using `apt-get install wget` on most Linux flavors, `brew install wget` on [Homebrew for macOS](https://brew.sh/), or through download links

## Installation
For macOS users, an option to install via Homebrew is available. Simply execute `brew install p-easterbrooks/blit/blit`

If you choose to not use Homebrew or are on a Linux machine, download the release files and move `blit` to a directory where you normally execute scripts from (i.e. `/usr/local/bin`)
After downloading, create a `bin` directory in your home directory if it does not already exist and copy the `bsp-install` script to `~/bin` and add `~/bin:$PATH`to your path in your `~/.bash_profile`. Alternatively, you may add the script to any other directory you use executable scripts.

## Using the Installer
From the directory you typically install Brightspot projects in, run `bsp-install` and follow the prompts. The script will download and configure all necessary resources.
