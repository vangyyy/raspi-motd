## MOTD script for Raspberry Pi

<img width="100%" src="https://imgur.com/LJQpeJu.png"/>

## Installation

Copy script into `/etc/profile.d/` directory using **Wget**:

```
sudo wget -q -O /etc/profile.d/motd.sh https://raw.githubusercontent.com/vangyyy/raspi-motd/master/motd.sh
sudo chmod +x /etc/profile.d/motd.sh
```

or with **cURL**:

```
sudo curl -s -o /etc/profile.d/motd.sh https://raw.githubusercontent.com/vangyyy/raspi-motd/master/motd.sh
sudo chmod +x /etc/profile.d/motd.sh
```

Optionally to remove the default MOTD run:
```
sudo truncate -s 0 /etc/motd
```
