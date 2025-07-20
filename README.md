# AutoSecScan   
**Car diagnostics + OBD-II security case**

This project presents a real-world diagnostic session on a LADA Priora 2171 (2012) using the ELM327 Bluetooth adapter and OBD Auto Doctor software.

It also includes a basic analysis of the cybersecurity risks associated with OBD-II interfaces.

---

##  Vehicle Info

- **Model**: LADA Priora 2171  
- **Year**: 2012  
- **Adapter**: ELM327 v1.5 (Bluetooth)  
- **Software**: OBD Auto Doctor Premium  
- **Protocol**: ISO 14230-4 (KWP FAST)

---

##  Diagnostic Errors (Before Fix)

- `P0504`: Brake switch A/B signal mismatch  
- `P0441`: Incorrect EVAP purge flow  
- Freeze Frame captured:
  - Coolant temp: 81°C  
  - RPM: 970  
  - Speed: 6 km/h  
  - Throttle: 12.9%

##  After Troubleshooting

- All fault codes cleared  
- Monitors completed successfully  
- System verified via screenshots

---

##  Cybersecurity Focus

> OBD-II interfaces — especially wireless adapters — can be vulnerable.

**Risks Identified:**
- No encryption/authentication in some devices  
- Remote ECU access  
- CAN-bus injection or data manipulation  
- Unauthenticated DTC clearing

**Mitigation Tips:**
- Use adapters with security (PIN-code or encrypted)  
- Avoid leaving OBD devices plugged in permanently  
- Consider IDS solutions for CAN-bus monitoring (advanced users)

---

##  Files in this project

- [📄 Full Report, Before/After Screenshots(DOCX)](AutoSecScan.docx)
- [Diagnostic Logs](logs)
---

##  Author

**Vlassov Vladislav**  
Student & Cybersecurity Enthusiast  
