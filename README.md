# MSI Laptop Ubuntu Setup Instructions

Instructions for setting up my MSI laptop and configs

## Installing Ubuntu

Check this link [here](https://medium.com/@gentra/how-to-install-ubuntu-16-04-on-msi-ge62-6qc-ae4f30f50465). Check out comments, add `apci=off` and `nouveau.modeset=0` on same line as quiet splash and just after quiet splash.

## Installing NVIDIA Driver

Check this link out [here](https://askubuntu.com/questions/760934/graphics-issues-after-while-installing-ubuntu-16-04-16-10-with-nvidia-graphics).

## Upgrade system

`sudo apt-get upgrade && sudo apt-get update`

## Other installations

### Tmux

```bash
sudo apt-get install tmux
cp configs/.tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf
```

### Sublime Text

Follow [this](http://tipsonubuntu.com/2017/05/30/install-sublime-text-3-ubuntu-16-04-official-way/#prettyPhoto) line to install Sublime as package and avoid bz2 package dealing.

