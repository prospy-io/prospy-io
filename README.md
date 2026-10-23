# Prospy

Small, open-source tools for finding people who are asking for a product: read-only keyword watchers and a transparent buying-intent scorer. MIT-licensed, no third-party runtime dependencies.

| Tool | What it does | Code | Package |
| --- | --- | --- | --- |
| **hn-keyword-watch** | Watches Hacker News for keywords and buying-intent phrases via the official HN Firebase and Algolia search APIs (Python CLI). | [Codeberg](https://codeberg.org/prospy/hn-keyword-watch) · [GitHub](https://github.com/prospy-io/hn-keyword-watch) | [PyPI](https://pypi.org/project/hn-keyword-watch/) |
| **bsky-keyword-watch** | Read-only Bluesky keyword watcher using the public AT Protocol `searchPosts` endpoint (TypeScript CLI and library). | [Codeberg](https://codeberg.org/prospy/bsky-keyword-watch) · [GitHub](https://github.com/prospy-io/bsky-keyword-watch) | |
| **intent-score** | Scores posts 0–100 for buying intent with editable regex rules; every point comes with a reason (Python). | [Codeberg](https://codeberg.org/prospy/intent-score) · [GitHub](https://github.com/prospy-io/intent-score) | [PyPI](https://pypi.org/project/intent-score/) · [demo](https://prospy-io.github.io/intent-score/) |

Codeberg is the canonical home for each repo; GitHub holds mirrors. Issues and pull requests are welcome on either.

**Tutorial:** [Find buying-intent posts on Hacker News with ~100 lines of Python](https://dev.to/prospy/find-buying-intent-posts-on-hacker-news-with-100-lines-of-python-bj) (dev.to)

If you'd rather not run this yourself, [Prospy](https://prospy.io) does social listening and AI lead generation across X/Twitter, Reddit, Bluesky and Hacker News, surfacing buying-intent posts.
