# Security Policy

This repository hosts public static pages for Google OAuth app verification.

## Sensitive Data

Do not commit OAuth tokens, OAuth client secrets, API keys, private keys, cookies, passwords, environment files, or other credentials to this repository.

The published site must contain only public app description, privacy policy, and terms content.

## Reporting Security Issues

If you find sensitive data or a security issue in this repository, report it through GitHub so it can be removed and any affected credentials can be rotated.

## Pre-Publish Checks

Before publishing changes:

- Run `gitleaks detect --source . --redact`.
- Review changed files for OAuth tokens, client secrets, API keys, private keys, cookies, and raw environment files.
- Confirm GitHub Pages still serves only static public policy pages.
