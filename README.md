    ╔═════════════════════════════════════════════════════════════════════════════╗
    ║   ███████╗ ██████╗ ██████╗ ████████╗██╗ ██████╗  █████╗ ████████╗███████╗   ║
    ║   ██╔════╝██╔═══██╗██╔══██╗╚══██╔══╝██║██╔════╝ ██╔══██╗╚══██╔══╝██╔════╝   ║
    ║   █████╗  ██║   ██║██████╔╝   ██║   ██║██║  ███╗███████║   ██║   █████╗     ║
    ║   ██╔══╝  ██║   ██║██╔══██╗   ██║   ██║██║   ██║██╔══██║   ██║   ██╔══╝     ║
    ║   ██║     ╚██████╔╝██║  ██║   ██║   ██║╚██████╔╝██║  ██║   ██║   ███████╗   ║
    ║   ╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝   ║
    ║                                                                             ║
    ║      ██████╗ ███████╗██╗     ███████╗███████╗███╗   ██╗                     ║
    ║      ██╔══██╗██╔════╝██║     ██╔════╝██╔════╝████╗  ██║                     ║
    ║      ██████╔╝█████╗  ██║     ███████╗█████╗  ██╔██╗ ██║                     ║
    ║      ██╔══██╗██╔══╝  ██║     ╚════██║██╔══╝  ██║╚██╗██║                     ║
    ║      ██████╔╝███████╗███████╗███████║███████╗██║ ╚████║                     ║
    ║      ╚═════╝ ╚══════╝╚══════╝╚══════╝╚══════╝╚═╝  ╚═══╝                     ║
    ║                                                                             ║
    ║      ██╗     ███████╗ █████╗ ██╗  ██╗                                       ║
    ║      ██║     ██╔════╝██╔══██╗██║ ██╔╝                                       ║
    ║      ██║     █████╗  ███████║█████╔╝                                        ║
    ║      ██║     ██╔══╝  ██╔══██║██╔═██╗                                        ║
    ║      ███████╗███████╗██║  ██║██║  ██╗                                       ║
    ║      ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝                                       ║
    ║                                                                             ║
    ║                    Configuration Leak Tracker                               ║
    ╚═════════════════════════════════════════════════════════════════════════════╝

#Fork Info

Forked from: https://github.com/arsolutioner/fortigate-belsen-leak - Thank you for posting the dump!
I have iterated on it by matching the ip addresses to Countries as well as ASN.
Anyone willing to help build a map?
Check to see if your ip is listed and take action immediately.


This repository contains informaion about the Fortigate firewall vulnerability (CVE-2022-40684) and affected IPs that were publicly disclosed by the Belsen Group. This information is being shared for security research and defensive purposes to help organizations identify if they were impacted.

## Background

In 2022, Fortinet disclosed a critical authentication bypass vulnerability (CVE-2022-40684) affecting FortiOS, FortiProxy, and FortiSwitchManager. In January 2025, configurations from approximately 15,000 affected devices were publicly released by the Belsen Group.

## Purpose

This repository serves as a resource for:
- Security researchers studying the impact of CVE-2022-40684
- Organizations to check if they were affected
- Raising awareness about the importance of timely security patches

## Contents

- `affected_ips.txt`: List of IP addresses identified as potentially affected
- `REFERENCES.md`: Additional resources and references about the vulnerability
- `affected_ips_country_code_asn.csv`: The list modified to match ASN and Country in CSV format.
- `affected_ips_country_code_asn.xlsx`: The list modified to match ASN and Country in Excel format, with pivot tables.

## Disclaimer

This information is provided for defensive security research purposes only. The data has been publicly disclosed and is being shared to help organizations assess their exposure and take necessary remediation steps.

## References

- [Fortinet Advisory](https://www.fortinet.com/blog/psirt-blogs/update-regarding-cve-2022-40684)
- CVE-2022-40684
- Source: https://github.com/arsolutioner/fortigate-belsen-leak

## Contact

- https://www.linkedin.com/in/randallmaharaj/
