BSc Mathematics and Computer Science at the University of Cape Town. Cape Town, South Africa.

This account is mostly a working library rather than a portfolio — forks of projects I read. The
four below are mine, and they are the four I would want read.

## Projects

**[mzantsi-vibes](https://github.com/realtimshady16/mzantsi-vibes)** — a free guide to the years
after matric in South Africa, split into study / work / don't-know-yet / for-everyone, plus a
community submission flow: a Cloudflare Worker takes a submitted resource, opens a pull request,
and a cron job batches the review. Live at [mzantsivibes.co.za](https://mzantsivibes.co.za).
JavaScript, static front end plus a Worker, ~100 commits. Built with AI coding agents under my
direction — the working agreement for them is checked into the repo as `AGENTS.md`.

**[sa-open-data](https://github.com/realtimshady16/sa-open-data)** — preserved copies of South
African local-government datasets: municipal finance from National Treasury, AGSA audit
outcomes, IEC council composition, Stats SA free-basic-services. Captured 2026-11-09/10 while
working on local-government politics, with provenance per file, a sha256 manifest, and the
fetchers that produced them, so every byte can be reproduced. Two of the sources are not
preserved anywhere else. Archived on Zenodo (DOI 10.5281/zenodo.24241806); MIT code, CC BY 4.0
data. Python.

**[bible-cli](https://github.com/realtimshady16/bible-cli)** — an offline Bible for the
terminal. WEB and KJV in SQLite with FTS5: verse, chapter and range lookup, ranked search, an
fzf picker, `--json` for scripts and agents, and a small Neovim wrapper. No scripture text ships
in the repo — `build.py` fetches the public-domain sources and builds a local database. Python,
MIT.

**[realtimshady16.github.io](https://github.com/realtimshady16/realtimshady16.github.io)** — two
browser-based tools with no server behind them: a document signing tool and a PDF merger. HTML
and JavaScript.

## Now

- **Finishing the degree.** A failed metric spaces course means a retake, which puts completion
  in 2027 or later rather than this year. That is the whole of my current constraint.
- **Building an education-data spine, not yet published.** The EMIS school register (every South
  African school, quarterly from 2013) joined to thirteen years of NSC per-school results,
  2012–2024. The missing layer is an external benchmark — TIMSS or SACMEQ — before it is worth
  anyone's time.
- **Mzantsi Vibes is live and moving slowly.** The open work is content and policy, not code.
- **Reading other people's systems.** Browser automation, agent harnesses, a couple of local
  government data projects. That is what the forks are; none of it is upstream yet, which is a
  thing I would like to change before I call any of it contribution.

## Reach

- Site — [hellotim.co.za](https://hellotim.co.za)
- LinkedIn — [linkedin.com/in/tim-evertse](https://www.linkedin.com/in/tim-evertse/)
