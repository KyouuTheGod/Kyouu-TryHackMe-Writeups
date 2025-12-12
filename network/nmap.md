Nmap Enumeration Notes

Basic Scans
- Fast scan:
  nmap -F target

- Full TCP scan:
  nmap -p- -T4 target

Service Enumeration
- Default scripts & version detection:
  nmap -sC -sV target

Common Use Cases
- Identify open ports
- Detect running services
- Discover misconfigurations

Notes
Enumeration is the most important phase in penetration testing.
Missing information here often leads to failed exploitation.
