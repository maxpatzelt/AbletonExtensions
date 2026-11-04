# Ableton Extensions

Personal workspace for developing extensions for Ableton Live.

## Project Layout

Add each extension as its own directory. Keep its source, project configuration,
documentation, and any distributable application assets together, with a README
that describes its specific setup and build steps.

This repository is currently a scaffold; no extension project has been added yet.

## Ableton Extensions SDK

The SDK is required for extension development. Obtain it directly from Ableton
and keep the licensed SDK files local. The SDK license prohibits redistributing
the SDK or parts of it outside an application, so the local
`extensions-sdk-1.0.0-beta.1/` directory is ignored by Git. Do not commit the
SDK archive, documentation bundle, or generated SDK site.

## Repository Rules

- Commit extension source, documentation, and project configuration.
- Keep credentials, temporary files, backups, and licensed SDK files out of Git.
- Follow the build and test instructions in each extension's own README.
- Use feature branches and normal pushes; do not rewrite shared history.
