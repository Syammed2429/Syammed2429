# Daily Commit Bot

This directory contains files managed by the daily commit bot to maintain consistent GitHub activity.

## Files:
- `workflows/daily-commit.yml` - GitHub Actions workflow that runs daily
- `last-activity.txt` - Timestamp of last automated commit
- `commit-count.txt` - Counter of automated commits

## How it works:
The GitHub Action runs daily at 12:00 UTC and makes a small commit by updating the activity tracking files. This helps maintain a green contribution graph on GitHub.

## Configuration:
You can modify the schedule in the workflow file by changing the cron expression in `daily-commit.yml`.