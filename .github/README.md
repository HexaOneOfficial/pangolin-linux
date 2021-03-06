# Pangolin-linux
Pangolin Desktop running on Linux systems.

## Requirements

### arch

- Install flutter and matchbox-window-manager unzip
```
yay -S flutter matchbox-window-manager unzip
```
### Debian/Ubuntu

- install git and matchbox-window-manager unzip
```
sudo apt install git matchbox-window-manager unzip
```
- Install flutter [`Snap`](https://snapcraft.io/flutter)
```
sudo snap install flutter --classic
```

### Fedora

- Install flutter [`Snap`](https://snapcraft.io/flutter)
```
sudo dnf install snapd
```

```
sudo ln -s /var/lib/snapd/snap /snap
```

```
sudo snap install flutter --classic
```

## Installation

If you're using something other than Linux Mint you will get a nosnap error but this won't effect anything.
```bash
git clone https://github.com/hexa-one/pangolin-linux.git
cd pangolin-linux && chmod +x install.sh && sudo ./install.sh
```
- now restart and login with pangolin
