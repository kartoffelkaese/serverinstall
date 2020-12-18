# Installfile for debian-based machines v1.1
apt update && apt install curl && curl -O https://raw.githubusercontent.com/kartoffelkaese/serverinstall/main/install && chmod +x install && ./install

# does:
- changing default mirror
- apt update && upgrade && install things
- tzdata && locales
- dump motd
- adduser martin w/o pw
- new root pw
- new hostname
- sshkey for martin
- sshd: key only login, port 222
- profilebanner
- aliases
- bash colors (green user/purple root)
- no-pw sudo for apt for martin
- warning check sshd manually
- test logins (user/root)
- remove default ubuntu/pi users
