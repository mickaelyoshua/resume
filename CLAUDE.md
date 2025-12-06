# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal resume repository containing multiple versions of Mickael Yoshua's resume in different languages and targeting different roles:

- `resume.md` - English version (Data Engineer/Back-end Developer focus)
- `resume-portuguese.md` - Portuguese version (Data Engineer/Back-end Developer focus)
- `resume-analyst.md` - Portuguese version tailored for Data Analyst positions
- `resume-portuguese.pdf` - PDF export of the Portuguese version

## Repository Purpose

This repository is used to maintain and version-control resume variants for different job applications. Each markdown file can be customized to emphasize different skills and experiences based on the target role.

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

### Example: Data Analyst Focus
For data analyst positions, emphasize:
- Data extraction, cleaning, and analysis
- Dashboard and report creation
- KPIs and business insights
- ETL pipelines and data visualization tools (Power BI, QlikView)

Move these elements earlier in descriptions and skill lists while de-emphasizing pure engineering aspects.

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
pandoc resume-minsait.md -o resume-minsait.pdf --pdf-engine=pdflatex --from=markdown -V geometry:margin=1in -V colorlinks=true -V urlcolor=blue -V mainfont="Noto Sans"
```

Adapt the input/output filenames as needed for other resume variants.

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
