# JOUR 3318: Digital Investigative Techniques

## Community Knowledge Base

**Course:** JOUR 3318 — Digital Investigative Techniques  
**Focus:** Open-Source Intelligence (OSINT), Computational Journalism & AI Verification  
**GitBook Hub:** [digitalinvestigations.gitbook.io/digitalinvestigations-docs](https://digitalinvestigations.gitbook.io/digitalinvestigations-docs)

---

## What Is This Repository?

This is the living, community-driven knowledge base for **JOUR 3318: Digital Investigative Techniques**. Built **by students, for students**, it serves as an open archive of verified OSINT methodologies, Python data-scraping workflows, forensic verification protocols, and critical AI prompt logs discovered throughout the semester.

Approved student contributions submitted via Pull Requests are merged here and automatically synchronized with the course GitBook reference hub.

---

## Repository Structure

| Folder | Focus & Contents |
| :--- | :--- |
| [`phase-1-philosophical/`](phase-1-philosophical/README.md) | Epistemology of truth, AI authorship, Frankfurt's *On Bullshit*, Information Disorder taxonomy |
| [`phase-2-verification/`](phase-2-verification/README.md) | Visual verification, reverse image search, EXIF metadata, chronolocation & geolocation |
| [`phase-3-computational/`](phase-3-computational/README.md) | Python scripts (BeautifulSoup, Pandas), web scraping, data cleaning, and digital evidence custody |
| [`phase-4-ai-integration/`](phase-4-ai-integration/README.md) | AI Studio, Google Pinpoint archives, GDELT, SynthID provenance, AI hallucination analysis |
| [`investigation-logs/`](investigation-logs/README.md) | Formative & summative investigation case studies (Job Vetting, Health Debunking, Video Forensics) |
| [`prompts-library/`](prompts-library/README.md) | Documented Gemini Gem interactions, prompting logic, bias critiques, and hallucination logs |
| [`student-portfolios/`](student-portfolios/README.md) | Registry of individual student investigative workbench repositories |

---

## How Students Contribute

Contributions follow the editorial review workflow used in professional investigative newsrooms.

```
Student discovers technique / completes lab
                   ↓
Documents findings in personal GitHub workbench repo
                   ↓
Forks jour3318-knowledge-base & creates new .md file
                   ↓
Submits Pull Request with completed Verification Checklist
                   ↓
Instructor / Peer Review & Editorial Revision
                   ↓
Merged into main → Automatically synchronized to GitBook
                   ↓
Permanent attribution in Git commit history
```

### Step-by-Step Submission Guide

1. **Fork This Repository:** Click the **Fork** button in the top right of this repository to create your own working copy.
2. **Create Your Contribution File:** Navigate to the relevant phase directory (e.g., `phase-2-verification/`) and add a new markdown file named using kebab-case:
   ```
   phase-2-verification/[technique-or-tool-name]-[your-name].md
   ```
3. **Use the Contribution Template:** Populate your file using the structured [Contribution Template](#contribution-template) below.
4. **Open a Pull Request:** Submit a Pull Request targeting the `main` branch. GitHub will automatically load the **Editorial Review Checklist**. Complete all applicable checkmarks.
5. **Editorial Review:** The instructor will review your PR, request revisions if verification steps need strengthening, and merge approved submissions.

---

## Contribution Template

Copy and paste this markdown template into your submission file:

```markdown
# [Title of Discovery or Methodology]

**Contributor:** [Your Name]  
**GitHub Username:** @[your-username]  
**Semester:** [e.g., Fall 2026 / Spring 2027]  
**Course Phase:** [Phase 1 / Phase 2 / Phase 3 / Phase 4]  
**Category:** [OSINT / Metadata / Python Script / AI Evaluation / Geolocation]  

---

## 1. Executive Summary & Public Information Value
<!-- Explain the discovery and connect it to unmet public information needs or course Essential Questions -->

## 2. Tools & Dependencies
- **Primary Tools:** [e.g., InVID, Jeffrey's Image Metadata Viewer, Bellingcat Toolkit]
- **Environment / Libraries:** [e.g., Python 3.11, BeautifulSoup4, Pandas]

## 3. Step-by-Step Methodology
1. **Step 1:** Describe the initial observation or data collection step.
2. **Step 2:** Detail the technical execution.
3. **Step 3:** Detail how results were corroborated.

## 4. Evidence & Chain of Custody
- **Permanent Archive URL:** [e.g., Wayback Machine or Archive.today link]
- **Hash / Verification Artifact:** [SHA-256 hash or raw file reference in workbench]
- **Supporting Screenshots / Notebooks:** [Link to your student workbench repo]

## 5. AI Interaction & Hallucination Log (If Applicable)
- **Prompt Provided:** 
- **Raw AI Output:** 
- **Critical Assessment:** [Explain why output was accepted, modified, or rejected]

## 6. Limitations & Ethical Considerations
<!-- Note legal limitations, terms of service compliance, privacy protections, and potential failure modes -->
```

---

## Editorial Guidelines

- **Discipline of Verification:** All claims must be triangulated across at least two independent vectors. Declarative certainty is not permitted without documented proof.
- **Permanent Archiving:** Avoid linking solely to live social media posts. Submit snapshot URLs from the Wayback Machine, Archive.today, or hash-verified evidence.
- **Privacy & Ethics:** Redact non-public personal information (PII) unless there is a clear, substantiated public interest justification.
- **Code Standards:** Python scripts must include explicit error handling, comments, and ethical scraping rate limits (`time.sleep`).

---

*JOUR 3318: Digital Investigative Techniques — Built on the discipline of verification. Maintained by truth-seekers.*
