# AWS Security Architecture

This project report presents a proof-of-concept AWS architecture for WinLocal Giveaways, a small online business seeking improved availability, scalability, and security after a ransomware incident.

## Architecture covered

- A virtual private cloud spanning two Availability Zones, with public and private subnets.
- An Application Load Balancer and EC2 web servers, with Auto Scaling.
- A private RDS database and a bastion host for administrative access.
- Backup planning, plus AWS WAF and GuardDuty considerations for a production design.

The report distinguishes proof-of-concept implementation choices from production recommendations.

## Report

See [security architecture project.docx](security%20architecture%20project.docx) for the design, implementation discussion, and recommendations.
