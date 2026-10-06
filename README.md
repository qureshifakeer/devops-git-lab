Day 22 Git Fundamentals

# Git & Version Control Day 1: Foundations & Core Workflow

A foundational walkthrough of Git configuration, local repository initialization, tracking lifecycle states, committing changes, and inspecting commit histories.

## Core Concepts & Essential Commands

### 1. Global Environment Setup
* **`git config --global --list`**: Audits active global Git configurations, user credentials (`user.name`, `user.email`), and default preferences across the environment.

### 2. Repository Initialization & Tracking Lifecycle
* **`git init`**: Initializes an empty Git repository by generating the internal `.git/` metadata directory.
* **`git status`**: Inspects working tree states, distinguishing untracked files, modified files, and staged changes.
* **`git add <file>`**: Stages modified or new untracked files into the Git index preparing them for snapshotting.

### 3. Committing & History Inspection
* **`git commit -m "<message>"`**: Creates an immutable snapshot of staged changes along with a concise commit message.
* **`git log`**: Displays the full commit history, author metadata, timestamps, and full SHA-1 commit hashes.
* **`git log --oneline`**: Produces a compact, single-line output featuring shortened commit hashes and descriptions for rapid audit.
* **`git show <commit-id>`**: Inspects individual commit details, showing metadata and exact line-by-line file diffs (`+` and `-`).

---
*All command outputs, staging experiments, and commit logs are documented in this repository.*
