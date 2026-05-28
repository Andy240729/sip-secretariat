# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Current state

This repository is a fresh scaffold. As of this writing it contains only `README.md`
(a single title line) and no source code, dependency manifests, build configuration,
or tests. There is a single commit (`Initial commit`) on `main`.

There is therefore no build, lint, test, or run tooling to document yet. When the
first real code lands, update this file with:

- The package manager and language/runtime, and how to install dependencies.
- How to build, lint, run, and test — including how to run a single test.
- The high-level architecture (the "big picture" that spans multiple files).

Do not infer these from the repo name or environment integrations alone; document
them only once they exist in the codebase.

## Git workflow

- Do all work on the feature branch you were assigned for the task (do not commit
  directly to `main`); create the branch locally if it does not exist.
- Push with `git push -u origin <branch-name>`.
- Do not open a pull request unless explicitly asked.
