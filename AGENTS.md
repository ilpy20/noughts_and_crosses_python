# Repository Guidelines

## Project Structure & Module Organization
- `nought_and_crosses_python/` contains the Tkinter GUI and image assets.
- `nought_and_crosses_python/noughts_and_crosses_gui.py` is the main entry point.
- `nought_and_crosses_python/*.png` holds the UI images used for the board and players.
- `README.md` provides a brief project overview.

## Build, Test, and Development Commands
- `python nought_and_crosses_python/noughts_and_crosses_gui.py`: runs the game locally.
- No separate build step is required; Tkinter ships with standard Python installs.

## Coding Style & Naming Conventions
- Indentation: 4 spaces (Python standard).
- Naming: classes in `CamelCase` (e.g., `NoughtsAndCrosses`), functions and variables in `snake_case`.
- Keep UI strings short and consistent (e.g., “Player 1 your turn”).
- No formatter or linter is configured; keep changes small and readable.

## Testing Guidelines
- There are no automated tests or test framework configured.
- If you add tests, prefer `pytest` and place them in a new `tests/` folder with `test_*.py` names.
- For UI changes, include a short manual test note (e.g., “clicked all squares; win/draw states displayed”).

## Commit & Pull Request Guidelines
- The Git history does not show a commit message convention. Use short, present‑tense summaries (e.g., “Fix win detection”).
- PRs should include:
  - A concise description of the change and why it’s needed.
  - Screenshots or a short screen recording for UI changes.
  - Any manual test steps or notes.

## Assets & Configuration Notes
- Image file names are referenced in code; keep them in `nought_and_crosses_python/` and update `PICS` if you rename or add assets.
- Avoid absolute paths in code to keep the app portable.
