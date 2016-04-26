setup.git
=========
Clone and run this on a new EC2 instance running
Ubuntu Server 14.04 LTS (HVM), SSD Volume Type - ami-fce3c696
to configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
apt-get update
sudo apt-get install -y git-core
git clone https://github.com/bhammon/setup.git
./setup/setup.sh   
```

See also http://github.com/startup-class/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.





