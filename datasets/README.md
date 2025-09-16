# CZ-EDU-AI Datasets

This folder will contain all datasets created under the **CZ-EDU-AI** project.  
The datasets will be published under **CC BY 4.0** license and will follow the unified JSON schema defined in the root of this repository.

## Planned Structure
- `school_practice/` – tasks and texts for civic education, ICT, media literacy  
- `sme_scenarios/` – SME work scenarios (customer emails, safety checklists)  
- `ict_basics/` – definitions, terms, multiple-choice questions  

Each dataset entry will include:
- `text` – source paragraph or question
- `question` – optional, for QA/MCQ tasks
- `answer` – correct answer(s) or expected output
- `license` – explicit license for this entry
- `source` – origin or reference

## Roadmap
- **M1 (Weeks 1–6):** data standard & schema design, repository setup, 30 % curated items  
- **M2 (Weeks 7–12):** full v1.0 release (≥ 10 000 items) + SCORM/HTML exports  
- **M3 (Weeks 13–18):** pilot with ≥ 10 schools/SMEs, feedback integration → v1.1  
- **M4 (Weeks 19–24):** English translation of selected subsets, community call, PR package  

Datasets will be continuously versioned and validated via GitHub Actions.  
Any contributions must pass CI schema validation before merging.

---

**License:** CC BY 4.0 (see [LICENSE-DATA.md](../LICENSE-DATA.md))  
**DOI:** Will be added after first Zenodo release (M2)
