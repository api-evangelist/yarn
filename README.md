# YARN (yarn)
YARN (Yet Another Resource Negotiator in the original Hadoop context; also the JavaScript package manager) refers here to the yarnpkg.com JavaScript package manager. Yarn is a fast, reliable, and secure dependency management tool for JavaScript. Originally developed by Meta as an alternative to npm, Yarn offers deterministic dependency resolution, offline caching, parallel installation, and Plug'n'Play (PnP) module resolution. The project is actively maintained under the yarnpkg/berry repository (Yarn 2+) with a modular plugin architecture. Yarn provides a programmatic JavaScript/TypeScript API via @yarnpkg/core for building tools and plugins.

**URL:** [Visit APIs.json URL](https://github.com/yarnpkg/berry)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - JavaScript, Node.js, Package Manager, YARN

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### YARN Core API
The @yarnpkg/core programmatic JavaScript/TypeScript API that allows applications to interact with Yarn projects, workspaces, and dependency resolution. Used for building Yarn plugins and tooling integrations.

**Human URL:** [https://yarnpkg.com/api](https://yarnpkg.com/api)

#### Tags:

 - API, JavaScript, Package Manager, Plugin, TypeScript

#### Properties

- [Documentation](https://yarnpkg.com/api)
- [APIReference](https://yarnpkg.com/api)
- [GitHubRepository](https://github.com/yarnpkg/berry)
- [GettingStarted](https://yarnpkg.com/advanced/plugin-tutorial)
- [Tutorials](https://yarnpkg.com/advanced/plugin-tutorial)

### YARN CLI
The Yarn command-line interface built on @yarnpkg/cli, providing commands for package installation, workspace management, publishing, and more. Supports a plugin system for extensibility.

**Human URL:** [https://yarnpkg.com/cli](https://yarnpkg.com/cli)

#### Tags:

 - CLI, JavaScript, Package Manager

#### Properties

- [Documentation](https://yarnpkg.com/cli)
- [APIReference](https://yarnpkg.com/cli)
- [CLI](https://yarnpkg.com/cli)
- [GettingStarted](https://yarnpkg.com/getting-started/install)

## Common Properties

- [Documentation](https://yarnpkg.com/getting-started)
- [GettingStarted](https://yarnpkg.com/getting-started/install)
- [Tutorials](https://yarnpkg.com/getting-started/usage)
- [APIReference](https://yarnpkg.com/api)
- [GitHubOrganization](https://github.com/yarnpkg)
- [GitHubRepository](https://github.com/yarnpkg/berry)
- [SDK](https://www.npmjs.com/package/yarn)
- [ChangeLog](https://github.com/yarnpkg/berry/blob/master/CHANGELOG.md)
- [BestPractices](https://yarnpkg.com/migration/guide)
- [Resources](https://yarnpkg.com/configuration/yarnrc)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/yarn/main/json-schema/yarn-package-schema.json)

## Features

| Name | Description |
|------|-------------|
| Workspaces | First-class monorepo support letting projects split into sub-components managed from a single root. |
| Plug'n'Play (PnP) | Alternative installation strategy that eliminates node_modules in favor of a single resolution map for faster, stricter installs. |
| Plugin Architecture | Modular core with 25+ default plugins and a public API for building custom workflows and integrations. |
| Offline Caching | Local cache of downloaded packages enabling reproducible installs without network access. |
| Parallel Installation | Concurrent dependency fetching and linking for faster installs versus serial package managers. |
| Deterministic Resolution | Lockfile-driven dependency resolution that produces identical installs across machines and CI runs. |
| Hardened Mode | Stricter install mode that verifies registry metadata against the lockfile to defend against supply-chain tampering. |
| Cross-platform Shell | Built-in shell interpreter so package scripts behave consistently across Linux, macOS, and Windows. |
| Constraints | Declarative rules for enforcing dependency policies and conventions across a workspace. |
| Interactive Commands | Search and upgrade UIs that let developers explore and manage dependencies interactively. |
| Programmatic API | TypeScript-first @yarnpkg/core surface for building plugins, tooling, and CI integrations. |

## Use Cases

| Name | Description |
|------|-------------|
| Monorepo Management | Coordinate dependencies, scripts, and releases across many packages in a single repository. |
| Dependency Management | Install, upgrade, and audit JavaScript and TypeScript dependencies for libraries and applications. |
| Plugin Development | Build and distribute plugins that extend the Yarn CLI with project-specific commands and behaviors. |
| Reproducible CI Builds | Use the lockfile, offline cache, and hardened mode to keep CI installs deterministic and tamper-resistant. |
| Package Publishing | Publish packages to npm and other registries via the npm-related CLI commands and release workflows. |
| Workspace Coordination | Run scripts across workspaces, share dependencies, and enforce constraints in large multi-package projects. |

## Integrations

| Name | Description |
|------|-------------|
| npm Registry | Primary package registry for installing and publishing JavaScript packages. |
| Node.js | Runtime that executes Yarn-managed packages and the Yarn CLI itself. |
| TypeScript | Yarn ships TypeScript type definitions and is itself written primarily in TypeScript. |
| Corepack | Node.js shim that pins and provisions the Yarn version per project. |
| VS Code Editor SDK | Editor SDK integration that wires Yarn PnP-managed dependencies into VS Code's TypeScript and ESLint tooling. |
| JetBrains Editor SDK | Editor SDK integration for IntelliJ-family IDEs to resolve PnP dependencies in editor tooling. |
| GitHub | Source repository, issue tracker, and release distribution for the yarnpkg organization. |
| Discord | Community chat for support, contributor coordination, and announcements. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [YARN Package Schema](json-schema/yarn-package-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
