# Installfile for debian-based machines v1.5
bash <(curl -s inst.gcal.ch)
(obvsly you need curl to be installed)

# does:
- mirrors for apt w/ choose option
- apt update && upgrade && install things
- tzdata && locales
- dump motd
- test for user martin (adduser martin w/o pw, sshkey)
- new root pw
- new hostname
- sshd: key only login, port 222, security
- profilebanner
- aliases
- bash colors (green user/purple root)
- no-pw sudo for apt for martin
- warning check sshd manually
- test logins (user/root)
- remove default ubuntu/pi users
- custom wsl things
