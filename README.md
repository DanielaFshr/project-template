# Hack Apertus — project template

Template repository for [Hack Apertus](https://hackapertus.ch/) submissions.
Every project keeps almost the same layout, so organizers and judges find the
same things in the same place.

## Select your track

This repository holds one example project per track:

- `track_1a/`
- `track_1b/`
- `track_2a/`
- `track_2b/`

Take the one for the track you are competing in and use it as the template for
your project. **Rename it to whatever your project is called** — the name is
yours, the structure is not. Keep the files and directories as shown below.

## The structure

| Path | What it is |
| --- | --- |
| `README.md` | Your project write-up — fill in every section |
| `technical_report.md` | The deeper write-up: architecture, evaluation, limitations |
| `Makefile` | `make run` must spin up your project |
| `src/` | Your code |
| `data/` | Datasets — `track_2a` and `track_2b` only; its contents stay out of git |
| `docs/` | Diagrams, notes, longer write-ups |

Everything data related goes inside `data/` — the datasets, fixtures, samples
and evaluation sets that make sense for your challenge. Keep large or
non-redistributable files out of git (see `.gitignore`) and say in
`technical_report.md` where they came from.

`make run` has to spin up your project from its root:

```bash
cd my-project   # your renamed copy of the track directory
make run
```

## Getting started

1. Click **Use this template** to create your own repository.
2. Take the directory for your track and rename it to your project.
3. Fill in its `README.md` and `technical_report.md`.
4. Make `make run` work from its root, on a clean checkout.

## License

Apache-2.0 — see [LICENSE](LICENSE). All Hack Apertus projects are open-sourced.
