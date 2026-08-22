# 15-Week Course Schedule & Weekly Roadmap

**Course:** JOUR 3318 — Digital Investigative Techniques  
**Structure:** 4 Instructional Phases + Week 8 Midterm Digital Detox + Week 15 Capstone Publication  

---

> [!IMPORTANT]
> **Reading this on GitBook?**  
> GitBook is your read-only course schedule and reference hub. All assignment submissions, code notebooks, and logs are maintained in your personal GitHub repository.  
> [Open the JOUR 3318 GitHub Repository ->](https://github.com/cyowell/jour3318-knowledge-base)

---

## Semester Schedule Overview

| Week | Phase | Topic Focus | Core Tools & Environment | Deliverable / Milestone |
| :---: | :---: | :--- | :--- | :--- |
| **W1** | **Phase 1** | The Crisis of Truth, Frankfurt's *On Bullshit* | Which Face is Real?, GitHub Web | **Day 0 LinkedIn Job Vetting Lab** |
| **W2** | **Phase 1** | AI Authorship & Meaning-Making | Indicator Guide, GAN Concepts | Reading Reflection 1 |
| **W3** | **Phase 1** | Taxonomy of Information Disorder | Case Studies (7 Types of Disorder) | Setup Student Workbench Repo |
| **W4** | **Phase 2** | Image Provenance & Reverse Searching | RevEye, TinEye, Yandex, Google Lens | Lab: False Context Image Tracking |
| **W5** | **Phase 2** | Deep Metadata & Extraction | Jeffrey's Metadata Viewer, SingleFile | Lab: EXIF & Timestamp Audit |
| **W6** | **Phase 2** | Video Forensics & Fragmentation | InVID / WeVerify Plugin | Lab: Video Keyframe Extraction |
| **W7** | **Phase 2** | Geolocation & Chronolocation | Google Earth Pro, SunCalc, Wikimapia | **Task 3: Video Verification Case Study** |
| **W8** | **Detox** | **Digital Silence Week (No Classes)** | **Zero Digital Tools (Analog Journal)** | **Midterm Metacognitive Reflection** |
| **W9** | **Phase 3** | Python Foundations & Scraping Ethics | Google Colab, requests, time.sleep | Lab: Ethical Scraper in Colab |
| **W10** | **Phase 3** | Scraping Public Registries | BeautifulSoup4, HTML DOM | Lab: Table Extraction to CSV |
| **W11** | **Phase 3** | Data Wrangling & Chain of Custody | Pandas, SHA-256 Evidence Hashing | Python Script pushed to GitHub |
| **W12** | **Phase 4** | Large-Scale Document Forensics | Google Pinpoint (Journalist Studio) | Lab: FOIA/PDF Entity Extraction |
| **W13** | **Phase 4** | Prompt Architecture & Hallucinations | Google AI Studio, Course Gemini Gem | Lab: Documenting PROMPTS.md |
| **W14** | **Phase 4** | Provenance Limits & Synthesis | SynthID Analysis, BuiltWith | Draft Capstone Case Study |
| **W15** | **Finale** | **Newsroom Editorial Board & Publication** | GitHub Pull Requests -> GitBook | **Capstone Published to GitBook** |

---

## Detailed Weekly Breakdown

### Phase 1: Philosophical & Epistemological Anchor (Weeks 1–3)

#### Week 1: The Crisis of Truth, Algorithmic Persuasion & Day 0 Lab
- **Guiding Question:** *Does truth matter in an algorithmically mediated society?*
- **Readings:** Harry Frankfurt, *On Bullshit*; Claire Wardle, *Taxonomy of Information Disorder*.
- **Hands-on Lab:** [Day 0 Lab: LinkedIn Job Vetting & Scam Forensics](investigation-logs/day-0-linkedin-job-vetting.md).
- **Core Activity:** Setting up personal student GitHub investigative workbenches from template.

#### Week 2: AI Authorship, Cognition & Generative Adversarial Networks (GANs)
- **Guiding Question:** *Is statistical token prediction the same as human meaning-making?*
- **Readings:** *Your AI Use Is Breaking My Brain*; *Is AI Really Writing?*
- **Hands-on Lab:** GAN facial artifact detection (*Which Face is Real?*), identifying synthetic symmetry flaws.
- **Deliverable:** Reading Reflection 1 recorded in personal workbench.

#### Week 3: Taxonomy of Information Disorder & Coordinated Inauthentic Behavior
- **Guiding Question:** *What are the financial and political incentives behind digital deception?*
- **Concepts:** Misinformation vs. Disinformation vs. Mal-information; context collapse; astroturfing.
- **Hands-on Lab:** Deconstructing historical case studies using the 7-part Information Disorder taxonomy.
- **Deliverable:** Verified registration of student repository on class roster.

---

### Phase 2: The Discipline of Verification & OSINT Fundamentals (Weeks 4–7)

#### Week 4: Static Image Provenance & Reverse Searching
- **Guiding Question:** *How do we locate the earliest recorded instance of an image on the global web?*
- **Toolkit:** RevEye browser extension (Google Lens, Yandex, TinEye, Bing).
- **Hands-on Lab:** Tracing viral breaking news imagery to uncover recycled footage (*False Context*).
- **Deliverable:** Image Provenance Lab Report.

#### Week 5: Forensic Metadata & Digital Preservation
- **Guiding Question:** *What hidden digital fingerprints exist inside image files before compression?*
- **Toolkit:** Jeffrey's Image Metadata Viewer, SingleFile browser extension, Wayback Machine, Archive.today.
- **Hands-on Lab:** Extracting camera make/model, ISO, timestamps, and embedded GPS coordinates; saving permanent archival snapshots.
- **Deliverable:** Forensic Metadata Case File.

#### Week 6: Audiovisual Forensics & Video Keyframing
- **Guiding Question:** *How can moving video clips be reliably authenticated during conflict or crisis events?*
- **Toolkit:** InVID / WeVerify verification plugin.
- **Hands-on Lab:** Fragmenting video into static keyframes; running automated reverse thumbnail searches to detect historical recycling.
- **Deliverable:** InVID Keyframe Deconstruction Exercise.

#### Week 7: Geolocation & Chronolocation Triangulation
- **Guiding Question:** *How do we pinpoint the exact physical location and time of day an event occurred?*
- **Toolkit:** Google Earth Pro, SunCalc (shadow and sun angle calculator), Wikimapia.
- **Hands-on Lab:** Triangulating architectural landmarks, road markings, and solar angles against satellite imagery.
- **Deliverable:** **Performance Task 3: Video Verification & Geolocation Case Study**.

---

### Midterm Transition: Week 8 Digital Silence Week

#### Week 8: Digital Detox & Metacognitive Reflection (No Classes)
- **Guiding Question:** *How has learning the mechanics of digital deception recalibrated your cognitive approach to information?*
- **Activity:** Screen-free, analog reflection journal. Step back from social media feeds and analyze personal scrolling loops and algorithmic conditioning.
- **Deliverable:** **Midterm Metacognitive Reflection Essay** (aligned with UbD Stage 2 self-assessment).

---

### Phase 3: Computational Journalism & Data Extraction (Weeks 9–11)

#### Week 9: Computational Thinking & Ethical Scraping with Python
- **Guiding Question:** *Why is programmatic data extraction essential for investigative accountability?*
- **Toolkit:** Google Colab (browser-based Python notebooks), Python `requests`, `time.sleep`.
- **Concepts:** Scraping ethics, respecting `robots.txt`, request throttling, and lawful data ingestion.
- **Hands-on Lab:** Writing an ethical web-fetcher script in Google Colab.

#### Week 10: Scraping Public Registries with BeautifulSoup
- **Guiding Question:** *How do we extract structured tables from messy, uncooperative HTML pages?*
- **Toolkit:** Python `BeautifulSoup4`, HTML DOM inspection.
- **Hands-on Lab:** Scraping public government or regulatory inspection records into structured JSON/CSV format.
- **Deliverable:** Working scraper script notebook in Google Colab.

#### Week 11: Data Wrangling, Cleaning & Evidentiary Chain of Custody
- **Guiding Question:** *How do we clean chaotic datasets while proving the raw evidence was never altered?*
- **Toolkit:** Python `pandas`, SHA-256 cryptographic hashing.
- **Hands-on Lab:** Filtering, sorting, and analyzing extracted datasets; generating cryptographic checksums for raw data.
- **Deliverable:** Documented Python scraping and cleaning script committed to student GitHub workbench.

---

### Phase 4: Deep AI Integration & Original Creation (Weeks 12–14)

#### Week 12: Large-Scale Document Forensics with Google Pinpoint
- **Guiding Question:** *How do investigative reporters search through 10,000 pages of unstructured FOIA documents in seconds?*
- **Toolkit:** Google Pinpoint (Journalist Studio).
- **Hands-on Lab:** Uploading, optical character recognition (OCR) indexing, and entity search across a massive public document dump.
- **Deliverable:** Pinpoint Entity Analysis Matrix.

#### Week 13: Prompt Architecture, Gemini Gems & Hallucination Audits
- **Guiding Question:** *How can we use generative AI as an investigative assistant without outsourcing our ethical responsibility?*
- **Toolkit:** Google AI Studio, Course Custom Gemini Gem.
- **Hands-on Lab:** Structured system prompting; stress-testing AI models for hallucinations, bias, and fabricated citations.
- **Deliverable:** Completed `PROMPTS.md` interaction log with editorial verdicts (`[ACCEPTED]`, `[MODIFIED]`, `[REJECTED]`).

#### Week 14: Digital Provenance Limits & Capstone Production Workshop
- **Guiding Question:** *Can automated watermarks solve deepfakes, and how do we synthesize multi-vector proof?*
- **Toolkit:** SynthID technical framework analysis, BuiltWith / DNSlytics infrastructure checks.
- **Hands-on Lab:** In-class investigative production lab; synthesizing OSINT, Python data, and document evidence.
- **Deliverable:** Draft of Summative Capstone Investigation.

---

### Finale: Newsroom Editorial Board (Week 15)

#### Week 15: Capstone Showcase & GitBook Editorial Publication
- **Guiding Question:** *How does verified investigative journalism meet unmet public information needs?*
- **Activity:** Students present their completed multi-vector investigative packages.
- **Publication:** Students submit final Pull Requests to [`jour3318-knowledge-base`](https://github.com/cyowell/jour3318-knowledge-base).
- **Editorial Outcome:** Approved investigations are merged live and permanently published to the **Course GitBook Hub**.
