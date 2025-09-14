A Report on common network security threats focuses on three interconnected types: Denial-of-Service (DoS), Man-in-the-Middle (MITM), and Spoofing. Each threatens different pillars of the CIA triad—confidentiality, integrity, and availability—and are often used together in sophisticated cyberattacks.

Foundational Concepts
CIA Triad: Confidentiality (privacy), Integrity (accuracy), and Availability (accessibility) are the core principles that cyber threats target.

Threats and Vulnerabilities: Cyber threats exploit vulnerabilities to compromise systems. Effective security requires active risk management and mitigation.

Threat Overviews
Denial-of-Service (DoS)/Distributed DoS (DDoS): Aims to disrupt service availability by overwhelming resources. DDoS attacks use botnets to scale the assault, with notable vectors including volumetric floods, SYN flooding, and application-layer attacks like Slowloris. Major incidents (e.g., Dyn 2016, GitHub 2018) have shown the havoc these attacks can cause.

Man-in-the-Middle (MITM): Attackers intercept and possibly alter communications (often via SSL stripping, ARP/DNS spoofing, or Wi-Fi eavesdropping), targeting data confidentiality and integrity. The consequences include credential theft, financial fraud, and unauthorized account access.

Spoofing: Involves impersonation (IP, DNS, or email spoofing) to trick victims or enable other attacks. Spoofing underpins more advanced attacks like DDoS and MITM by allowing attackers to masquerade as trusted entities and redirect traffic or communications.

Defense Strategies
Technical Controls: Harden network infrastructure, deploy firewalls and intrusion prevention systems, implement encryption (VPN, HTTPS/HSTS), and use authentication controls (MFA, strong passwords).

Cloud-Based Solutions: DDoS protection and BGP Anycast routing distribute and filter attack traffic before it disrupts services.

Human-Centric Measures: Regular employee security awareness training, zero-trust frameworks, and vigilant checking of URLs, email headers, and public Wi-Fi safety are essential to minimize successful attacks enabled by human error.

Conclusion
Modern network threats are complex and interconnected, requiring multi-layered technical and human-focused defenses. Relying on single countermeasures is ineffective—organizations must adopt holistic, adaptive security strategies to manage risk and maintain resilience
