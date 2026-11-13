# Awesome AI for Office Workers [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of AI tools, guides, prompts and skills for people who run offices: admin clerks, dispatchers, coordinators, receptionists and small-business owners. No programming needed.

Most AI lists on GitHub are written for developers. This one is for the person who spends the day in email, Excel, Word and PDFs, and wants AI to take the repetitive work off their desk **safely**.

Every entry is free or has a free option, and was chosen because it helps with real office work.

## Contents

- [Start here: learn to write good prompts](#start-here-learn-to-write-good-prompts)
- [Claude skills for office work](#claude-skills-for-office-work)
- [Documents, PDFs and scans](#documents-pdfs-and-scans)
- [Automation without code](#automation-without-code)
- [Desktop helpers](#desktop-helpers)
- [Small ready-made office tools](#small-ready-made-office-tools)
- [Rules for using AI safely at work](#rules-for-using-ai-safely-at-work)
- [Contributing](#contributing)

## Start here: learn to write good prompts

- [Anthropic's Prompt Engineering Interactive Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) - Step-by-step course in 9 chapters. Also available as Google Sheets, which is easier if you don't code.
- [Anthropic Courses](https://github.com/anthropics/courses) - Free hands-on courses, including "real world prompting" for complex everyday tasks.
- [Claude prompt engineering docs](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) - Short official reference: be clear, give examples, ask for a format.
- [Gemini for Google Workspace: Prompting Guide 101 (PDF)](https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf) - Google's handbook with example prompts by job role (HR, customer service, project management and more). Useful even if you don't use Gemini.
- [Microsoft Copilot Prompt Gallery](https://adoption.microsoft.com/copilot/prompt-gallery) - Ready prompts for Word, Excel, Outlook and Teams.

## Claude skills for office work

Skills are folders of instructions that teach Claude how to do a task your way, every time.

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's official skills, including Word, Excel, PowerPoint and PDF skills. The best place to see how a skill is built.
- [office-claude-skills](https://github.com/Tonymathewz/office-claude-skills) - Approve-first skills for admins and dispatchers: email-to-approval queue, closure-notice-to-route mapper, monthly summary reports.
- [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) - A large community list of Claude skills and tools.

## Documents, PDFs and scans

- [MarkItDown](https://github.com/microsoft/markitdown) - Microsoft's tool that turns Word, Excel, PowerPoint and PDF files into clean text an AI can read well.
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - Merge, split, rotate, compress, sign and convert PDFs from your browser. Can run on your own computer so files never leave the office.
- [Tabula](https://github.com/tabulapdf/tabula) - Pull tables out of PDFs (statements, reports, price lists) into Excel/CSV.
- [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) - Makes scanned PDFs searchable and copyable.

## Automation without code

- [n8n](https://github.com/n8n-io/n8n) - Visual workflow builder: "when an email arrives, save the attachment, update the sheet, ask me to approve". Connects to Claude, OpenAI and Google models. Free to self-host.
- [n8n Self-hosted AI Starter Kit](https://github.com/n8n-io/self-hosted-ai-starter-kit) - A ready template for running AI workflows on your own machine.
- [Activepieces](https://github.com/activepieces/activepieces) - Open-source alternative to Zapier with a simple drag-and-drop builder.

## Desktop helpers

- [Espanso](https://github.com/espanso/espanso) - Text expander. Type `;thanks` and it writes your full standard reply. Great for repeated emails.
- [Microsoft PowerToys](https://github.com/microsoft/PowerToys) - Free Windows extras, including Text Extractor (copy text from any screenshot or image) and bulk file renaming.

## Small ready-made office tools

- [Airport Sign Printer](https://github.com/Tonymathewz/airport-sign-printer) - One HTML page that prints large A4 client name signs for airport and hotel pick-ups. No install, no account.
- [Office Automation Lessons](https://github.com/Tonymathewz/office-automation-lessons) - Practical gotchas from automating daily Excel reports with Python, LibreOffice and OneDrive, so you don't lose the same hours.

## Rules for using AI safely at work

Short rules that save you from the most common mistakes:

1. **You approve, AI applies.** Let AI prepare emails, bookings and changes, but read the preview and say yes yourself before anything is sent or saved.
2. **Don't paste private data into tools you don't control.** Customer names, phone numbers, ID numbers and bank details stay out unless your company has approved the tool.
3. **Check numbers and dates.** AI can mix up day-first and month-first dates, or add totals wrongly. Check before you send.
4. **Keep the original.** Work on a copy of a file, never the only version.
5. **Leave a note.** When AI helps change a record, write down what changed, why, and where the request came from.
6. **If it guesses, stop it.** A good setup asks you when something is missing instead of inventing an answer.

## Contributing

Suggestions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tony Mathew](https://github.com/Tonymathewz) has waived all copyright and related rights to this work.
