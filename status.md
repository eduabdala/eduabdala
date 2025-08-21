# Project Status Badges - Standards

This README documents the standard usage of **status badges** for projects in my profile. They are used to quickly indicate the current state of a project, helping collaborators and visitors understand its maturity or availability.

---

## Project Status

To indicate the **current state of the project**, we use generic badges from [Shields.io](https://shields.io/). Below are the possible states with recommended default colors:

| Status               | Badge Markdown                                                                                   | Suggested Color | Description                                                                | Example |
|----------------------|--------------------------------------------------------------------------------------------------|----------------|----------------------------------------------------------------------------|---------|
| Ready                | `![Project Status](https://img.shields.io/badge/status-ready-brightgreen)`                      | brightgreen    | Project is complete and stable.                                           | ![Project Status](https://img.shields.io/badge/status-ready-brightgreen) |
| In Development       | `![Project Status](https://img.shields.io/badge/status-in%20development-yellow)`               | yellow         | Project is active and still evolving.                                      | ![Project Status](https://img.shields.io/badge/status-in%20development-yellow) |
| Paused               | `![Project Status](https://img.shields.io/badge/status-paused-orange)`                           | orange         | Development is temporarily suspended.                                      | ![Project Status](https://img.shields.io/badge/status-paused-orange) |
| Stopped              | `![Project Status](https://img.shields.io/badge/status-stopped-red)`                             | red            | Project is halted, no updates planned soon.                                | ![Project Status](https://img.shields.io/badge/status-stopped-red) |
| Deprecated           | `![Project Status](https://img.shields.io/badge/status-deprecated-lightgrey)`                   | lightgrey      | Project is officially discontinued or no longer maintained.                | ![Project Status](https://img.shields.io/badge/status-deprecated-lightgrey) |

---

## Other Useful Badges

In addition to the status, it is recommended to add badges that provide important information about the project:

| Category             | Badge Markdown | Description | Example |
|----------------------|----------------|------------|---------|
| Version              | `![Version](https://img.shields.io/badge/version-1.0.0-blue)` | Current project version. | ![Version](https://img.shields.io/badge/version-1.0.0-blue) |
| License              | `![License](https://img.shields.io/badge/license-MIT-green)` | Project license type. | ![License](https://img.shields.io/badge/license-MIT-green) |
| Build / CI           | `![Build](https://img.shields.io/badge/build-passing-brightgreen)` | Build status on GitHub Actions or other CI. | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| Test Coverage        | `![Coverage](https://img.shields.io/codecov/c/github/user/repo)` | Percentage of test coverage. | ![Coverage](https://img.shields.io/codecov/c/github/user/repo) |
| Dependencies         | `![Dependencies](https://img.shields.io/librariesio/github/user/repo)` | Project dependency status. | ![Dependencies](https://img.shields.io/librariesio/github/user/repo) |
| Open Issues          | `![Issues](https://img.shields.io/github/issues/user/repo)` | Number of open issues on GitHub. | ![Issues](https://img.shields.io/github/issues/user/repo) |
| Pull Requests        | `![PRs](https://img.shields.io/github/issues-pr/user/repo)` | Number of open PRs. | ![PRs](https://img.shields.io/github/issues-pr/user/repo) |
| Contributors         | `![Contributors](https://img.shields.io/github/contributors/user/repo)` | Number of active contributors. | ![Contributors](https://img.shields.io/github/contributors/user/repo) |
| Languages / Stack    | `![Python](https://img.shields.io/badge/python-3.12-blue)` `![Flutter](https://img.shields.io/badge/flutter-3.13-blue)` | Languages or frameworks used in the project. | ![Python](https://img.shields.io/badge/python-3.12-blue) ![Flutter](https://img.shields.io/badge/flutter-3.13-blue) |
| Popularity           | `![Stars](https://img.shields.io/github/stars/user/repo?style=social)` | GitHub stars. | ![Stars](https://img.shields.io/github/stars/user/repo?style=social) |
| Forks                | `![Forks](https://img.shields.io/github/forks/user/repo?style=social)` | Number of forks. | ![Forks](https://img.shields.io/github/forks/user/repo?style=social) |

---

## How to Use in the Project README

Badges should be placed at the **top of the README**, right below the project title, for example:

```markdown
# Project Name

![Project Status](https://img.shields.io/badge/status-in%20development-yellow)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Build](https://github.com/user/repo/actions/workflows/main.yml/badge.svg)
