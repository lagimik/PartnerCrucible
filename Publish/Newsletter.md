You are generating a weekly Generative Partner Crucible post from repository changes in the last 7 days.

Use this exact style from recent _posts entries:
- YAML front matter with single-quoted title
- H1 section headings per workload
- Subheadings exactly "## What's new?" and "## Deep links"
- Emoji-led bullets in What's new
- Deep links in this exact pattern:
  - [Title](URL): one-line description (Source)
- End each section with a Topic Page sentence

Inputs:
1) run_date: {{RUNDATE}} (YYYY-MM-DD)
2) weekly_git_changes: structured data produced from git log and git diff for the past 7 days
3) optional_existing_post: prior weekly post for tone consistency only

Scope rules:
- Consider only .md files in repository root that represent topic pages (for example, DataAISolutionArea.md, SecuritySolutionArea.md, CSP.md)
- Ignore _posts entries when generating new content bullets (they are outputs, not inputs)
- Ignore purely mechanical changes (whitespace, typo-only, or format-only) unless they add or change external resources

Content extraction rules:
- Extract newly added or materially updated partner-facing resources from weekly diffs
- Prefer links explicitly present in changed lines; do not invent URLs
- If a meaningful update has no URL, include it in What's new but not in Deep links
- Merge related updates from multiple files into the same workload section when appropriate
- Keep wording concise, useful, and action oriented for Microsoft partners

Workload mapping guidance:
- AzureInfrastructureSolutionArea* -> Azure Workloads
- DataAISolutionArea* -> Data & AI Workloads
- DigitalAppsandInnovationSolutionArea -> Digital & App Innovation Workloads
- ModernWorkSolutionArea* -> Microsoft 365 Workloads
- SecuritySolutionArea* -> Security Workloads
- PowerPlatform* or BusinessApplications* -> Power Platform Workloads
- CSP -> CSP
- Industry* -> Industry Solutions Workloads
- If uncertain, infer workload from page title and changed content

Image metadata generation:
- For each changed topic page used in the post, output one image metadata record
- image_file: {{RUNDATE}}-<original-file>-image.png
- image_markdown: ![ <original-file> ]( /PartnerCrucible/assets/images/{{RUNDATE}}-<original-file>-image.png )
- image_prompt: monochrome, photorealistic, modern urban/enterprise scene aligned to that topic; no text, no letters, no logos

Output format (two blocks in this order):

1) FINAL_POST_MARKDOWN
Return one complete markdown file for _posts/{{RUNDATE}}-GenerativePartnerCrucible.md:

---
title: 'Generative Partner Crucible - for the week ending {{RUNDATE}}'
date: {{RUNDATE}}
flag: GenerativePartnerCrucible
layout: generativepartnercrucible
thumbnail: /PartnerCrucible/assets/images/{{RUNDATE}}-<best-thumbnail-source-file>-image.png
---

Then render all workload sections.

Section template:

![ <source-file>.md ]( /PartnerCrucible/assets/images/{{RUNDATE}}-<source-file>.md-image.png )

# <Workload Name>

## What's new?
- <emoji> <short update title>: <single-line summary>
- <emoji> <short update title>: <single-line summary>

## Deep links
- [<Link title>](<URL>): <single-line why it matters> (<Source>)
- [<Link title>](<URL>): <single-line why it matters> (<Source>)

Visit the extended Partner Crucible page on this [Topic Page](https://lagimik.github.io/PartnerCrucible/<source-file-without-.md>) for more partner resources.

2) IMAGE_METADATA_JSON
Return JSON array with one object per source file used:
[
  {
    "source_file": "DataAISolutionArea.md",
    "image_file": "{{RUNDATE}}-DataAISolutionArea.md-image.png",
    "image_markdown": "![ DataAISolutionArea.md ]( /PartnerCrucible/assets/images/{{RUNDATE}}-DataAISolutionArea.md-image.png )",
    "image_prompt": "<prompt text>"
  }
]

Quality checks before finalizing:
- Every Deep links URL must appear in weekly_git_changes
- No duplicate links across sections unless context is different
- All section headings and subheadings match the template exactly
- Front matter keys and order match the template exactly
- Date and filename use {{RUNDATE}}
- Keep the post practical, concise, and publish-ready

