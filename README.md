# **VIU-DSC-App**
### First things first:
Until the mobile version is done, the full version of the App will pull the front-end
from here. If you want to work on the Front-end, please submit a pull request and work
on the development branch only please, as Lenz will pull only from the master.

### Install nodejs and npm on your system

#### Arch Base

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
npm install
```
#### This should just install node-sass, it is also recommended to install live-server onto your machine.
```
npm install live-server
```
#### Then run the next two commands in the project root folder in seperate or tabbed terminals
```
npm run compile:sass
```
```
live-server
```
#### The only caveat to this is you only need to run the compile:sass command if you plan on making changes to the code

