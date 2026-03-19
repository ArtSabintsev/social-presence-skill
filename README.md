# Social Presence

A Claude Code skill for drafting LinkedIn posts, X (Twitter) posts, and threads with strategic voice, platform-native formatting, and human authenticity.

Built on the same persuasion and "sound human" framework as [command-presence](https://github.com/ArtSabintsev/command-presence-skill), adapted for social media.

## Install

```bash
claude mcp add-skill social-presence /path/to/social-presence-skill
```

Or symlink into your skills directory:

```bash
ln -s /path/to/social-presence-skill ~/.agents/skills/social-presence
```

## Usage

```
/social-presence LinkedIn post about [topic]
/social-presence X thread on [topic]
/social-presence hot take about [opinion]
/social-presence rewrite this for LinkedIn: [pasted text]
/social-presence announcement post for [news] on [platform]
/social-presence both platforms: [topic]
```

## What It Does

- Drafts platform-native posts for LinkedIn and X with correct formatting, length, and tone
- Applies persuasion principles (frame control, social proof, loss aversion, specificity) adapted for social
- Enforces a strict "sound human" rule — banned AI words, required contractions, varied sentence rhythm
- Detects post type (thought leadership, story, hot take, thread, announcement, engagement) and applies type-specific rules
- Runs a self-check before delivering every draft

## Relationship to Command Presence

Social Presence shares DNA with command-presence:
- Same banned word/phrase lists
- Same "sound human" voice rules
- Same persuasion framework (Cialdini, Voss, Adams)

But applies them through platform-specific lenses — LinkedIn's 3,000-char posts, X's 280-char constraints, thread structure, hook patterns, hashtag strategy, and algorithm-aware formatting.

## License

MIT
