# AGENTS.md

## Adding New Options

When introducing new options to copilot-yolo:
- Update the help dialog in `copilot-yolo` to document the new options.
- Add the new options to the completions list in `copilot-yolo.bash-completion` for shell autocompletion support.

## Existing Files
- LICENSE: Contains the GNU Affero General Public License v3.
- copilot-yolo: Main bash script for running copilot in a container, with option parsing and help dialog.
- copilot-yolo.bash-completion: Bash completion script listing available options for copilot-yolo.
