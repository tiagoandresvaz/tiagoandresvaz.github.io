# Experience and Projects Done

### Work Done {#work-samples}

#### Federated Data Pipeline {#covid-vaccines-effectiveness-cove}

As Core Scientific Lead, I designed and delivered this international federated data project led by Utrecht University, involving multiple European partners to evaluate the effectiveness of heterologous and booster COVID-19 vaccination schedules in five countries. The research used a cohort approach covering both children and adults with a completed primary vaccination regimen.

I led the development of a robust federated data pipeline, ensuring data from all partners adhered to a common data model and harmonised semantic concept libraries — enabling consistent, privacy-preserving analysis across diverse international contexts.

**Participating Organisations:**
- Utrecht University, The Netherlands (Consortium Lead)
- UMC Utrecht, The Netherlands
- VAC4EU, Belgium
- Democritus University of Thrace, Greece
- APHP, France
- ARS, Italy
- INSPIRE, Italy
- SoSeTe-Pedianet, Italy
- Rīga Stradiņš University, Latvia
- PHARMO Institute, The Netherlands
- RIVM, The Netherlands
- IACS, Spain
- IDIAPJGol, Spain
- RTI Health Solutions, Spain
- Servicio Navarro de Salud, Spain
- Teamit Institute, Spain
- DSRU, UK
- AEMPS, Spain (Coordinator)

**Project Documentation:**
- [Utrecht University — Project Homepage](https://www.uu.nl/en/research/eu-pepv-research-network/effectiveness-of-heterologous-and-booster-covid-19-vaccination-in-5-european-countries)
- [Study Protocol (approved by the European Union)](https://catalogues.ema.europa.eu/sites/default/files/document_files/D2_StudyProtocol_v0.4_ROC12_FINAL_20220615.pdf)
- [CoVE Project Repository (Zenodo)](https://zenodo.org/records/7858776)

**Key Results:**
- [Effectiveness of homologous/heterologous booster COVID-19 vaccination schedules against severe illness (PubMed)](https://pubmed.ncbi.nlm.nih.gov/37858451/)

#### Nursing Workload AI Classification {#wiley-pds-nursing-workload}

This study addressed the time burden of manual nursing workload classification by training a machine learning model to predict patient care needs from electronic health records. Using a Random Forest algorithm on nearly 44,000 nurse-conducted assessments, the model classified patients into four care levels — minimum, intermediate, semi-intensive, and intensive — achieving 72% overall accuracy and an AUC of 82%. The findings demonstrate that clinical data already captured in hospital systems can reliably automate workload assessment, freeing nurses to redirect time toward direct patient care.

[Read the full article](https://www.scielo.br/j/rlae/a/SPkGC5Hnmzhw5K4bftMvbmj/?lang=en)

#### Covid-19 Scenarios (Neherlab) {#covid-19-scenarios-by-neherlab}

Contributed to the Neherlab COVID-19 Scenarios model by implementing a new compartment in the SIR model — the "Palliative Flux" — modelling the transition of patients into palliative care. Implementation used Python for the statistical/epidemiological model and TypeScript (React, Node.js) for the UI.

Set up cloud environments (dev and production) with CI/CD pipelines so statisticians could run and validate models locally. Built a data parser to ingest real-time data from government dashboards and customised the calculator to generate specific scenarios for 26 local regions.

Collaboration included statisticians, physicians, and computer science faculty from UFRGS alongside state health authorities.

{{< youtube sv5T7MPKE5A >}}

#### AGHUse (Hospital de Clínicas de Porto Alegre) {#aghuse-by-hospital-de-clinicas-de-porto-alegre}

Co-author of the registered GPL software at INPI (Brazil's National Industrial Property Institute). AGHUse is a comprehensive EHR (Electronic Health Record) and ERP (Enterprise Resource Planning) system designed for healthcare providers of all types and sizes.

I initiated and named the project — after the original AGHU and the predecessor AGH — serving as main coordinator and lead for all developers. As original Technical Leader and later IT Executive, I led the rollout at a 1,000-bed hospital covering primary care, emergency, maternity, psychiatry, and heart transplants.

By 2016, AGHUse had become the most widely adopted university hospital software in Brazil. In 2017, it received the **Public Innovation Award from ENAP**. The project is now maintained by the "Comunidade AGHUse," which includes UNICAMP, the Brazilian Army, Air Force, local governments, and other universities.

**Recent expansion (2025):** AGHUse is now present in 8 Brazilian states across 100+ health facilities, including the Brazilian Army (4 hospitals, with plans for the full national military health system) and state health secretariats. In July 2025, the **Brazilian Ministry of Health officially joined the AGHUse community**, with Hospital Federal de Ipanema (Rio de Janeiro) as the first federal implementation site — a landmark milestone validating the platform's quality and reach across the national healthcare system.

{{< youtube MZocqXWM-Ig >}}

Hospital de Clínicas de Porto Alegre (900+ beds) was appointed by the federal government in 2009 as a blueprint for a digital healthcare business model — its software is now in use nationwide.

#### Meu Clínicas (Hospital de Clínicas de Porto Alegre) {#meu-clinicas}

Co-designed and led the development of Meu Clínicas, HCPA's patient-facing digital platform — one of the few hospital apps in Brazil available to SUS patients. Launched in 2019, it gives patients mobile and web access to schedule appointments, view exam results, download prescriptions and special medication reports, and conduct teleconsultations.

Since launch, the platform reached 1.9 million accesses through 2023, with 963,000 accesses in 2023 alone (37% year-over-year growth), over 200,000 teleconsultations completed, and an 85% reduction in paper volume for patient records.

{{< youtube hjr-vTxo5qU >}}

[HCPA — Meu Clínicas](https://www.hcpa.edu.br/area-do-paciente-apresentacao/meuclinicas)

#### AGHU (EBSERH — Empresa Brasileira de Serviços Hospitalares) {#aghu-by-ebserh}

AGHU is a complete EHR designed for federal university hospitals across all five regions of Brazil. As founding Technical Leader, I co-authored the source code in Java and later became the IT Executive responsible for rolling out the system across the first 23 hospitals — covering small, medium, and large institutions. The project is now maintained by EBSERH in partnership with a multi-university community.

**Recent expansion (2024):** AGHU now runs in 41 federal university hospitals, managing 25 million patient records with 5.6 million consultations and 190,200 surgeries recorded annually. In February 2024, the Ministries of Health and Education opened a public call for all SUS medium- and high-complexity hospitals to voluntarily adopt AGHU — a potential expansion to 3,000+ hospitals nationwide at no cost. EBSERH simultaneously launched AGHUx (version 11), the largest platform update in 15 years.

#### Infection Surveillance Assistant — ISA (Qualis Infectologia) {#infection-surveillance-assistant-by-qualis-infectologia}

As founding investor, partner, and AI Lead at Qualis Infectologia, I designed and built ISA — Infection Surveillance Assistant — an automated AI system running on Amazon AWS that helps hospitals streamline infection control and surveillance. The algorithm was validated against NHSN (National Healthcare Safety Network) definitions, achieving results comparable to manual expert review. After building and validating the product through peer-reviewed research, I made a successful exit from Qualis Infectologia in 2025.

**Published results:**
- [Hospital-acquired infections surveillance: The machine-learning algorithm mirrors NHSN definitions — *Infection Control & Hospital Epidemiology*, 2024](https://doi.org/10.1017/ice.2023.224)
- [Using Machine Learning to Reduce Burden on Infection Control Staff — *NEJM Catalyst*, 2022](https://doi.org/10.1056/cat.22.0071)
- [Automated healthcare-associated infection surveillance using an AI algorithm — *Infection Prevention in Practice*, 2021](https://doi.org/10.1016/j.infpip.2021.100167)

{{< youtube o4Nq3GmwRoM >}}

{{< admonition tip "More details and past works" >}}
Prior works and full portfolio details are available on my [LinkedIn profile](https://www.linkedin.com/in/tiagoandresvaz/).
{{< /admonition >}}
