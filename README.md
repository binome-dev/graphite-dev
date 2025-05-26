# Graphite Dev

Graphite Dev provides a local assistant runtime with visual workflow tracing. The tool must be executed from the project root directory to function properly.

## Installation

```bash
pip install grafi-dev
```

## Usage

```bash
grafi-dev <path to your assistant instance>
```

Or run from source:

```bash
python -m grafi_dev.cli <path to your assistant instance>
```

## Feature

* Run any assistant and inspect its workflow in the browser
* Live node execution and event trace
* Interactive web UI for reviewing conversations and workflow details

## Development

To start the server from source

```bash
python -m grafi_dev.cli <path to your assistant instance>
```

This launches a FastAPI server with uvicorn and opens the UI.

## Support

For questions or fixes, refer to the source code, tests, and issues.
Contributions via pull requests are welcome.