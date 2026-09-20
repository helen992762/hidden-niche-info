# Privacy Policy — ytb-hidden-gems

_Last updated: 2026-09-20_

**ytb-hidden-gems** is an internal research tool with a single user — its developer. It is not distributed, has no end users, and is not public-facing.

## What the tool accesses

- The tool uses **YouTube API Services** (YouTube Data API v3) with a server API key to read **only publicly available YouTube metadata**: video titles and statistics, channel statistics, playlist items, and the text of public top-level comments.
- The tool does **not** use OAuth and therefore never requests, accesses, or stores any Authorized Data or private user data.

### Public comments

- The tool reads the text of **public** top-level comments on public videos in order to detect questions viewers are asking about a topic. This is used only to measure how much of a topic is left unanswered.
- The commenter's display name returned by the API is **discarded immediately** and is never stored, displayed, scored, or exported. Only the comment text and its public like count are used.
- Comment text is not attributed to anyone and is not linked to any identity in any report the tool produces.

## Personal data

- The tool does **not** collect, store, process, or share any personal data. Commenter names and channel owner identities are not retained (see *Public comments* above).
- No cookies, no tracking technologies, no advertising, no analytics on any person.

## Data retention

- API responses are cached locally for a maximum of **7 days** (168-hour TTL).
- All raw API data is refreshed or deleted within **30 days**, in accordance with the YouTube API Services Developer Policies.
- Only self-computed aggregate scores (derived metrics that do not identify any person) are retained long-term.

## Data sharing

- No data is shared with any third party. All data stays on the developer's local machine.

## YouTube API Services

By using YouTube API Services, this tool is bound by the [YouTube Terms of Service](https://www.youtube.com/t/terms) and the [Google Privacy Policy](https://policies.google.com/privacy).

## Contact

doxuankinh@gmail.com
