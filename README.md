# Single-Use-Apps

Home for all Claude-built web apps, hosted on Firebase (`claw-apps.web.app`).

## Structure

- Each app lives as a single self-contained HTML file in the root
- `outputs/` — persistent state JSON files used by scheduled tasks (dedup caches, etc.)

## Stack

- **Hosting:** Firebase Hosting (site: `claw-apps`) → `claw-apps.web.app`
- **Live sync:** Firestore (`claw-apps` project, `users/{uid}/` collections)
- **Source of truth:** This repo (GitHub REST API for all reads/writes in unattended tasks)
- **Deploys:** Firebase Hosting REST API — no CLI needed

## Apps

| File | Description | Live URL |
|------|-------------|----------|
| *(first app coming soon)* | | |
