# Validation-Risk-Compliance-Week14

## Security Validation Risk Register & Compliance Dossier
**Week 14 — Validation Engineering Assignment**

---

### Target Application
- **URL:** https://demo.owasp-juice.shop
- **Scan Tool:** OWASP ZAP by Checkmarx v2.17.0
- **Scan Date:** Wednesday, 20 May 2026

---

### Repository Structure

```
Validation-Risk-Compliance-Week14/
├── SecurityReports/
│   └── ZAP-Scan-Report.html          ← Full OWASP ZAP HTML scan report
│
├── RiskRegisters/
│   └── Risk_Register.csv             ← Structured risk register (7 risks, VR-01 to VR-07)
│
├── ComplianceDossier/
│   └── Final_Compliance_Dossier.docx ← Complete audit-ready compliance document
│
└── Screenshots/              ← Screenshots from scanning sessions
```

---

### Alert Summary

| Risk Level    | Count |
|---------------|-------|
| High          | 0     |
| Medium        | 2     |
| Low           | 3     |
| Informational | 2     |
| **Total**     | **7** |

---

### Vulnerabilities Found

| Risk ID | Vulnerability                        | Risk Level    |
|---------|--------------------------------------|---------------|
| VR-01   | CSP Header Not Set                   | Critical      |
| VR-02   | Cross-Domain CORS Misconfiguration   | Critical      |
| VR-03   | Server Version Information Leakage   | Moderate      |
| VR-04   | HSTS Header Not Set                  | High          |
| VR-05   | Timestamp Disclosure (Unix)          | Low           |
| VR-06   | Cache-Control Misconfiguration       | Low           |
| VR-07   | Modern SPA Framework Detected        | Informational |

---

### Tools Used
- OWASP ZAP v2.17.0 (Checkmarx)
- MS Word (Final Compliance Dossier)
- GitHub (repository submission)

---

> **Note:** All testing was conducted on a demo/lab system (OWASP Juice Shop). No real production systems were tested.

---

**Prepared by:** Validation Engineering Team  
**Course:** Software Validation — Week 14  
**Classification:** For Educational/Audit Review Purposes Only
