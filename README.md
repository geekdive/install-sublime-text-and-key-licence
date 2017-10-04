# install-sublime-text-and-key-licence
Install Sublime on Linux Ubuntu 16.04 LTS with Key Licence

## Install Sublime Text on Ubuntu
First download the security key for the text editor’s repository. This will ensure packages downloaded from the repo are authenticated, etc:<br />
<b>wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -</b> <br />

## If you want to run the latest development builds of Sublime Text you can: just run this command instead of the one above:
<b>echo "deb https://download.sublimetext.com/ apt/dev/" | sudo tee /etc/apt/sources.list.d/sublime-text.list</b> <br /><br />
