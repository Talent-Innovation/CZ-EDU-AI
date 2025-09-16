# CZ-EDU-AI – Otevřené datasety pro vzdělávání a testování AI (CZ/EN)
**CZ:** Otevřený projekt dodávající tři datasety (CZ/EN, ≥10 000 položek) pro výuku AI a testování modelů.  
**EN:** Open project delivering three datasets (CZ/EN, ≥10,000 items) for AI education and model evaluation.

---

## Cíl projektu / Project Goal
**CZ:** Zrychlit a zjednodušit práci učitelů a SME díky otevřeným, standardizovaným datasetům připraveným pro okamžité použití v LMS (SCORM/HTML) a pro férové porovnávání LLM (benchmark úlohy + Jupyter notebooky).  
**EN:** Speed up and simplify the work of teachers and SMEs through open, standardised datasets ready for immediate LMS deployment (SCORM/HTML) and fair LLM benchmarking (benchmark tasks + Jupyter notebooks).

---

## Co dodáme / Deliverables
**CZ:**
- 3 datasety (CZ/EN, celkem ≥10 000 položek):  
  • „Škola v praxi“ (občanská nauka, ICT, mediální výchova)  
  • „SME scénáře“ (zákaznické e-maily, checklisty)  
  • „ICT základy“ (definice, pojmy, testové úlohy)  
- **Standardizace:** jednotné JSON schéma + CI validace  
- **Soukromí:** automatická PII detekce + manuální kontrola vzorků  
- **Okamžité použití:** SCORM/HTML exporty pro LMS (Moodle, MS Teams)  
- **Reprodukovatelnost:** benchmark úlohy (QA/MCQ/RC) + 3 Jupyter notebooky  

**EN:**
- 3 datasets (CZ/EN, total ≥10,000 items):  
  • "School in Practice" (civics, ICT, media literacy)  
  • "SME Scenarios" (customer emails, checklists)  
  • "ICT Basics" (definitions, terms, test exercises)  
- **Standardisation:** unified JSON schema + CI validation  
- **Privacy:** automated PII detection + manual sample review  
- **Immediate use:** SCORM/HTML exports for LMS (Moodle, MS Teams)  
- **Reproducibility:** benchmark tasks (QA/MCQ/RC) + 3 Jupyter notebooks  

---

## Plán (M1–M4) / Roadmap
**CZ:**
- **M1 (Weeks 1–6):** datový standard, repo, 30 % dat, CI, PII skripty  
- **M2 (Weeks 7–12):** v1.0 ≥10 000 položek, benchmarky, SCORM/HTML, Zenodo DOI, 3 notebooky  
- **M3 (Weeks 13–18):** pilot ≥10 škol/SME, feedback, release v1.1  
- **M4 (Weeks 19–24):** EN mutace, community call, PR (článek, webinář)  

**EN:**
- **M1 (Weeks 1–6):** data standard, repo, 30% of data, CI, PII scripts  
- **M2 (Weeks 7–12):** v1.0 ≥10,000 items, benchmarks, SCORM/HTML, Zenodo DOI, 3 notebooks  
- **M3 (Weeks 13–18):** pilot ≥10 schools/SMEs, feedback, release v1.1  
- **M4 (Weeks 19–24):** EN version, community call, PR (article, webinar)  

> **Datasets will be published here under CC BY 4.0 starting M2.**

---

## Odkazy / Links
**CZ:**  
- Main Application (PDF): přidáme odkaz po zveřejnění  
- Annex (PDF): přidáme odkaz po zveřejnění  
- NGI Zero Commons Fund (call): volitelný odkaz  
- Zenodo DOI: doplníme v M2  

**EN:**  
- Main Application (PDF): link will be added when available  
- Annex (PDF): link will be added when available  
- NGI Zero Commons Fund (call): optional link  
- Zenodo DOI: TBA in M2  

---

## Jak přispět / How to Contribute
**CZ:**  
Viz `CONTRIBUTING.md` (CZ/EN) – jak poslat PR, jak projde CI validací.  
Issues: návrhy témat, bugy v datech, žádosti o rozšíření.  
Po v1.0 proběhne community call – termín oznámíme v Issues.  

**EN:**  
See `CONTRIBUTING.md` (CZ/EN) – how to submit PR, how CI validation works.  
Issues: topic proposals, data bugs, requests for extensions.  
After v1.0 a community call will be held – date will be announced in Issues.  

---

## Licence / Licensing
**CZ:**  
- Kód: MIT (viz LICENSE)  
- Data: CC BY 4.0 (viz LICENSE-DATA.md)  
Při citování datasetu použijte DOI (bude doplněno v M2).  

**EN:**  
- Code: MIT (see LICENSE)  
- Data: CC BY 4.0 (see LICENSE-DATA.md)  
When citing the dataset, please use the DOI (to be added in M2).  

---

## Soukromí & bezpečnost / Privacy & Security
**CZ:**  
- PII: automatická NER + regex detekce, manuální vzorkování 5–10 %  
- Rollback plán: v případě nálezu citlivých údajů vracíme změny verzí v Gitu  
- Bezpečnostní kontakt: security@t-i.cz  

**EN:**  
- PII: automated NER + regex detection, 5–10% manual sampling  
- Rollback plan: if sensitive data are found, revert via Git version history  
- Security contact: security@t-i.cz  

---

## Tým / Team
**CZ:**  
- Talent Innovation s.r.o. – project lead, curation, documentation, pilot coordination  
- Externí experti – ETL/PII, CI, benchmarky  
- Piloti – ≥10 škol/SME (síť partnerů)  

**EN:**  
- Talent Innovation s.r.o. – project lead, curation, documentation, pilot coordination  
- External experts – ETL/PII, CI, benchmarks  
- Pilots – ≥10 schools/SMEs (partner network)  

---

## 🇪🇺 European Dimension
**CZ:** Multilingual-ready (CZ/SK/PL/DE) + kompatibilita s ELG / ELLIS / CLARIN.  
**EN:** Multilingual-ready (CZ/SK/PL/DE) + compatibility with ELG / ELLIS / CLARIN.  
Supports trustworthy & reproducible AI evaluation aligned with EU best practices.
