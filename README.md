# Auto Commit Bot

This repository uses GitHub Actions to automatically make a commit with a random message every 5 minutes.

## How It Works

- GitHub Actions workflow runs every 5 minutes
- A script fetches a random commit message from [whatthecommit.com](https://whatthecommit.com)
- The workflow automatically appends the timestamp and commit message to a log file
- The repository maintains a history of all automatic commits

## Features

- Completely automated - no manual intervention needed
- Unique and often humorous commit messages from whatthecommit.com
- Historical record of all commits is preserved in commit-log.txt
- Easily customizable schedule (currently set to every 5 minutes)
- Minimal resource usage

## Monitoring Activity

You can monitor the activity of this bot by:
1. Checking the commit history of this repository
2. Viewing the Actions tab in GitHub to see the workflow runs
3. Looking at the commit-log.txt file for the complete history of updates

## Purpose

This project demonstrates GitHub Actions' scheduling capabilities and automated git operations.

## Customization

You can customize this bot by editing the `.github/workflows/auto-commit.yml` file:
- Change the schedule by modifying the cron expression
- Change the source of commit messages (currently using whatthecommit.com)
- Modify what content gets updated in each commit