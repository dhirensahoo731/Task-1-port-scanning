# Task 1: Scan Your Local Network for Open Ports

## Objective
To discover open ports on devices in a local network and understand network exposure.

## Tools Used
- Nmap
- Windows 11

## Commands Used

ipconfig

nmap -sn 10.187.139.0/24

nmap 10.187.139.48

## Results

Active Hosts:
- 10.187.139.165
- 10.187.139.48

Open Ports:
- 135/tcp (msrpc)
- 139/tcp (netbios-ssn)
- 445/tcp (microsoft-ds)

## Security Risks
- Open file-sharing services may expose resources.
- Unnecessary services should be disabled.
- Firewall protection should be enabled.

## Conclusion
Nmap successfully identified active hosts and open ports on the local network. This task helped understand network reconnaissance and service exposure.
