# copilot-yolo

copilot-yolo is a Bash script for running GitHub Copilot with full permissions inside a stock Ubuntu container. It provides options for enabling network access, selecting the Copilot model, skipping backups, and controlling access to the `.git` directory. The project includes shell autocompletion and is licensed under the GNU Affero General Public License v3.

## Features

- Run Copilot in a secure, isolated Ubuntu container
- Options: `--enable-network`, `--model`, `--skip-backup`, `--allow-git`
- Automatic backup of your project directory (unless skipped)
- Smart handling of `.git` directory permissions
- Bash completion for all options and model names

## Files

- `copilot-yolo`: Main Bash script
- `copilot-yolo.bash-completion`: Bash completion script
- `AGENTS.md`: Contribution and option documentation
- `LICENSE`: GNU Affero General Public License v3

## Usage

```bash
./copilot-yolo [--enable-network] [--model MODEL] [--skip-backup] [--allow-git] [<prompt>]
```

Run with `--help` for details on all options.
