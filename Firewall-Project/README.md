# OPNsense Firewall Project

This project documents a network security assessment comparing pfSense, OPNsense and IPFire, with a focus on configuring and testing OPNsense.

## My contribution

My section covers the OPNsense firewall setup and testing, including:

- Configuring firewall rules to restrict access to the OPNsense web interface (HTTPS, port 443) and SSH (port 22).
- Limiting administrative access to the approved admin/client virtual machines and blocking other LAN hosts.
- Reviewing firewall logs to confirm denied connection attempts.
- Testing brute-force protections and observing SSH disconnections after repeated failed authentication attempts.
- Assessing the limitations of GUI rate-limiting and the effectiveness of the implemented controls.

## Report

The full group assessment report can be added to this folder as `Firewall Project.pdf`.
