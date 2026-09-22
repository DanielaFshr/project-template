# Hack Apertus — project template

Template repository for [Hack Apertus](https://hackapertus.ch/) submissions.
Every project keeps almost the same layout, so organizers and judges find the
same things in the same place.

## Select your track

This repository has one directory per track. **Work only inside the directory
for the track you are competing in** and leave the others untouched:

- `track_1a/`
- `track_1b/`
- `track_2a/`
- `track_2b/`

## What goes in a track directory

Each one is a complete, self-contained project skeleton:

| Path | What it is |
| --- | --- |
| `README.md` | Your project write-up — fill in every section |
| `technical_report.md` | The deeper write-up: architecture, evaluation, limitations |
| `Makefile` | `make run` must spin up your project |
| `src/` | Your code |
| `docs/` | Diagrams, notes, longer write-ups |

## Getting started

1. Click **Use this template** to create your own repository.
2. Pick the directory for your track.
3. Fill in its `README.md` and `technical_report.md`.
4. Make `make run` work from a clean checkout.

## License

Apache-2.0 — see [LICENSE](LICENSE). All Hack Apertus projects are open-sourced.
