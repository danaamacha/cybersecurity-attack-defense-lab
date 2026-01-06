# Recon – Nmap Scan

## Target
- Target name: DVWA (lab)
- IP address: TBD
- Date: TBD

## Commands Used
```bash
nmap -sC -sV -oN nmap-initial.txt <TARGET_IP>
nmap -p- -T4 -oN nmap-allports.txt <TARGET_IP>
