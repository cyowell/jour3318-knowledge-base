# 🕵️‍♀️ Day 0 Lab: LinkedIn Job Vetting & Scam Forensics

**Activity Type:** Formative Performance Task / Day 0-1 Interactive Lab  
**Course SLO Addressed:** Apply digital verification tools to interrogate online entities, detect synthetic media (GANs), and establish an evidentiary chain of custody.  
**Estimated Time:** 45–60 minutes  

---

> ⚠️ **Reading this on GitBook?**  
> **GitBook is read-only.** You will read the investigation protocol here, but you will record your findings and evidence in your personal repository on GitHub:  
> 🔗 **[Open your Personal Investigative Workbench on GitHub →](https://github.com/cyowell/jour3318-knowledge-base/blob/main/student-portfolios/README.md)**

---

## 🎯 The Investigative Hook

As an undergraduate or emerging professional, your LinkedIn inbox and feed are targets for malicious actors. Fraudulent job postings have exploded due to automated LLMs, synthetic profile pictures (GANs), and sophisticated data-harvesting networks. 

These postings generally fall into three distinct categories:
1. 🟢 **Legitimate Job:** A verified corporate entity with matching corporate registration, a genuine corporate career portal, and verifiable human recruiters.
2. 🔴 **Phishing / Advance-Fee Scam:** A malicious operation designed to harvest Social Security numbers, banking details, or run "fake check equipment reimbursement" scams.
3. 🟡 **Ghost Job / Data-Harvesting Operation:** An ad or shell listing designed to harvest resumes for lead generation or inflate company growth metrics with no real open role.

Your mission in this lab is to conduct a **forensic investigation** of a assigned or student-selected LinkedIn job posting and render a verified editorial verdict based on **three independent vectors of proof**.

---

## 🛠️ The 4-Vector Verification Protocol

Do not rely on appearances or professional logos. Follow this four-step forensic protocol:

```
[ Step 1: Recruiter Visual Forensics ]  ──>  [ Step 2: Corporate Registry Lookup ]
                                                                ↓
[ Step 4: Editorial Verdict & Triangulation ] <──  [ Step 3: Domain & Infrastructure Check ]
```

---

### Vector 1: Recruiter Headshot & Profile Interrogation
Scammers frequently use AI-generated headshots from Generative Adversarial Networks (StyleGAN / Midjourney).
* **Forensic Visual Check:** Look for GAN artifacts:
  - Are the pupils centered precisely in the middle of the frame?
  - Are the earlobes, earrings, or glasses asymmetrical?
  - Is the background unnaturally blurred with strange melted shapes?
* **Reverse Image Search:**
  - Right-click the recruiter's profile image $\rightarrow$ search using **Google Lens**, **Yandex**, or **TinEye**.
  - Does the same photo appear on 20 different dating sites, stock photo libraries, or random crypto profiles under different names?

---

### Vector 2: Official Corporate Entity Registration
Legitimate companies must be legally registered with state or national governments.
* Search the official business registry:
  - **Texas Secretary of State:** [SOSDirect](https://www.sos.state.tx.us/corp/sosda/index.shtml) / [Texas Comptroller Business Search](https://mycpa.cpa.state.tx.us/coa/)
  - **National / International:** [OpenCorporates.com](https://opencorporates.com)
* **Check the details:**
  - When was the entity formed? (Red flag: A company claiming "20 years of industry leadership" formed 3 weeks ago).
  - Who is the registered agent? Is the address a real commercial office or a UPS Store / vacant residential lot on Google Maps?

---

### Vector 3: Domain Age & Infrastructure Analysis
Scammers often create lookalike domains (e.g., `company-careers-apply.com` instead of `company.com`).
* Look up the website domain on **[WHOIS (lookup.icann.org)](https://lookup.icann.org/)** or **[whois.domaintools.com](https://whois.domaintools.com/)**:
  - **Creation Date:** Was the domain registered within the last 30–90 days?
  - **Registrar:** Is it registered through disposable privacy proxies?
  - **Email MX Records:** Does the recruiter email you from `@gmail.com` / `@outlook.com` rather than the verified corporate domain?

---

### Vector 4: Triangulation via the Official Careers Portal
* Navigate directly to the organization's official, primary website.
* Check their official `/careers` or `/jobs` page.
* Does this specific requisition number or position exist on their primary platform?

---

## 📋 Student Deliverable: Logging Your Investigation

Open your personal **`investigation-log.md`** on GitHub and fill out entry **`INV-01`**:

```markdown
### INV-01: LinkedIn Job Posting Vetting
- **Target URL:** [Paste Job Posting URL]
- **Archived Snapshot:** [Wayback Machine or Archive.today link]
- **Target Company / Role:** [e.g., Apex Tech Solutions — Remote Junior Research Assistant]

#### 1. Evidence & Chain of Custody
- Recruiter Profile Screenshot: `evidence/inv01_recruiter.png`
- Corporate Registry PDF / Screenshot: `evidence/inv01_sos_registry.png`
- Domain WHOIS Lookup: `evidence/inv01_whois.png`

#### 2. Triangulation Matrix
| Vector | Tool / Source Used | Observations & Evidence |
| :--- | :--- | :--- |
| **Vector 1: Recruiter** | Yandex / Google Lens | Profile photo matched StyleGAN synthetic face repository. |
| **Vector 2: Corporate Registry** | OpenCorporates / State Registry | No legal business entity registered under this name in listed state. |
| **Vector 3: Domain Age** | ICANN WHOIS | Domain registered 8 days ago via NameCheap privacy proxy. |
| **Vector 4: Official Portal** | Official Company Website | Official domain does not list any remote openings matching this title. |

#### 3. Editorial Verdict
- **Classification:** `[LEGITIMATE / PHISHING SCAM / GHOST JOB]`
- **Information Disorder Taxonomy:** `[Imposter Content / Fabricated Content]`
- **Confidence Level:** High (Triangulated across 3 independent vectors)
- **Public Warning / Reporter Summary:** [2-3 sentences explaining why a job seeker should avoid or proceed with this posting].
```

---

## 🤖 Using the Course Gemini Gem (AI Logging)

If you use the course Gemini Gem to help analyze the job description or write a corporate lookup query:
1. Record your prompt in [`PROMPTS.md`](https://github.com/cyowell/jour3318-knowledge-base/blob/main/student-workbench-template/PROMPTS.md).
2. Check if the AI hallucinated any business facts or company history.
3. Mark your verdict as `[ACCEPTED]`, `[MODIFIED]`, or `[REJECTED - HALLUCINATION]`.

---

## 🏆 Promoting Your Investigation

Standout investigations with rigorous chain-of-custody documentation will be selected for publication into the [Community Investigation Logs](https://digitalinvestigations.gitbook.io/digitalinvestigations-docs/investigative-case-studies/investigation-logs-index) via Pull Request!
