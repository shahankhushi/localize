# localize

> **Multi-market campaign adaptation engine: transcreation rules, Right-to-Left (RTL) creative specifications, local platform weighting, and regional shopping seasonality calendars.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![RTL Ready](https://img.shields.io/badge/RTL-Arabic%20%26%20Urdu-green.svg)](#)
[![Global Growth](https://img.shields.io/badge/Markets-GCC%20%7C%20South%20Asia%20%7C%20DACH-purple.svg)](#)

---

## The Problem: Translation $\ne$ Transcreation

Silicon Valley marketing repos assume every buyer is an English-speaking US SaaS founder with a corporate credit card. 

When you scale campaigns internationally (MENA, South Asia, LATAM, DACH), literal word-for-word translation fails:
- **Visual Composition Fails:** Arabic and Urdu eye-tracking moves Right-to-Left. Putting the "Before" picture on the left makes it look like the "After" result!
- **Channel Weight Shifts:** In the Gulf and South Asia, WhatsApp and Snapchat dominate email and LinkedIn.
- **Payment Method Mismatch:** Demanding credit card checkout in markets where 70% of e-commerce is Cash on Delivery (COD) kills conversion rate.

`localize` provides the architectural rules, typography specs, and seasonality calendars needed to adapt campaigns across global markets.

---

## Directory Structure

```
localize/
├── configs/
│   ├── markets.json             # Channel weights, payment preferences, culture rules
│   ├── rtl_creative_specs.md    # Mirrored eye-tracking, typography, safe zones
│   └── seasonality_calendars.json # Ramadan, White Friday, 11.11, Diwali
└── README.md
```

---

## Covered Regional Frameworks

1. **GCC / Middle East (UAE & Saudi Arabia):**
   - RTL video flipping guidelines and Arabic typography standards.
   - Ramadan & White Friday flighting schedules.
   - COD, Tabby, and Apple Pay payment messaging.
2. **South Asia (Pakistan & India):**
   - Hinglish / Roman Urdu conversational hooks.
   - Low-bandwidth video compression specs.
   - WhatsApp-first funnel architectures.
3. **DACH (Germany, Austria, Switzerland):**
   - Impressum and GDPR regulatory compliance standards.
   - Direct-response vs technical proof tone adjustment.

---

## Contributing New Markets

This project expands through global contributions. To add your country or region, submit a PR adding your market schema to `configs/markets.json`.

---

## License
MIT © [Haider (@darimamhaider)](https://github.com/darimamhaider)
