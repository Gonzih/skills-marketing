# @gonzih/skills-marketing

Claude Code skill suite for marketing managers, brand strategists, and content creators.

## Skills included

| Skill | Command | Description |
|---|---|---|
| Content Calendar | `/content-calendar` | Generate a monthly content calendar with themes, post ideas, platform strategies, and hashtag plans |
| Brand Voice Guide | `/brand-voice-guide` | Build a brand voice document with tone, vocabulary, dos/don'ts, and channel-specific sample copy |
| Campaign Brief | `/campaign-brief` | Write a full campaign brief with objective, audience, messaging hierarchy, channels, and KPIs |
| Competitor Teardown | `/competitor-teardown` | Analyze a competitor's positioning, messaging gaps, content themes, and exploitable weaknesses |

## Install

```bash
npx @gonzih/skills-marketing
```

Or install globally:

```bash
npm install -g @gonzih/skills-marketing
```

Skills are copied to `~/.claude/skills/`. Restart Claude Code after installing.

## Usage

```
/content-calendar Acme Co June "B2B SaaS buyers" "drive trial signups"
/brand-voice-guide "Acme Co" SaaS "startup founders" "bold, direct, human"
/campaign-brief "Acme Pro plan" "generate 500 trials" "$20k" "6 weeks"
/competitor-teardown Competitor "Acme Co" "website, LinkedIn, ads"
```

## License

MIT
