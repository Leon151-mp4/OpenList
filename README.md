# OpenList

A minimal command-line task manager written in Python.

OpenList is designed to help users create and manage independent task lists directly from the terminal, with a simple interface and local JSON storage.

## Planned features

- Create independent task lists.
- Open an existing task list.
- List available task lists.
- Add, display, complete, and remove tasks.
- Store lists locally as JSON files.

## Planned commands

```bash
openlist --create studies
openlist --open studies.json
openlist --list
openlist --help
```

These commands describe the planned interface and may change during development.

## Data directory

OpenList will use a directory in the user's home folder:

```text
~/.openlist/
└── lists/
```

Each task list will be stored as an independent JSON file inside `lists/`.

## Technology

- Python
- `argparse` for command-line argument parsing
- JSON for local data storage

The initial version aims to use only Python's standard library.

## Project status

OpenList is at the initial planning/scaffolding stage. Features are not implemented yet.

## License

A license has not been selected yet.
