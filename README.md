# Docs.dev Beta Testing: Plain Language Project

**Date:** May 4, 2025 Author: [Melissa Vagi, Founder & Director of AI Content Strategy, Write-Brained Editorial Services LLC](https://www.writebrainedits.com/about)

**Repository:** [https://github.com/vagimeli/plain-language-compliance-project](https://github.com/vagimeli/plain-language-compliance-project)

## Overview
This repository tests Docs.dev, a tool that creates and checks documents. The project focuses on plain language, following the Plain Writing Act of 2010. It uses a 6-hour plan to see how well Docs.dev makes clear, simple documents for everyday users. The repository has code, a user guide, a checklist, a fixed guide, and settings for plain language.

## Purpose
This project checks if Docs.dev can:

- Make clear documents from datasync.py code.
- Find and fix plain language problems in user-guide-original.md, like complex words or long sentences.
- Edit documents easily using Markdown and GitHub.
- Use Dev-Docs.JSON to create plain language documents.

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
To test Docs.dev with this repository:

- Copy the repository: git clone https://github.com/your-username/docs-dev-test-repo.git
- Add the Docs.dev GitHub App (see https://learn.docs.dev/docs).
- Use Docs.dev to:
- Create documents for datasync.py using Dev-Docs.JSON.
- Check user-guide-original.md with plain-language-checklist.md.
- Edit documents to match user-guide-revised.md and test GitHub updates.

Write results in docs/feedback-report.md and add issues in the Issues tab.

## Testing Scenarios

- Create Documents: Make documents for datasync.py. Check if they use simple words, active voice, and are easy to read (Grade 8 level).
- Check Documents: Look at user-guide-original.md for problems like jargon or passive voice. Compare it to user-guide-revised.md.
- Edit Documents: Fix user-guide-original.md in Docs.dev’s editor to follow plain-language-checklist.md.
- Share Feedback: Add bugs (e.g., “Missed complex word ‘utilize’”) or ideas (e.g., “Add a readability score”) to Issues.

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
