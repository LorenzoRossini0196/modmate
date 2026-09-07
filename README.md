# modmate

Discord utility bot for my study group server

## What it does

- Graceful shutdown flushing state to disk
- Rate-limit friendly: single task loop
- Slash commands via discord.py app_commands
- Recurring reminders stored in a JSON file

## Examples

```bash
python bot.py
# then /remind 10m stretch and /quote in your server
```

## Getting started

```bash
pip install -r requirements.txt
cp .env.example .env  # put your token in .env
```

## Project structure

```text
├── docs/
│   ├── development.md
│   └── usage.md
├── .env.example
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── bot.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT licensed, see LICENSE.
