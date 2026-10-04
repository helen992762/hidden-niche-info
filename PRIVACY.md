# Privacy Policy — ytb-hidden-gems

_Last updated: 2026-10-04_

**ytb-hidden-gems** is an internal research tool with a single user — its developer. It is not distributed, has no end users, and is not public-facing.

## What the tool accesses

- The tool uses **YouTube API Services** (YouTube Data API v3) with a server API key to read **only publicly available YouTube metadata**: video titles and statistics, channel statistics, playlist items, and the text of public top-level comments.
- For YouTube, the tool does **not** use OAuth and therefore never requests, accesses, or stores any YouTube Authorized Data or private user data.

### Google Ads API (Keyword Planner)

- The tool calls the **Google Ads API** Keyword Planner services to read aggregate, anonymous keyword statistics (average monthly searches, competition level, bid ranges) for topic keywords the developer enters.
- Access uses OAuth 2.0 with scope `https://www.googleapis.com/auth/adwords`, granted only by the developer for **their own** Google Ads account. No other user ever signs in. The resulting refresh token is stored only on the developer's local machine and is never shared.
- The tool is **read-only**: it never creates, modifies, or deletes campaigns, budgets, or any other Google Ads data, and never reads billing or account-owner information.
- Keyword statistics are aggregate market data and contain no personal data. They are cached locally for up to **30 days** and then deleted.
- The use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

### Public comments

- The tool reads the text of **public** top-level comments on public videos in order to detect questions viewers are asking about a topic. This is used only to measure how much of a topic is left unanswered.
- The commenter's display name returned by the API is **discarded immediately** and is never stored, displayed, scored, or exported. Only the comment text is used, to count how many comments are questions and which terms recur across at least three different questions. Reports never quote a comment.
- Comment text is not attributed to anyone and is not linked to any identity in any report the tool produces.

## Personal data

- The tool does **not** collect, store, process, or share any personal data. Commenter names and channel owner identities are not retained (see *Public comments* above).
- Public channel titles appear in the local reports only as attribution next to a video or channel statistic, each linked back to YouTube. No other information about channel owners is collected.
- No cookies, no tracking technologies, no advertising, no analytics on any person.

## Data retention

- YouTube API responses are cached locally for a maximum of **7 days** (168-hour TTL). Google Ads Keyword Planner responses are cached for a maximum of **30 days**.
- All raw API data is refreshed or deleted within **30 days**, in accordance with the YouTube API Services Developer Policies.
- Only self-computed aggregate scores (derived metrics that do not identify any person) are retained long-term.

## Data sharing

- No data is shared with any third party. All data stays on the developer's local machine.
- The developer can revoke the tool's Google Ads access at any time at https://myaccount.google.com/permissions, after which the local refresh token stops working.

## YouTube API Services

By using YouTube API Services, this tool is bound by the [YouTube Terms of Service](https://www.youtube.com/t/terms) and the [Google Privacy Policy](https://policies.google.com/privacy).

## Contact

doxuankinh@gmail.com
