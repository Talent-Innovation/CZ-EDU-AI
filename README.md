# CZ-EDU-AI – Otevřené datasety pro vzdělávání a testování AI (CZ/EN)

> **CZ** • Otevřený projekt dodávající 3 české datasety (CZ/EN, ≥10 000 položek) pro výuku AI a evaluaci modelů.
> **EN** • Open project delivering 3 Czech datasets (CZ/EN, ≥10,000 items) for AI education and model evaluation.

---

## 🧭 Cíl projektu / Project goal

**CZ:** Zrychlit a zjednodušit práci učitelů a SME díky otevřeným, standardizovaným datasetům připraveným pro okamžité použití v LMS (SCORM/HTML) a pro férové porovnávání LLM (benchmark úlohy + Jupyter notebooky).

**EN:** Enable teachers and SMEs to work faster with open, standardized datasets ready for immediate LMS use (SCORM/HTML) and fair LLM comparison (benchmark tasks + Jupyter notebooks).

---

## 📦 Co dodáme / Deliverables

- **3 datasety (CZ/EN, celkem ≥10 000 položek)**:
  - „Škola v praxi“ (civics, ICT, media literacy)
  - „SME scénáře“ (zákaznické e-maily, checklisty)
  - „ICT základy“ (definice, pojmy, testové úlohy)
- **Standardizace**: jednotné **JSON** schéma + **CI** validace.
- **Soukromí**: automatická **PII** detekce + manuální kontrola vzorků.
- **Okamžité použití**: **SCORM/HTML** exporty pro LMS (Moodle, MS Teams).
- **Reprodukovatelnost**: benchmark úlohy (QA/MCQ/RC) + **3 Jupyter notebooky**.

---

## 🗺️ Plán (M1–M4) / Roadmap

- **M1 (Weeks 1–6)**: datový standard, repo, 30 % dat, CI, PII skripty  
- **M2 (Weeks 7–12)**: v1.0 ≥10 000 položek, benchmarky, SCORM/HTML, Zenodo DOI, 3 notebooky  
- **M3 (Weeks 13–18)**: pilot ≥10 škol/SME, feedback, release v1.1  
- **M4 (Weeks 19–24)**: EN mutace, community call, PR (článek, webinář)

> **Datasets will be published here under CC BY 4.0 starting M2.**

---

## 🔗 Odkazy / Links

- **Main Application (PDF):** _add link when available_  
- **Annex (PDF):** _add link when available_  
- **NGI Zero Commons Fund (call):** _optional link_  
- **Zenodo DOI:** _TBA in M2_

---

## 🛠️ Jak přispět / How to contribute

- Viz **CONTRIBUTING.md** (CZ/EN) – jak poslat PR, jak projde CI validací.
- Issues: návrhy témat, bugy v datech, žádosti o rozšíření.
- Po v1.0 proběhne **community call** – termín oznámíme v Issues.

---

## ⚖️ Licence / Licensing

- **Kód:** MIT (viz `LICENSE`)  
- **Data:** CC BY 4.0 (viz `LICENSE-DATA.md`)  
- Při citování datasetu použijte DOI (bude doplněno v M2).

---

## 🛡️ Soukromí & bezpečnost / Privacy & Security

- PII: automatická NER + regex detekce, manuální vzorkování 5–10 %.  
- Rollback plán: v případě nálezu citlivých údajů vracíme změny verzí v Gitu.  
- Bezpečnostní kontakt: **security@t-i.cz** (příklad – upravte podle reality)

---

## 👥 Tým / Team

- **Talent Innovation s.r.o.** – project lead, curation, documentation, pilot coordination  
- Externí experti – ETL/PII, CI, benchmarky  
- Piloti – ≥10 škol/SME (síť partnerů)

---

## 🇪🇺 European dimension

- Multilingual-ready (CZ/SK/PL/DE) + kompatibilita s ELG / ELLIS / CLARIN.
- Supports trustworthy & reproducible AI evaluation aligned with EU best practices.

