# My Daily Digest

A personalized morning briefing workflow created by Yuval Cohen through a Handshake project activity, using ChatGPT with connected tools and AI-assisted iteration.

[View the project case study](https://my-daily-digest-case-study.grassisspiky.chatgpt.site)

## What it does

Runs at 6 AM America/Los Angeles and puts actionable student email and calendar items first, followed by UCSB weather, sourced political news, and one daily random number evaluated against 25 pattern badges. The briefing is designed to take under three minutes to read.

## Repository contents

- `workflow.md`: reusable instructions recovered from the current scheduled task. The student email is replaced with `YOUR_STUDENT_EMAIL`; dated draw history is omitted.
- `schedule.ics`: daily schedule definition.

## Setup

Install and authorize the required Gmail, Google Calendar, Tomorrow.io Weather, and Real Random connections in ChatGPT. Replace `YOUR_STUDENT_EMAIL` with your verified self address in your private task configuration. Create a scheduled task using `workflow.md`, with a daily 6 AM schedule in America/Los_Angeles. News retrieval requires web access.

This repository documents a ChatGPT scheduled workflow. It is not a standalone application, and GitHub does not run the digest. Personal email, calendar contents, credentials, and generated daily briefings are excluded.

## Behavior and boundaries

The workflow uses read-only connected-source access except for one explicitly authorized self-notification email. Suggested calendar additions require the user's click and confirmation. It discloses unavailable sources, avoids duplicate notification emails, and reuses each day's existing random draw on retries. All 25 badge predicates and their populations must be checked before scoring.

## Review

Check a generated briefing for source links, local-date scheduling, temperature units, all 25 badge checks, and absence of duplicate random draws or notifications. The recovered instructions were inspected for this repository; no new scheduled run was executed during packaging.
