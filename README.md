CentOS Linux release 7.9.2009 (Core)
Visual Studio Code 1.58.2

sudo yum install epel-release -y
sudo yum install snapd -y
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
And then, install Visual Studio Code through Snap:

sudo snap install code --classic
