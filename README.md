# Plain Language Compliance Project for Docs.dev Beta Testing

**Date:** May 4, 2025 

**Author:** Melissa Vagi, Founder & Director of AI Content Strategy, [Write-Brained Editorial Services LLC](https://www.writebrainedits.com/about)

**Repository:** [https://github.com/vagimeli/plain-language-compliance-project](https://github.com/vagimeli/plain-language-compliance-project)

## Overview
This repository supports a 6-hour beta testing project for Docs.dev, an AI-assisted documentation tool, with a focus on plain language compliance per the Plain Writing Act of 2010. It includes a Python codebase, a non-compliant user guide, a compliance checklist, and a configuration file to test Docs.dev’s AI generation, auditing, and editing capabilities from a technical writer’s perspective.

## Purpose
The project evaluates Docs.dev’s ability to:
- Generate plain language-compliant documentation from `datasync.py`.
- Audit `user-guide-original.md` for clarity, active voice, and readability.
- Support Markdown editing and GitHub workflows for compliance revisions.
- Customize AI output via `Dev-Docs.JSON` for plain language standards.

## Repository Structure
```
docs-dev-test-repo/
├── .gitignore                      # Ignores Python files we don’t need
├── README.md                       # This overview file
├── Dev-Docs.JSON                   # Settings for plain language documents
├── datasync.py                     # Sample Python code
├── docs/
│   ├── user-guide-original.md      # User guide with plain language issues
│   ├── user-guide-revised.md       # Fixed user guide with clear language
│   ├── plain-language-checklist.md # List to check plain language rules
│   └── feedback-report.md          # Test results (added after testing)
```

## Usage
To use this repository for Docs.dev testing:
1. Clone the repository: `git clone https://github.com/your-username/plain-language-compliance-project.git`
2. Install the Docs.dev GitHub App (follow https://learn.docs.dev/docs).
3. Use Docs.dev to:
   - Generate documentation for `datasync.py` using `Dev-Docs.JSON`.
   - Audit `user-guide-original.md` with `plain-language-checklist.md`.
   - Edit docs and test pull request workflows.
4. Document findings in `docs/feedback-report.md` and the [Issues tab](https://github.com/your-username/plain-language-compliance-project/issues).

## Testing Scenarios

- **AI Generation**: Generate docs for `datasync.py`, checking for plain language compliance (e.g., active voice, no jargon).
- **Auditing**: Audit `user-guide-original.md` for issues like passive voice or complex terms.
- **Editing**: Revise docs in Docs.dev’s editor, ensuring compliance with `plain-language-checklist.md`.
- **Feedback**: File issues for bugs (e.g., “AI missed passive voice”) or suggestions (e.g., “Add readability score”).

## Notes

- Plain Language Focus: This project follows Plain Writing Act rules for clear, simple writing. It tests Docs.dev’s ability to help non-technical users.
- Feedback: After testing, add docs/feedback-report.md and Issues to share results with the Docs.dev team.
- Docs.dev Setup: Make sure the Docs.dev GitHub App works with this repository.
- Contact: Ask Melissa questions at [hello@writebrainedits.com](hello@writebrainedits.com).

## Acknowledgments
This project is a volunteer effort to help improve Docs.dev. Thank you to the Docs.dev team for letting me test their tool.

## References

- Docs.dev Quickstart: https://learn.docs.dev/docs
- Plain Writing Act: https://www.plainlanguage.gov/law/
- Plain Language Guidelines: https://www.plainlanguage.gov/guidelines/
