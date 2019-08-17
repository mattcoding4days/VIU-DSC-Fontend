# **DSC Portal App Beta Front-End only**
### Installation for Front-end dependencies:
The front end is pure CSS, using SASS as a pre-processor

### Install nodejs and npm on your system

#### Arch/Manjaro Base

```console
$ pacman -S nodejs npm
```
#### Debian/Ubuntu Base
```
$ sudo apt update
$ sudo apt install nodejs
$ sudo apt install npm
```
#### Mac OSX
Install Home brew
```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install node
```
---

#### In project root folder run the following command to install dependencies
```
$ npm install
```
#### Then run the next two commands in the project root folder in seperate or tabbed terminals
```
$ npm run compile:sass
```
#### The only caveat to this is you only need to run the compile:sass command if you plan on making changes to the code
