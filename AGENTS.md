# Repository Guidelines

## Project Structure & Module Organization

This repository powers the public GitHub profile for `MSIChowdhury`. Treat visible changes as portfolio content: professional, current, and visually polished.

- `README.md`: the main profile page shown on GitHub.
- `AGENTS.md`: contributor and agent guidance for repository maintenance.
- Root-level documents, such as a CV, belong here only when intentionally linked.
- Put future images, banners, and icons in `assets/`.

There is no application source tree, package manifest, or test directory. If demos are added later, place them under `src/` with notes in `README.md`.

## Build, Test, and Development Commands

No build system is configured. Use lightweight checks before publishing:

- `git status --short`: inspect changed and untracked files before editing or committing.
- `git diff -- README.md AGENTS.md`: review Markdown changes.
- `npx markdownlint-cli2 "**/*.md"`: optionally lint Markdown if Node.js is available.

Preview `README.md` on GitHub or in a Markdown viewer to verify layout, links, and image sizing.

## Coding Style & Naming Conventions

Write Markdown that scans quickly. Use clear headings, short paragraphs, compact bullets, and a confident professional tone. Highlight identity, technical focus, featured work, skills, contact links, and selected achievements.

Use relative links, for example `[CV](./sameer-cv.pdf)`. Name new assets with lowercase kebab-case, such as `assets/profile-banner.png`, `assets/project-preview.png`, or `sameer-cv.pdf`.

Avoid broken badges, oversized generated sections, private local paths, and decorative content that does not strengthen the profile.

## Profile Content Guidelines

Keep the README current and intentional. Prioritize real projects, measurable impact, technologies used, and direct links to work. Tasteful visuals, GitHub stats, badges, and a banner are welcome when they support the main story.

## Testing Guidelines

There is no automated test suite. Validate changes by checking Markdown rendering, verifying links, and confirming images or PDFs open from the repository. Check visuals in light and dark GitHub themes when possible.

## Commit & Pull Request Guidelines

The history only contains `Initial commit`, so no strict convention is established. Use concise, imperative commit messages such as `Refresh profile README`, `Add profile banner`, or `Update CV link`.

Pull requests should include a short summary, note changed public-facing links or assets, and attach screenshots when the profile layout changes visually.

## Security & Configuration Tips

Do not commit secrets, private contact data, credentials, or documents not intended for public viewing. Before adding PDFs or images, confirm metadata and file contents are safe to publish.
