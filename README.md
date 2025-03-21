# Auto Commit Bot

This repository uses GitHub Actions to automatically make a commit with a random message every 5 minutes.

## How It Works

- GitHub Actions workflow runs every 5 minutes
- A script generates a random message from a predefined list
- The workflow automatically commits the changes to a file
- The repository maintains a history of automatic commits

## Features

- Completely automated - no manual intervention needed
- Various random commit messages for more realistic commit history
- Easily customizable schedule (currently set to every 5 minutes)
- Minimal resource usage

## Monitoring Activity

You can monitor the activity of this bot by:
1. Checking the commit history of this repository
2. Viewing the Actions tab in GitHub to see the workflow runs
3. Looking at the commit-log.txt file for the latest update

## Purpose

This project demonstrates GitHub Actions' scheduling capabilities and automated git operations.

## Customization

You can customize this bot by editing the `.github/workflows/auto-commit.yml` file:
- Change the schedule by modifying the cron expression
- Add more random messages to the array
- Modify what content gets updated in each commit