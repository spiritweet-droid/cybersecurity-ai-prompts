# Contributing to Cybersecurity AI Prompts

Thank you for contributing. This guide explains how to add or improve prompts.

---

## Prompt Quality Standards

Every prompt must meet the following standards before submission.

### Structure
- Opens with a clear role framing statement
- Includes a numbered intake section that collects all needed context
  before any output is generated
- Breaks output into labeled sections with clear headers
- Ends sensitive workflows with a safety gate or authorization check

### Tone and Language
- Uses plain, professional English throughout
- Avoids unexplained jargon — define terms on first use
- Assumes the reader is an entry to mid-level security professional,
  not a tool vendor or academic

### Safety
- Any prompt involving offensive techniques must include an
  authorization confirmation in the intake
- Steps that could cause system damage must be labeled DESTRUCTIVE
  with an explicit approval requirement

### README
- Every prompt must include a README.md following the existing format
- README must include: overview, prompt engineering highlights,
  target user table, and how to use steps

---

## Folder Structure

New prompts must follow this structure exactly:

```
/your-prompt-name/
  README.md
  prompt.md
```

---

## Submitting a Pull Request

1. Fork this repository
2. Create your prompt folder using the structure above
3. Confirm your prompt passes all checklist items
4. Submit a PR with: prompt name, use case, and a one-paragraph description
