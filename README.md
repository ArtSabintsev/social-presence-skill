# Social Presence

A Claude Code skill for drafting LinkedIn posts, X (Twitter) posts, blog articles, newsletters, essays, and general writing with strategic voice, platform-native formatting, and human authenticity.

## Lineage

Social Presence is built on the persuasion framework from [command-presence](https://github.com/ArtSabintsev/command-presence-skill). That skill handles private, high-stakes communication (emails, investor messages, negotiations). This skill takes the same strategic foundation and applies it to public writing.

**Shared from command-presence:**
- Full 8-principle persuasion framework (Adams, Voss, Cialdini, Patterson, Willink, Greene, Fisher & Ury)
- Banned word/phrase lists and "sound human" voice rules
- Frame control, tactical empathy, loss aversion, identity-based persuasion

**Added by social-presence:**
- Platform-specific rules for LinkedIn, X, blogs, newsletters, and essays
- Algorithm-aware formatting and hook patterns
- Post type detection (thought leadership, story, hot take, thread, announcement, engagement)
- Blog post, newsletter, and essay structure guidance
- Extended anti-AI detection (em dash ban, triad-breaking, parallel structure variation)

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
/social-presence blog post about [topic]
/social-presence newsletter issue about [topic]
/social-presence essay on [topic]
/social-presence rewrite this for LinkedIn: [pasted text]
/social-presence rewrite this to sound more human: [pasted text]
/social-presence announcement post for [news] on [platform]
/social-presence both platforms: [topic]
```

## License

MIT
