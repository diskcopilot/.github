# DiskCopilot — AI-Powered Disk Cleanup for macOS

DiskCopilot helps you find large files, remove junk, and free up disk space on your Mac. Scan your entire drive in seconds, analyze storage usage with SQL queries, and clean up safely — all from the terminal or through an AI agent.

## Projects

- **[diskcopilot-cli](https://github.com/diskcopilot/diskcopilot-cli)** — Fast macOS disk scanner that caches filesystem metadata in SQLite for instant queries. Scans a full drive in ~17 seconds.
- **[diskcopilot-skills](https://github.com/diskcopilot/diskcopilot-skills)** — AI agent plugin for [Claude Code](https://claude.ai/code), Cursor, GitHub Copilot, Windsurf, and Gemini CLI. Ask questions about your disk in plain English.

## What It Does

- Scan disk usage and find what's taking up space
- Identify and clean up dev artifacts (node_modules, target/, DerivedData)
- Find large, old, or duplicate files
- Remove macOS system junk (caches, logs, old downloads)
- Get a full disk health report with cleanup recommendations

Learn more at [diskcopilot.com](https://diskcopilot.com)
