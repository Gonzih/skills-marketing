---
name: content-calendar
description: Generate a full monthly content calendar with themes, post ideas, platform strategies, copy angles, and hashtag plans.
triggers: ["content calendar", "plan my content", "monthly content plan", "social media calendar", "content schedule"]
---

# Content Calendar

## What this skill does
Generates a complete monthly content calendar tailored to your brand, audience, and goals. Produces a week-by-week breakdown with themed content pillars, platform-specific post ideas, copy angles, and a hashtag strategy — ready to hand off to a content team or execute directly.

## How to invoke
/content-calendar [brand name] [month] [audience] [goals]

## Workflow steps

### Step 1 — Gather context
Ask for or infer: brand name, industry, target audience, primary platforms (Instagram, LinkedIn, TikTok, X, etc.), content goals (awareness, engagement, leads, retention), brand voice keywords, and any campaigns or events in the target month.

### Step 2 — Define content pillars
Establish 4–5 monthly themes or content pillars that align with the brand's goals and audience interests. Each pillar should have a clear purpose (educate, entertain, convert, build community, showcase product/service).

### Step 3 — Build the weekly calendar
For each week of the month, assign a primary theme and generate specific post ideas per platform. Include: post format (carousel, reel, thread, article, story), copy angle or hook, key message, and a call-to-action.

### Step 4 — Hashtag and keyword strategy
Produce a tiered hashtag strategy: 3–5 branded hashtags, 5–8 niche community hashtags, and 3–5 broad reach hashtags. Flag which hashtags belong to which content pillar.

### Step 5 — Output the calendar
Deliver a structured table or week-by-week breakdown with all post ideas, formats, copy angles, and hashtags. Include a summary of the monthly narrative arc and any cross-platform repurposing opportunities.

## Example outputs
A 4-week calendar with 20–30 post ideas organized by week, platform, format, and copy hook. Includes a hashtag bank and a one-paragraph monthly narrative summary. Formatted as a table or structured list ready for import into a content management tool.

## Live Data Sources

Use these sources to ground the calendar in real-time topic momentum and community signals:

- **Google Trends API** (`trends.google.com/trends/api`) — query interest-over-time for proposed content pillar keywords; prioritize topics with rising (not peaked) momentum curves; use geo and category filters to match the brand's market.
- **Reddit trending via Pushshift patterns** — surface threads gaining velocity in relevant subreddits (use `r/<niche>` + sort by `top/week`); mine comment language for authentic vocabulary and unmet questions that can seed post hooks and FAQ content.
