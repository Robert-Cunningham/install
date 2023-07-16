# install
Quickly install standard utilities
```
sudo apt update
sudo apt install curl htop nload ffmpeg tmux vim

curl -fsSL https://tailscale.com/install.sh | sh

# get updated link from here: https://docs.conda.io/en/latest/miniconda.html#linux-installers
wget https://repo.anaconda.com/miniconda/Miniconda3-py311_23.5.2-0-Linux-x86_64.sh
chmod +x Miniconda3-py311_23.5.2-0-Linux-x86_64.sh
```
# Interactive
```
tailscale login
./Miniconda3-py311_23.5.2-0-Linux-x86_64.sh
```

# After
```
sudo tailscale up --ssh
```
