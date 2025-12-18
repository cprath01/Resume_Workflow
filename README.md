# Resume Workflow — Tailored
 Resumes & Cover Letters

A lightweight repo for creating **tailored resumes and cover letters** per job posting. The goal is to keep a clean, repeatable workflow: store sample/source documents, create role-specific variants, and track what was submitted.

## What this repo is for

- Drafting and iterating on resumes and cover letters targeted to a specific role/company
- Keeping reusable base content (skills, accomplishments, bullets) alongside role-specific outputs
- Storing **sample documents** you can copy from (with personal info removed if sharing)

## Setup

1. Install VS Code [download](https://code.visualstudio.com/download) or use [vscode.dev](https://vscode.dev)
2. Download this repo.
3. Start from your best baseline resume/cover letter. Place those files in the correct sample folders.

## Workflow
1. Open VS Code.
2. Open to the workflow folder
3. Open CoPilot Chat window
4. Prompt Copilot to 'Create a Resume and Cover Letter for the following Job Description'
5. Past the Job Description in

### Suggested naming

- Resumes: `Resume - <Name> - <Role> - <Company> - YYYY-MM-DD.ext`
- Cover letters: `Cover Letter - <Name> - <Role> - <Company> - YYYY-MM-DD.ext`

(Examples: `.docx`, `.pdf`, `.md` — use whatever format you prefer.)

## Folder structure

- [Samples/CoverLetters](Samples/CoverLetters)
  - Place sample cover letters (templates, strong past letters, de-identified examples)
- [Samples/Resumes](Samples/Resumes)
  - Place sample resumes (templates, master resume, de-identified examples)
- [.github/copilot-instructions.md](.github/copilot-instructions.md)
  - Guidance for using GitHub Copilot effectively and consistently in this repo

## Notes

- Consider removing personal data from any sample documents you intend to share.
- If you want, I can also add a minimal `.gitignore` (e.g., ignore exported PDFs or local drafts) — only if you tell me what file types you want tracked.
