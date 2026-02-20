# Linux Backup Automation Scripts

Shell-based backup automation using tar, at, and cron.

## Design

- Manual backup execution
- One-time scheduled backup via `at`
- Recurring scheduled backup via `cron`
- Basic input validation and error handling

## Scripts

- `bck`   — direct backup of file or directory
- `bck1`  — scheduled backup using `at`
- `bck2`  — cron-oriented recurring backup

## Usage

bash
chmod +x bck bck1 bck2

./bck user source destination
./bck1 user source destination HH:MM
./bck2

Example cron entry:
bash
0 23 * * 0 /home/username/bck2

## Stack

Bash · Linux · tar · at · cron · Automation

⸻

Panagiotis Zois
MSc ICT | Bridging Business & Technology
