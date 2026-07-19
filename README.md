# Recruiting Skills

AI-powered skills for Claude Code that help recruiters source, evaluate, and engage candidates. Designed for non-technical HR and talent acquisition professionals.

> **Adapted by Musab** — Founder, HireMomentum. Building done-for-you AI automation systems for recruitment agencies and HR departments.
> Original repo by [Tushar Mangla](https://github.com/tushar-mangla/recruitment-skills).

## What's Included

| Skill | What It Does |
|-------|-------------|
| **Job Requirement Analysis** | Walks you through a structured 18-dimension analysis of a role before you start sourcing |
| **ICP Builder** | Turns a job description into a weighted scoring rubric (must-have / important / nice-to-have) |
| **Job Seller** | Identifies what's exciting about a role, rewrites boring job ads, generates outreach hooks |
| **Sourcing Strategy Generator** | Creates Boolean search strings, Google X-ray searches, and a full channel checklist |
| **Candidate Screener** | Scores candidates against your rubric with evidence, ranks batches, writes hiring manager briefings |
| **Outreach Writer** | Writes personalized LinkedIn, email, and X messages with A/B variants and follow-up sequences |

Plus: a **pipeline tracker template** and **playbooks** for capturing what worked per role type.

## Installation

**Step 1: Clone this repo**

```
git clone https://github.com/musabhaad/recruitment-skills.git
```

**Step 2: Copy the `.claude` folder into your project or home directory**

Option A (project-scoped):
```
cp -r recruitment-skills/.claude /path/to/your-recruiting-project/
```

Option B (global):
```
cp -r recruitment-skills/.claude ~/.claude
```

Then restart Claude or start a new conversation.

## Quick Start

1. "Here's a job description, analyze the requirements" — triggers Job Requirement Analysis
2. "Build me a scoring rubric for this role" — triggers ICP Builder
3. "Make this job ad more appealing" — triggers Job Seller
4. "Where should I find candidates for this role?" — triggers Sourcing Strategy Generator
5. "Score this candidate against our rubric: [paste profile]" — triggers Candidate Screener
6. "Write outreach for this candidate" — triggers Outreach Writer

## Recommended Workflow

```
Job Requirement Analysis -> ICP Builder -> Job Seller -> Sourcing Strategy -> Candidate Screener -> Outreach Writer
```

## File Structure

```
.claude/
  skills/
    job-requirement-analysis/
    candidate-icp-builder/
    job-seller/
    sourcing-strategy-generator/
    candidate-screener/
    outreach-writer/
  playbooks/
  templates/
examples/
```

## About

Adapted by **Musab**, founder of **HireMomentum** — building done-for-you AI automation systems for recruitment agencies and HR departments.

Original project by [Tushar Mangla](https://github.com/tushar-mangla/recruitment-skills).

## License

MIT
