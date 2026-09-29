# Run Guide

## Prerequisites
- Python 3.9 or later
- JDK 17 or later (`java` and `javac` available)
- Run commands from the repository root

## Run the demo

    python3 run.py demo

On Windows, if `python3` is not found, use `py -3 run.py demo`.

## What the demo does
The demo runs a short library loan scenario on a fixed date (2026-09-01).
It prints the loan limits for students and faculty, runs a search for "git",
lends the book "Git Essentials" to Alex with a due date of 2026-09-15,
returns it with a fee of 0, and shows that no loans remain active.
