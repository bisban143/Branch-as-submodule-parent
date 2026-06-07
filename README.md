# Branch-as-submodule-parent

Parent repository demonstrating the branch as submodule pattern.

## Overview

This repository serves as a parent repository that references other repositories' branches as Git submodules. This pattern allows for:

- Tracking specific branches from other repositories
- Managing dependencies across multiple repositories
- Testing and validating the Blitzy ingestion hypothesis with branch-based submodules

## Structure

This parent repository will contain submodules pointing to specific branches of other repositories.

## Usage

Add submodules using:
```bash
git submodule add -b <branch-name> <repository-url> <path>
```

Update submodules:
```bash
git submodule update --remote --merge
```
