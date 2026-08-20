# 🚀 Getting Started with GitHub: Student Onboarding Guide

**Course:** JOUR 3318 — Digital Investigative Techniques  
**Welcome to your digital investigative workbench!**

In this course, you will not just read about investigative journalism — you will practice it using the same version control, archiving, and code collaboration tools used by professional open-source intelligence (OSINT) analysts and computational journalists worldwide.

> **Don't panic if you've never used GitHub before!**  
> For the first half of this course, you will do **100% of your work directly in your web browser**. No command lines, terminal commands, or complicated installations required.

---

## 🎯 The Three Platforms You Will Use

| Platform | What It Is | How You Use It |
| :--- | :--- | :--- |
| **[Course GitBook](https://digitalinvestigations.gitbook.io/digitalinvestigations-docs)** | The Course Hub | The authoritative reference manual. Read forensic protocols, tool guides, and course materials here. |
| **Your Personal GitHub Repo** | Your Investigative Workbench | Your private/personal digital reporter’s notebook. Log evidence in `investigation-log.md` and track AI chats in `PROMPTS.md`. |
| **[Course Knowledge Base](https://github.com/cyowell/jour3318-knowledge-base)** | Community Archive | Where the class collaborates. You submit **Pull Requests** here to publish your best discoveries and earn permanent attribution. |

---

## 🛠️ Step 1: Create Your Free GitHub Account

1. Go to **[github.com/signup](https://github.com/signup)**.
2. Sign up using your university email address.
3. Choose a professional username (e.g., `janedoe-jour` or `jdoe`). This will appear on your published investigations and portfolio.
4. Verify your email address.

---

## 🔬 Step 2: Set Up Your Personal Investigative Workbench

You will create your own personal repository to store your investigation notes and AI logs.

1. Navigate to the **[JOUR 3318 Student Workbench Template](https://github.com/cyowell/jour3318-knowledge-base/tree/main/student-workbench-template)** (or the template link provided on Canvas).
2. Click the green **"Use this template"** button $\rightarrow$ select **"Create a new repository"**.
3. Configure your repository:
   - **Repository Name:** `jour3318-workbench-[your-name]` (e.g., `jour3318-workbench-alex`)
   - **Description:** `JOUR 3318 Investigative Workbench for [Your Name]`
   - **Visibility:** Public (or Private if instructed by your professor)
4. Click **"Create repository"**.

🎉 **Congratulations!** You now have a personal investigative workspace with pre-formatted files:
- `investigation-log.md` (where you record evidence and case findings)
- `PROMPTS.md` (where you log AI interactions and check for hallucinations)

---

## 📝 Step 3: Edit Files Directly in Your Browser (No Terminal Required)

Whenever you want to add an entry to your log:

1. Open your repository on GitHub.com.
2. Click on the file you want to edit (for example, `investigation-log.md` or `PROMPTS.md`).
3. Click the **pencil icon (✏️)** in the top right corner of the file.
4. Type or paste your findings into the markdown editor.
5. Scroll down to the bottom:
   - In the "Commit message" box, type a short note about what you added (e.g., `Add initial job vetting evidence for INV-01`).
   - Click the green **"Commit changes"** button.

Your changes are now saved, timestamped, and protected in the version history!

---

## 🤝 Step 4: How to Contribute to the Community Knowledge Base (Your First Pull Request)

When you discover an OSINT tool, write a Python script, or complete an investigation, you can promote it to the course knowledge base.

```
Fork the Course Repo  ──>  Create a new file  ──>  Fill template  ──>  Open Pull Request  ──>  Instructor Review
```

### The 5-Minute Pull Request Walkthrough:

1. **Fork the Knowledge Base:**
   - Go to [github.com/cyowell/jour3318-knowledge-base](https://github.com/cyowell/jour3318-knowledge-base).
   - Click the **"Fork"** button in the top right corner.
   - Click **"Create fork"**. This creates a linked copy under your account.

2. **Add Your File:**
   - In your forked repository, navigate into the appropriate folder (e.g., `phase-2-verification/` or `investigation-logs/`).
   - Click **"Add file"** $\rightarrow$ **"Create new file"**.
   - Name your file: `phase-2-verification/[tool-or-topic]-[your-name].md`.

3. **Paste & Fill Out the Template:**
   - Copy the [Contribution Template from the Course README](https://github.com/cyowell/jour3318-knowledge-base#contribution-template).
   - Document your discovery, steps, tools, and evidence links.
   - Click **"Commit changes"**.

4. **Submit Your Pull Request:**
   - At the top of your repository page, click the **"Pull requests"** tab $\rightarrow$ click **"New pull request"**.
   - Click **"Create pull request"**.
   - Title your PR: `[Phase 2] Reverse image workflow: Yandex - Jane Doe`.
   - Complete the **Verification & Rubric Checklist** that automatically appears in the description box.
   - Click **"Create pull request"**.

5. **Editorial Review & Merging:**
   - Your instructor will review your methodology.
   - Once approved and merged, your work automatically updates the live [Course GitBook](https://digitalinvestigations.gitbook.io/digitalinvestigations-docs) with your name permanently credited in the Git commit history!

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Q: What is Markdown (.md) and how do I format text?</b></summary>

Markdown is a simple way to format text with plain characters:
- `# Large Heading`
- `## Section Heading`
- `**Bold text**` and `*Italic text*`
- `- Bulleted list item`
- `[Link text](https://example.com)`
- `![Image description](image_url)`
</details>

<details>
<summary><b>Q: What is a "commit"?</b></summary>

A commit is a permanent, timestamped snapshot of your files. Unlike a Google Doc that overwrites your edits silently, each commit creates an immutable audit trail — providing the "verifiable chain of custody" required in professional forensic investigations.
</details>

<details>
<summary><b>Q: What if I make a mistake or break something?</b></summary>

You cannot break the main course repository! Because students submit work via **Pull Requests**, your instructor reviews everything before it gets merged. Furthermore, Git stores the full revision history, so any file can be rolled back to an earlier state at any time.
</details>

---

*Need assistance? Check the [Course GitBook](https://digitalinvestigations.gitbook.io/digitalinvestigations-docs) or consult the custom Course Gemini Gem for guided troubleshooting.*
