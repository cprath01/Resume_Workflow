# Resume Workflow — Taylored Resumes & Cover Letters

A lightweight repo for creating **tailored resumes and cover letters** per job posting. The goal is to keep a clean, repeatable workflow: store sample/source documents, create role-specific variants, and track what was submitted.

## What this repo is for

- Drafting and iterating on resumes and cover letters targeted to a specific role/company
- Keeping reusable base content (skills, accomplishments, bullets) alongside role-specific outputs
- Storing **sample documents** you can copy from (with personal info removed if sharing)

## Recommended workflow

1. Start from your best baseline resume/cover letter.
2. Create a new job-specific version (copy, then edit for the role) by using CoPilot.
3. Keep filenames descriptive so you can find what you sent later.

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
