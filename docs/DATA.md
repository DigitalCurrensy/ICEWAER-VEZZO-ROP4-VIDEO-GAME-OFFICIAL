# Scores, ranks, and storage

Honest data notes for the ROP 4 game. No invented backend.

## What exists today

| Thing | Where it lives |
|---|---|
| Playable game | Higgsfield host `blue-cloud-787` |
| Rank card | Generated at the end of a run in that host |
| Leaderboard UI | Title-menu button on the live Higgsfield build |
| Campaign site | Static HTML on Vercel (`richoffpints.com`) |
| This repo | Docs and media only |

## What does not exist in these GitHub repos

- A database you can clone and run
- An API key or score endpoint in git
- Soundtrack masters
- Engine source

The campaign website has **no forms, no email capture, no analytics endpoint, and no leaderboard API**. Scores are not written by `index.html`.

## Rank card

The shareable record of a run is the end-of-run rank card. Share it with `#ROP4`.

If Higgsfield exposes a public leaderboard in the game shell, that board is owned by the live build, not by this repository.

## If you add a real score store later

Keep it out of the static site repo. Do not put tokens in git. Fail closed if the store is missing. Document the contract here before shipping it.
