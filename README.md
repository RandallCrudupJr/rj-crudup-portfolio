# RJ Crudup — IT Automation Portfolio

Solo IT administrator who designs and ships production automation across the Microsoft cloud — Power Automate, Microsoft 365, Azure, Microsoft Graph and PowerShell tooling around them. I tend to own solutions end to end: the integration plumbing, the data model, and the thing the end user actually sees.

This repo collects sanitized case studies of real solutions I've built — the problem each one solved, how it's put together, and the design decisions behind it. Credentials, internal identifiers, and personal data have been removed; only the logic and structure remain.

## Areas of focus

- **Automation & integration** — Power Automate (cloud flows), PowerShell, Microsoft Graph, REST API integration
- **Microsoft 365 & cloud** — M365 administration, Azure, Entra ID, SharePoint, Exchange Online
- **Data & reporting** — Power BI, SharePoint-backed datasets
- **Infrastructure** — firewalls, identity, and tenant administration

## Projects

- **[Automated Birthday & Work Anniversary Notifications](birthday-anniversary-notifications)** — A scheduled Power Automate flow that reads an enterprise HRIS via REST, finds upcoming birthdays and work anniversaries, and emails each employee's manager a formatted reminder. Shows paged API integration, timezone-safe date logic, relational manager lookups, and conditional templated email.
- **[Automated Monthly Teams Phone Call Reporting](teams-pstn-call-reporting)** — A scheduled Azure Automation runbook that pulls customer phone calls placed through Microsoft Teams Phone from Microsoft Graph, aggregates each agent's call volume and average talk time, and emails a monthly report formatted to mirror the team's existing contact-center report. Shows app-only Graph access via managed identity, PSTN call-record retrieval, least-privilege mail scoping with an Exchange Online application access policy, and Outlook-ready HTML reporting.

*More case studies in progress, including an LTL freight-tracking data pipeline (Power Automate → SharePoint → Power BI).*

## Connect

- LinkedIn: https://www.linkedin.com/in/rj-crudup-a801b7231
- Email: rjcrudup@proton.me
