## Data for SME Virtual Network Open Source Projects

[![Build Status](https://dev.azure.com/smevirtual/OpenSourceProjectData/_apis/build/status/smevirtual.OpenSourceProjectData?branchName=master)](https://dev.azure.com/smevirtual/OpenSourceProjectData/_build/latest?definitionId=1&branchName=master)

Contains the data for [smevirtual.github.io](https://smevirtual.github.io/), a web
application that lists all of the open source projects (software or hardware) that the SME Virtual Network is currently maintaining, supporting and developing.

### Criteria for the project list

The SME Virtual Network has a number of open source projects that are maintained and developed to both enrich the broader open source community and provide educational content to the membership and the public. Most of the projects listed can also be found in the [SME Virtual Network GitHub organization](https://github.com/smevirtual).

In some cases, the SME Virtual Network will partner with commercial, research and educational organizations in supporting third-party projects. All third-party projects must be approved by the SME Virtual Network Leadership Team before they are listed.

In general, we will only list projects that conform to the following guidelines:

- Available under an [OSI-approved license](https://opensource.org/licenses).
- Industrial, manufacturing and/or engineering-related.
- Actively maintained.
- Willing to maintain a friendly/professional atmosphere for accepting contributions by novice programmers and developers.
- Supports a Code of Conduct or similar community guidelines that will resolve disputes and discourage harassment.

At this time, we will only list projects that are hosted on GitHub.

### Adding a project

To add or modify projects to the list on [smevirtual.github.io](https://smevirtual.github.io/), create a new [issue](https://github.com/smevirtual/OpenSourceProjectData/issues/new).

### Removing a project

Partners and third-parties can request the removal of their project from our list at any time. The project maintainer or any other authorized person should create a new [issue](https://github.com/smevirtual/OpenSourceProjectData/issues/new) for the request.

### Development Prerequisites

There are several prerequisites need to be installed on your development
machine prior to working with this codebase.

1.  Install Node.js version 10.0 or greater.

    See [this page](https://nodejs.org/en/download/).

    For macOS development machines, installing Node.js with [Homebrew](https://brew.sh/)
    is recommended.

2.  Install Yarn.

    See [this page](https://yarnpkg.com/en/docs/install).

### Development Quick Start

For a freshly cloned repository, run:

```bash
yarn install
```

Once all of the above prerequisites are installed, the following commands are
now available:

| Command         | Description                                                                                |
| --------------- | ------------------------------------------------------------------------------------------ |
| `yarn run test` | Validates the JSON file containing open source project data against the JSON schema for the repository. |

### Community Participation Guidelines

The SME Virtual Network is committed to providing a friendly, safe and welcoming
environment for all. Please take a moment to read our
[Community Participation Guidelines](https://github.com/smevirtual/community-guidelines/blob/master/README.md).

### License

The contents of this repository are licensed under the [MIT License](LICENSE) unless otherwise noted in the header of a specific file or within a particular source directory.
