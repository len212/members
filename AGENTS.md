# Repository Guidelines

## Project Structure & Module Organization

The repository is currently an empty scaffold: no source, test, or asset directories are present. As the project grows, keep application code in a clearly named source directory (for example, `src/`), tests in `tests/` or alongside the modules they cover, and static assets in an `assets/` directory. Keep related modules together and document any top-level layout changes here.

## Build, Test, and Development Commands

No build system or development commands are configured yet. When adding one, provide reproducible commands in the project README and keep this guide in sync. Prefer standard project entry points such as `make`, package scripts, or the language's normal toolchain; run the relevant build and test commands before submitting changes.

## Coding Style & Naming Conventions

No formatter, linter, or language convention is established yet. Follow the conventions of the language and framework introduced by the project, and configure automated formatting or lint checks when practical. Use descriptive, consistent names; reserve uppercase names for constants where the language convention supports it. Avoid unrelated formatting changes.

## Testing Guidelines

There is no test framework or test suite yet. Add tests with new behavior and bug fixes, use the framework's conventional test naming pattern, and document how to run the suite. Keep tests deterministic and focused on observable behavior.

## Commit & Pull Request Guidelines

Git history is not available in this workspace, so no repository-specific commit convention can be inferred. Use short, imperative commit subjects (for example, `Add account settings page`) unless project history establishes another format. Pull requests should explain the change and motivation, link related issues when applicable, and include screenshots for user-facing visual changes. Note tests and checks performed.

## Security & Configuration

Do not commit credentials, tokens, or local environment files containing secrets. Provide safe example configuration with placeholders and document required environment variables as the project adds them.
