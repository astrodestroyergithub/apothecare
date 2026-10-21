# Apothecare — Universal Medicinal, Healing & Big-Data Clinical Sanctuary

**Apothecare** is a responsive, fault-tolerant medical web platform built for **Netlify** hosting. It serves **Patients, Doctors, Nurses, Medical Representatives (MRs), and Medical Students** through a biophilic hospital-relief aesthetic paired with a multi-API biomedical big-data engine.

## Quick Deployment to Netlify

1. **Drag & Drop (Netlify Drop)**:
   - Unzip `apothecare_netlify.zip` and drag the extracted folder directly onto [app.netlify.com/drop](https://app.netlify.com/drop).
2. **Netlify CLI**:
   ```bash
   npx netlify-cli deploy --dir=. --prod
   ```
3. **Git Continuous Deployment**:
   - Push this directory to GitHub/GitLab/Bitbucket and connect the repository in Netlify. `netlify.toml` and `_redirects` are pre-configured.

## Multi-API High-Availability Architecture

Apothecare integrates 8 biomedical & career APIs with automatic circuit-breaker failover and an in-memory Big-Data procedural synthesizer (scaling from 10,420+ to 15,000+ JSON objects at 60 FPS):
- **OpenFDA Drug Label & NDC API** (`api.fda.gov`)
- **NIH / NLM RxNorm, RxTerms & ICD-10-CM ClinicalTables API** (`clinicaltables.nlm.nih.gov`)
- **Europe PMC / PubMed REST API** (`ebi.ac.uk/europepmc`)
- **ClinicalTrials.gov API v2** (`clinicaltrials.gov/api/v2`)
- **Disease.sh Global Epidemiological Surveillance API** (`disease.sh`)
- **Wikimedia / Wikipedia Medical REST API** (`en.wikipedia.org/api/rest_v1`)
- **OpenAlex Biomedical Works API** (`api.openalex.org`)
- **Remotive Medical & Health Jobs API** (`remotive.com/api`)
