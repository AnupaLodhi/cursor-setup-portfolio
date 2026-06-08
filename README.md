# Cursor Setup Portfolio

## Overview

This repository documents my setup process for Cursor IDE, Claude Code, and Codex.

## Tools Installed

* Cursor IDE
* Claude Code
* Codex CLI
* GitHub

## Steps Completed

1. Installed Cursor IDE.
2. Installed Claude Code.
3. Verified Claude Code installation using:

   * `claude update`
   * `claude --help`
4. Installed Codex.
5. Updated Codex using:

   * `codex update`
6. Logged into Codex using:

   * `codex login`
7. Verified setup using:

   * `codex doctor`
8. Created a public GitHub repository.
9. Added this README and pushed it to GitHub.

## Issues Encountered

### Issue 1: Claude Code Agent UI

The "Add New Agent → Claude Code" option in Cursor did not respond when clicked.

### Resolution

I verified Claude Code through the terminal instead. Running `claude update` and `claude --help` confirmed the installation was successful.

### Issue 2: Codex Authentication

Initially, `codex doctor` reported that no credentials were configured.

### Resolution

I authenticated using `codex login` and re-ran `codex doctor`, which confirmed that authentication was configured successfully.

## What I Learned

* Installing AI development tools
* Using terminal commands for verification
* Authenticating developer tools
* Troubleshooting setup issues
* Basic GitHub repository management
