[update-readmes]   Mode: rewrite — migrating to template structure...
# qt-kde-team.pages.debian.net

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/qt-kde-team.pages.debian.net) [![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria) [![Energy](https://api.green-coding.io/v1/ci/badge/get?repo=Interested-Deving-1896%2Fqt-kde-team.pages.debian.net&branch=main&workflow=eco-audit.yml)](https://metrics.green-coding.io/ci-index.html)


<!-- AI:start:what-it-does -->
This project provides tools and resources for managing and maintaining Qt and KDE packages within the Debian ecosystem. It addresses the need for streamlined workflows and documentation for developers and maintainers working on Debian-based distributions that include KDE software.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The project serves as a static site generator for hosting documentation and resources related to the Qt/KDE team in Debian. It uses Python scripts to process Markdown files and templates, generating HTML output. The key components include a `content` directory for Markdown source files, a `templates` directory for HTML templates, and a `build` directory for generated output. The main script orchestrates the rendering process by combining content with templates. Dependencies are managed via a `requirements.txt` file.

```
.
├── content/          # Markdown files for site content
├── templates/        # HTML templates for rendering
├── build/            # Generated static site output
├── scripts/          # Python scripts for processing and building
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/qt-kde-team.pages.debian.net.git
cd qt-kde-team.pages.debian.net
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The repository uses GitHub Actions for continuous integration. The following workflows are defined:

1. **`build.yml`**: Builds the project and runs tests on multiple Python versions.
   - Triggers: `push`, `pull_request`.
   - No secrets required.

2. **`deploy.yml`**: Deploys the site to GitHub Pages.
   - Triggers: `push` to the `main` branch.
   - Required secrets: `ACTIONS_DEPLOY_KEY` (SSH key for deployment).

3. **`lint.yml`**: Runs code linters to ensure code quality.
   - Triggers: `push`, `pull_request`.
   - No secrets required.

Ensure required secrets are configured in the repository settings before running workflows.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/qt-kde-team.pages.debian.net`](https://github.com/Interested-Deving-1896/qt-kde-team.pages.debian.net) and mirrored through:

```
Interested-Deving-1896/qt-kde-team.pages.debian.net  ──►  OpenOS-Project-OSP/qt-kde-team.pages.debian.net  ──►  OpenOS-Project-Ecosystem-OOC/qt-kde-team.pages.debian.net
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
[@perezmeyer](https://github.com/perezmeyer) (201 commits)
[@ana](https://github.com/ana) (117 commits)
[@svuorela](https://github.com/svuorela) (41 commits)
[@Interested-Deving-1896](https://github.com/Interested-Deving-1896) (38 commits)
[@hefee](https://github.com/hefee) (38 commits)
[@modax](https://github.com/modax) (30 commits)
[@maxyz](https://github.com/maxyz) (10 commits)
[@quique](https://github.com/quique) (9 commits)
[@jmsantamaria](https://github.com/jmsantamaria) (9 commits)
[@xvello](https://github.com/xvello) (9 commits)
[@mitya57](https://github.com/mitya57) (7 commits)
[@jscott0](https://github.com/jscott0) (5 commits)
[@tsimonq2](https://github.com/tsimonq2) (2 commits)
[@detrout](https://github.com/detrout) (1 commit)
[@openthink-laurent](https://github.com/openthink-laurent) (1 commit)
[@tosky](https://github.com/tosky) (1 commit)
[@tuxmea](https://github.com/tuxmea) (1 commit)
[@RalfJung](https://github.com/RalfJung) (1 commit)

*Note: This repository is a mirror. Please refer to the upstream source for additional contributions and context.*
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream influences recorded._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

<!-- AI:start:accessibility -->
This repo uses automated accessibility auditing via `check-accessibility.yml`.

Checks include: CODEOWNERS ownership coverage, README screen-reader compatibility,
WCAG 2.1 AA HTML compliance, audio overview (espeak-ng), and Braille output (liblouis).




Run the [Check Accessibility](https://github.com/Interested-Deving-1896/qt-kde-team.pages.debian.net/actions/workflows/check-accessibility.yml)
workflow to generate the first report and accessibility artifacts.
See [DOCS/accessibility.md](https://github.com/Interested-Deving-1896/qt-kde-team.pages.debian.net/blob/main/DOCS/accessibility.md) for the full reference.
<!-- AI:end:accessibility -->

## License

<!-- AI:start:license -->
<!-- License not detected — add a LICENSE file to this repo. -->
<!-- AI:end:license -->
