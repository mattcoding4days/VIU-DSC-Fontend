# **VIU-DSC-App Devel Branch**
### First things first, install npm on your machine

#### Arch Base
sudo pacman -S npm

#### Debian Base
sudo apt install npm

---

#### In project root folder run the following command to install dependencies

npm install

#### This should just install node-sass, it is also recommended to install live-server onto your machine.

npm install live-server

#### Then run the next two commands in the project root folder in seperate or tabbed terminals

npm run compile:sass

live-server

#### The only caveat to this is you only need to run the compile:sass command if you plan on making changes to the code

