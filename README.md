# Installfile for debian-based machines v1.4
bash <(curl -s inst.gcal.ch)
(obvsly you need curl to be installed)

# does:
- changing default mirror (raspbian/debian)
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
- custom wsl things
