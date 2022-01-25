# termux-x11-audio
it enables sound in proot distro
## Steps In installition
``` 
git clone https://github.com/aruncs31s/termux-x11-audio
cd termux-x11-audio
bash termux-setup.sh
```
```
now log in to proot-distro add the following line to
~/.vnc/xstartup
export PULSE_SERVER=127.0.0.1
```
```
or run this command inside proot-distro
#if you are using bash
echo "export PULSE_SERVER=127.0.0.1" >> ~/.bashrc
#if your using zsh 
echo "export PULSE_SERVER=127.0.0.1" >> ~/.zshrc
```
