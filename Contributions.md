
# Team Contributions — Group 3

**Project:** Heart Disease Prediction Using Machine Learning  
**Course:** BIS3012 · Hochschule Pforzheim · Prof. Dr. Dustin van der Haar · 2026  
**Team:** Karim · Kushul · Tarik · Max

---

## How We Organised the Work

We met once a week throughout the semester. Each meeting we went through what was done, discussed any problems, and assigned tasks for the following week. Everyone had a clear role from the start. Once each person finished their part, everything was collected and uploaded from one laptop — Karim's — to keep the repository clean and avoid duplicates or merge conflicts from multiple people pushing at the same time.

---

## GitHub Issues

We ran into two problems with GitHub that are worth explaining since they affected the commit history.

First, when the GitHub Classroom repository was created, none of us could access it. We tried multiple times over several days but kept getting access errors. Rather than wait, we created our own repository at `github.com/saffadek/heart-disease-classification` and worked from there for the entire project.

Second, when we eventually got into the classroom organisation, we still could not push files — uploads were disabled for our accounts. We only managed to get the project into the classroom repo the night before the presentation by forking it directly. Prof. van der Haar was kept informed by email throughout.

Because of all this, and because we were uploading from one machine on purpose, the commit history only shows one account. It does not reflect how the work was actually split.

---

## What Each Person Did

**Karim — Data Engineer & Project Lead**

Karim handled the technical implementation and repository management. He built the data pipeline, implemented the models, and managed all uploads. He also built the interactive website and wrote the technical sections of the report.

- Jupyter notebook — full pipeline from data loading to evaluation
- `src/preprocess.py`, `src/train.py`, `src/evaluate.py`
- GridSearchCV tuning for all 3 models with class_weight='balanced'
- Interactive website — risk calculator, model switcher, what-if simulator
- Report sections 1–4
- Lab 12 deployment notebook
- Repository setup, README, and all uploads

**Kushul — Code Review & QA**

Kushul reviewed and tested all technical outputs each week. He went through the notebook, checked the results, and flagged anything that needed fixing. He also contributed to the preprocessing decisions and helped structure the methodology section of the report.

- Full notebook review and reproducibility testing
- Verification of all evaluation metrics and confusion matrix
- Encoding and stratified split validation
- Contribution to preprocessing pipeline design
- Technical review of report sections 1–2
- Helped prepare and upload project files

**Tarik — Presentation & Communication**

Tarik was responsible for the presentation and how the project was communicated externally. He designed the slide structure, prepared the website for live demo use, and handled team coordination throughout the semester. He also contributed to the repository by reviewing and uploading presentation materials.

- Presentation structure and results narrative
- Live demo walkthrough preparation
- Website content review and feedback
- Uploaded presentation files to the repository
- Team meeting coordination and scheduling
- Contributed to report review and formatting feedback

**Max — Report & Ethics**

Max owned the written quality of the report. He wrote the full ethics section, the limitations section, and the conclusion. He also sourced all references, did the final proofread, and contributed to repository documentation.

- Report sections 5–6 (Ethics and Conclusion)
- All 11 academic references with DOIs
- Limitations section (4.4)
- Final report proofreading and formatting
- Contributed to CONTRIBUTIONS.md and repository documentation
- Reviewed and gave feedback on the README

---

## Contribution Overview

| Area | Karim | Kushul | Tarik | Max |
|---|---|---|---|---|
| Repository & uploads | ●●●●● | ●●●○○ | ●●●○○ | ●●○○○ |
| Data pipeline & preprocessing | ●●●●● | ●●●●○ | ●●○○○ | ●●○○○ |
| Model training & tuning | ●●●●● | ●●●●○ | ●●○○○ | ●●○○○ |
| Metrics verification | ●●●●○ | ●●●●● | ●●○○○ | ●●○○○ |
| Website & deployment | ●●●●● | ●●○○○ | ●●●●○ | ●●○○○ |
| Report — technical (1–4) | ●●●●● | ●●●○○ | ●●○○○ | ●●●○○ |
| Report — ethics & conclusion (5–6) | ●●○○○ | ●●○○○ | ●●○○○ | ●●●●● |
| References & formatting | ●●○○○ | ●●○○○ | ●●○○○ | ●●●●● |
| Presentation & communication | ●●●○○ | ●●●○○ | ●●●●● | ●●●○○ |
| Code review | ●●●○○ | ●●●●● | ●●○○○ | ●●○○○ |

---

*Written by Group 3. All four members reviewed this before submission.*
