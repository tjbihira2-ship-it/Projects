# Projects
# Open Source Firewall Evaluation (Network Security, TU Dublin)

Group project comparing pfSense, OPNsense and IPFire in a VirtualBox lab
with an attacker VM. **My part: OPNsense.**

## What I did
- Admin-only rules for GUI/SSH; block all other LAN hosts
- Verified with attacker-VM tests and firewall logs
- Tested brute force on GUI and SSH; researched rate-limit options

## Results
- Rules blocked all unauthorised access and logged denials
- No built-in GUI lockout; recommended VPN-only management access
- SSH disconnected the attacker after ~6 failed attempts

## Tools
OPNsense, VirtualBox, Linux attacker VM, SSH

## Evidence
See /OPNsense-Report.pdf (my section) with rule and log screenshots.

## Team
Ken Sweeney (pfSense), Sean Wogan (IPFire), Tevin Bihirabagabo (OPNsense)
