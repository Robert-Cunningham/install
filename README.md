# install
Quickly install standard utilities
```
sudo apt update
sudo apt upgrade
sudo apt install curl htop btop nload ffmpeg tmux vim git git-lfs zsh fd-find ripgrep ncdu

curl -fsSL https://tailscale.com/install.sh | sh


# get updated link from here: https://docs.conda.io/en/latest/miniconda.html#linux-installers
wget https://repo.anaconda.com/miniconda/Miniconda3-py311_23.5.2-0-Linux-x86_64.sh
chmod +x Miniconda3-py311_23.5.2-0-Linux-x86_64.sh

curl -fsSL https://get.docker.com -o install-docker.sh
sudo sh install-docker.sh

curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash - &&\
sudo apt-get install -y nodejs

```
# Interactive
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
tailscale login
./Miniconda3-py311_23.5.2-0-Linux-x86_64.sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

```

# After
```
sudo tailscale up --ssh
```

# Add a non-root user
sudo adduser robert
sudo usermod -aG sudo robert
