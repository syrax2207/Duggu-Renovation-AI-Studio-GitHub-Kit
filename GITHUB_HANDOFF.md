# GitHub Handoff Guide

## Suggested repository
`duggu-renovation-concept`. Keep it private while this is an unapproved concept.

## Before pushing
- Remove `.env` files and secrets.
- Never commit API keys, passwords, tokens, customer data, or credentials.
- Do not add unapproved Google Maps photos/reviews as public assets.
- Keep only assets you have rights to use.
- Include a `.gitignore`.

## Suggested commits
1. `docs: add prototype planning kit`
2. `feat: implement responsive concept website`
3. `fix: address QA and accessibility issues`

## Local test
After AI Studio generates source code, use the package manager matching the existing lockfile:
- `npm install` if npm is appropriate and dependencies are not installed.
- `npm run dev` to preview locally.
- `npm run build` to test production build.

Do not delete a lockfile or change package managers without a reason.

## Publishing
Do not deploy publicly or make the site appear official until the owner approves the project, content, and assets. Clearly label any shared preview as a private concept.
