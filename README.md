# Home Gateway Security & Firmware Integrity Audit
By: Divyansh Tiwari

Inspired by my Cisco Networking Academy Introduction to Cybersecurity credential, I conducted a live environment audit of a residential JioFiber Gateway infrastructure (Gateway IP: 192.168.29.1) to observe vulnerability configurations and default credential structures.

## 🛠️ Audit Findings & System Baseline
* **Gateway Hardware Environment:** Residential Fiber-to-the-Home (FTTH) Access Point.
* **Firmware Baseline:** Active running firmware isolated as version `SRCMTF1_JCOW414_R2.59`.
* **Device Identity:** Hardware Serial Number logged as `RSTOTKIPE018383`.

## 🔒 Security Threat Vector Analysis
1. **Default Credential Vulnerability:** The audit confirmed that the device was accessible using standard regional factory-default administrative credentials. In a live threat landscape, this represents a significant vector for unauthorized local privilege escalation.
2. **Forced Mitigations Observed:** Upon entry, the firmware successfully executed an automated compliance checkpoint—interrupted by a mandatory prompt to rotate the administrative passphrases. This enforces proper operational security hygiene.

## 💡 Practical Takeaways
This project allowed me to map theoretical concepts from my Cisco course—such as access control frameworks, threat surfaces, and firmware vulnerability management—directly onto physical networking hardware. It demonstrates a proactive approach to auditing and securing network edge devices.
