# Golf POC - Best Practices

This document outlines the best practices for branch-naming, commit messages, and other Git-related workflows for the Golf POC project.

## Table of Contents

- [Branch Naming](#branch-naming)
- [Commit Messages](#commit-messages)
- [Pull Requests](#pull-requests)
- [General Guidelines](#general-guidelines)

## Branch Naming

Consistent branch naming conventions making it easier to understand and manage the workflow.

If possible, always use lowercase characters when naming branches.

Use the following guidelines:

### Feature branches

- **Naming Convention:** `feature/{module}/{short-description}`
- **Example:** `feature/golf-portal-admin/login-button`

### Fix / Bug fix branches

- **Naming Convention:** `fix/{module}/{short-description}`
- **Example:** `fix/golf-portal-server/createTournamentAPI-fix-error`

### Other branches
- **Chore Branches:** `chore/{module}/{short-description}`
    - **Example:** `chore/golf-portal/update-dependencies`
- **Refactor Branches:** `refactor/{module}/{short-description}`
    - **Example:** `refactor/golf-portal-server/auth-module`

## Commit Messages

Clear and concise commit messages so other developers can easily understand the changes you have committed.

**Some examples of concise commit messages:**
- implement user CRUD endpoints
- add JWT-based authentication
- migration of mui library from v4 to v5

## Pull Requests

When creating a pull request (PR), follow these guidelines to ensure a smooth review process:

- Title - [{module}] - {short-title}
- Ticket/s
- Description
- Screenshots (if possible)
- Issues / Notes

**Example:**
Title: [golf-portal-server] JWT-based Authentication Implementation
Ticket/s: [Trello Ticket](link-from-trello-ticket)
Description: 
- Adds JWT-based authentication to the golf-portal-server.
- Updated user model.

Screenshot/s (if possible)
- insert screenshot if possible

Issues / Notes
- issues with the mui library still persists, to be fixed in the future PR.

## General Guidelines


This `README.md` provides a comprehensive guide to best practices for branch naming, commit messages, pull requests, code reviews, and version control within the project.
