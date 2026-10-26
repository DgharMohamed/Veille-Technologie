---
name: veille-technologies
description: Research, plan, build, and maintain Veille Technologies, producing a finished technology-watch deliverable whenever the user gives a technology concept.
---

# Veille Technologies

## Purpose

Help create and improve Veille Technologies as a clear, reliable place to follow technology news, developments, and trends. This skill applies to product planning, implementation, and technology-watch content.

## Default workflow for a technology concept

When the user gives a technology, product, standard, or other technical concept as a topic:

1. Give a short plan in plain language before changing files.
2. Research current or changing claims using reliable sources, preferably primary sources.
3. Complete the work in the same task; do not stop after proposing an outline or asking whether to proceed.
4. Create a topic-named folder in the repository root (for example, `MCP/`) and create or update the concise Marp presentation inside it, named `veille-<topic-slug>.md` (for example, `MCP/veille-mcp.md`).
5. Write the presentation in English by default for this workspace. Use another language when the user asks for it.
6. Structure the deck with a `Veille Plan` agenda and these three sections: `Introduction`, `Problems Encountered`, and `Solutions Implemented`. Adapt the content within each section to the concept; include a practical example and dated source links where useful. Omit details that do not fit the topic.
7. Check the resulting file and its Marp front matter, then report the artifact path and the sources/checks briefly.

### Required concept-deck outline

Use this slide sequence by default:

1. **Title** — name the concept and give a short subtitle.
2. **Veille Plan** — list `Introduction`, `Problems Encountered`, and `Solutions Implemented`.
3. **Introduction** — explain what the concept is in plain English and show its basic context or flow.
4. **Problems Encountered** — describe the need or difficulty the concept addresses. Do not invent shortcomings; use sourced, proportionate wording.
5. **Solutions Implemented** — explain how the concept works or addresses the need, with a concrete example and relevant limits.
6. **Sources** — link the reliable sources used, with publication dates where available.

Save the deck inside its topic-named folder, using a clear, filesystem-safe folder name such as `MCP`, `Laravel`, or `Web-Assembly`.

Combine or omit slides only when the topic makes a section irrelevant. Keep the audience general and the presentation simple. Do not create a separate plan file for every topic unless requested: the short plan is the work plan, and the Marp deck is the finished result.

For broader product or feature requests, use the implementation workflow below and create the requested working result, not only a plan.

## Product principles

- Make it easy to discover recent and relevant technology developments.
- Organize information with understandable topics, dates, and source attribution.
- Help readers quickly understand what happened, why it matters, who may be affected, and what to watch next.
- Keep pages and features simple, readable, accessible, and responsive.
- Prefer a small, useful solution over extra features that do not serve the product.
- Use the project's existing stack, design, and conventions. Inspect the repository before choosing an implementation.
- This is a technology-watch product, not a lab or course generator. Do not create educational labs unless the user asks.

## Technology-watch research

1. Identify the topic, audience, and relevant time period. Use the defaults above when unspecified.
2. Verify current claims with reliable, preferably primary sources such as official announcements, documentation, research papers, or public datasets.
3. Record source title, link, and publication date. Distinguish the publication date from the event date.
4. Explain what changed, why it matters, who may be affected, and what remains uncertain or worth watching.
5. Separate confirmed facts from analysis or forecasts. Never present a prediction as a fact.
6. Leave unverifiable claims out of factual summaries.

## Implementation workflow

1. Show a short plan.
2. Inspect relevant files and the current project state.
3. Identify the smallest complete change that meets the request.
4. Implement it using existing conventions; keep content and interface focused on Veille Technologies.
5. Check changed files and relevant links or behavior. Do not run tests unless the user asks for tests or verification.
6. Summarize what changed and what was checked, and list skills used.

## Content defaults

- English is the default language for this workspace, based on the user's preference. Follow a later explicit language request.
- For Marp decks, use the project's simple format: `marp: true`, `theme: default`, `paginate: true`, and `size: 16:9`.
- Prefer short titles, brief paragraphs, descriptive links, and clear dates.
- A technology update should normally include a title, topic, event date (when known), publication date, short summary, why it matters, and sources.
- Avoid hype, unexplained jargon, unsupported rankings, and claims that a technology is "the best" without a stated basis.




