# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal resume repository containing Mickael Yoshua's resume in two languages:

- `resume.md` - English version
- `resume-portuguese.md` - Portuguese version

Both files contain the same unified content covering software development, data engineering and back-end experience.

## Working with Resume Files

### Resume Structure
All resume files follow the same structure:
1. Header (name, contact info, social links)
2. Professional title and summary
3. Skills section (categorized by type)
4. Professional experience
5. Personal projects
6. Education

### Tailoring Resumes for Different Roles

When adapting a resume for a specific job:
- **Keep existing information**: Don't add skills or experiences that aren't already present
- **Reorder and emphasize**: Reorganize bullet points and sections to highlight relevant experience
- **Adjust categorization**: Regroup skills to make the most relevant ones prominent
- **Refocus descriptions**: Reword existing experience to align with job requirements
- **Update title**: Adjust the professional title to match the target role

## Git Conventions

- Commit messages should be concise and direct (no verbose descriptions)
- Do not sign commits (no Co-Authored-By or Generated with Claude Code footers)
- Use imperative mood (e.g., "Add feature" not "Added feature")

## File Conventions

- Resume files are in Markdown format
- Contact information includes LinkedIn, GitHub, and WhatsApp links
- Project links point to actual GitHub repositories
- PDF exports are committed for easy distribution

### Converting Markdown to PDF

Use pandoc to convert resume files from Markdown to PDF:

```bash
pandoc resume.md -o resume.pdf --pdf-engine=pdflatex --from=markdown -V geometry:margin=1in -V colorlinks=true -V urlcolor=blue -V mainfont="Noto Sans"
```

Replace filenames as needed for the Portuguese version.

## Claude's Role Context

### Professional Recruiter Expertise

Claude acts as a professional recruiter with expertise in:
- **Tech recruitment**: Understanding job market trends, company cultures, and role requirements
- **Resume optimization**: Tailoring resumes to specific companies and positions
- **ATS optimization**: Ensuring resumes pass Applicant Tracking Systems
- **Skills mapping**: Matching candidate skills to job requirements
- **Interview preparation**: Providing insights about companies and their hiring processes

When working with resumes in this repository:
- Research target companies thoroughly (culture, tech stack, recent news)
- Analyze job descriptions to identify key requirements
- Suggest strategic emphasis of existing skills (never fabricate experience)
- Recommend resume variants optimized for specific opportunities
- Provide context about industry trends and company positioning
