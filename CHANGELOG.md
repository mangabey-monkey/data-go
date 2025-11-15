# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

This changelog is automatically generated during releases based on git history and changes.

## [0.2.13] - 2025-11-15

### Added

- Implemented a new AI-assisted workflow for reviewing and suggesting changelog entries based on Pull Request changes.
- Enhanced CI workflows with version comparison and explicit version bump outputs.

### Changed

- Replaced the fully automated changelog generation process with an AI-powered PR review suggestion model.
- Updated conditions for AI review and general changelog review within CI workflows.

### Fixed

- Improved JSON validation, extraction, and error handling across CI workflows, particularly `check-npm-version` and `review-changelog`.
- Enhanced API key validation and handling (`GEMINI_API_KEY`) in changelog and CI workflows.
- Updated the Gemini model version used in the changelog workflow.
- Addressed various minor issues in workflow logic and messaging.

## [0.2.12] - 2025-11-15

### Removed

- Remove `CHANGELOG.md` in favor of automated changelog management.

### Changed

- Automate changelog updates as part of the release process.
