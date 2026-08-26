# scorecard

Keyword-based eval runner with latency tracking

Side project, maintained when I have time.

## Highlights

- Swap in any agent function via one line
- Keyword scoring + latency per case
- Exit code usable as a CI gate
- Cases defined in plain JSON

## Install

```bash
# stdlib only, nothing to install
```

## Usage

```bash
python evals.py
# edit cases.json, point run() at your agent
```

## Project structure

```text
├── .github/
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── SECURITY.md
├── cases.json
└── evals.py
```

## Notes

- mostly stable, edge cases remain

## License

MIT licensed, see LICENSE.
