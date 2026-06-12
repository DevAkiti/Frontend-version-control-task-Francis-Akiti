Frontend Version Control Task

This repository contains the completed Frontend Version Control deliverable. It showcases basic Git version control workflows, branching strategy, and successful pull request collaboration.

Branching Structure & Purpose

This project utilizes isolated feature branches before merging them back to the stable main branch:
.

🛠️ Frequently Used Git Commands

These are the primary Git commands utilized during the setup, development, and merging phases of this task:

# Repository Initialization
git init
git remote add origin <repository-url>


# Branch Management & Navigation
git checkout -b feature-header
git checkout -b feature-main-content
git checkout main

# Tracking & Committing Changes
git add .
git commit -m "feat: add styling to body and header child elements"
git commit -m "feat: add Javascricpt - array functions"

# Syncing with Remote Repository
git push origin feature-header
git push origin feature-main-content
git pull origin main

Pull Request & Merging Process

Feature Isolation: Independent tasks were split into separate developer tracks (feature-header and feature-footer) to keep changes clean.

Pull Requests: Individual Pull Requests (PRs) were opened from each feature branch to merge into main.

Review & Merge: Code integrations were peer-reviewed for conflicts, verified, and successfully merged to consolidate the project structure.

Lessons Learned

Feature Isolation: Keeping development off the main branch ensures the production environment remains safe and functional while new code is drafted.

Clear Commit History: Using descriptive, concise commit messages makes it easy to track changes back through the project timeline.

Collaborative Reviews: Code reviews in Pull Requests are essential for spotting potential styling conflicts or overlapping layouts before they make it to production.
