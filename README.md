# GitHub Actions MCP Server

An MCP server for interacting with GitHub Actions workflows. This server provides tools to query and monitor GitHub Actions workflow runs.

## Features

- List workflow runs with filtering options
- Get the latest workflow run
- Get failed workflow runs
- Filter by status, branch, and event type

## Installation

```bash
npm install
```

## Usage

1. Build the project:
```bash
npm run build
```

2. Start the server:
```bash
npm start
```

## Available Tools

### list-workflow-runs
Lists GitHub Actions workflow runs for a repository with filtering options.

### get-latest-workflow-run
Gets the most recent workflow run, with optional filtering by workflow ID.

### get-failed-workflow-runs
Gets a list of failed workflow runs, with configurable limit.

## Configuration

You'll need a GitHub personal access token with appropriate permissions to access private repositories.

## License

MIT