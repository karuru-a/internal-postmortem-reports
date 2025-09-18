# Postmortem Repository

This repository contains postmortem reports for incidents and issues across our systems and applications. A postmortem is a detailed analysis conducted after an incident to understand what happened, why it happened, and how to prevent similar issues in the future.

## What is a Postmortem?

Postmortems are blameless documents that focus on:
- **Learning** from incidents rather than assigning blame
- **Documenting** the timeline and root cause
- **Identifying** action items to prevent recurrence
- **Sharing** knowledge across the team

## Repository Structure

- `2025/` - Incidents organized by year
- `template.md` - Standard template for creating new postmortem reports
- Each incident gets its own directory with a descriptive name

## When to Write a Postmortem

Create a postmortem for:
- System outages or performance degradation
- Security incidents or breaches
- Data loss or corruption
- Deployment failures
- Any incident that impacts users or business operations

## Creating a New Postmortem

1. Copy `template.md` to a new directory under the appropriate year
2. Use the naming format: `month-day-brief-description`
3. Place any supporting images, logs, or screenshots in an `images/` subdirectory
4. Fill out all sections of the template thoroughly
5. Focus on facts, timeline, and actionable improvements

## Example Structure

```
|-- README.md
|-- internal-postmortem-reports
|   `-- 2025
|       |-- README.md
|       `-- september-18-wordpress-xmlrpc-attack
|           |-- README.md
|           `-- images
|               |-- high-cpu-utilization.png
|               |-- memory-utilization.png
|               `-- xmlrpc-blocked.png
`-- template.md
```

## Best Practices

- Write postmortems within 48 hours while details are fresh
- Include relevant screenshots, graphs, and log snippets
- Be specific about times, commands used, and steps taken
- Focus on systemic issues, not individual mistakes
- Always include action items with owners and due dates
