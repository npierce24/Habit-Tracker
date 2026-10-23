# Habit Tracker

A simple, mobile-friendly habit tracker for building daily routines and keeping a record of your progress. The app uses a calm blue and charcoal design and runs directly in your web browser.

## Features

- Start with a few sample habits, then add or edit habits with a name, icon, and customizable accent color; confirm before removing a habit and its check-ins.
- Track your habits in daily, weekly, or monthly views.
- Record the time and optional notes for each check-in.
- Review your check-in history in the activity log.
- See daily progress, habit streaks, and your number of habits.
- Choose a display name and receive a personal welcome.
- Get a background that changes with the time of day.
- Use the responsive layout on desktop and mobile devices.
- Download a JSON backup or restore your data from one in **Settings**.

## Getting started

This project does not require installation, an account, or a server:

1. Download or clone this project.
2. Open `index.html` in a modern web browser.
3. Add your habits and check in as you complete them.

Your browser may ask you to choose a name the first time you open the tracker. You can change it later from **Settings**.

## Your data and backups

Habits, check-ins, notes, colors, and your name are saved in the browser's local storage on the current device and remain available when you reopen `index.html` in that same browser. The app does not sync this data to an online account. Other browsers or devices have separate storage, so use **Settings → Download data backup** to save a copy you can keep or transfer.

To transfer or restore data, open the tracker on the destination device and choose **Settings → Restore from backup**, then select a Habit Tracker JSON backup. Restoring replaces the habits and name currently saved in that browser. Keep your backup file somewhere safe; clearing browser data may delete the locally saved tracker data.

## Project files

- `index.html` — the complete app, including its layout, styles, and behavior.
- `README.md` — project overview and instructions.