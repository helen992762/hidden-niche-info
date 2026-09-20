# ytb-hidden-gems — Internal YouTube Niche Research Tool

A personal, internal command-line research tool that helps its single user (the developer) plan their own YouTube content. It measures content supply and demand for candidate topics by reading **public** YouTube metadata through the official **YouTube Data API v3**.

## What it does

- Searches public video metadata for candidate topic keywords (`search.list`).
- Retrieves public video statistics, channel statistics, and channel uploads (`videos.list`, `channels.list`, `playlistItems.list`).
- Reads public top-level comments on those videos (`commentThreads.list`) to find questions viewers are still asking, which indicate gaps in existing content.
- Computes self-derived aggregate niche scores (supply, demand, competition).
- Outputs reports as command-line text and local markdown files.

The complete list of YouTube Data API endpoints the tool calls is exactly the five above: `search.list`, `videos.list`, `channels.list`, `playlistItems.list`, `commentThreads.list`.

## What it is NOT

- Not public-facing: no hosted service, no website, no app distribution.
- No user accounts, no sign-in, no OAuth — the tool uses a server API key and reads only public data.
- Does not collect, store, or share data about any person.

## Access

Command-line only, running locally on the developer's machine. This repository page serves as the tool's public description page for YouTube API Services compliance review.

## Privacy

See [PRIVACY.md](./PRIVACY.md).

## Contact

doxuankinh@gmail.com
