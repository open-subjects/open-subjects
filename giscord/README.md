# giscord

**Goal**: Create Bot to report github repository activity in a Discord channel.

## Features

Interactions **must** be done through `bot-commands`. You are free to chose
a common prefix for your commands, as long as it is consistant.

_The prefix '$' will be used in the example._

Every command **must** involve an output.

The bot can be deployed and hosted any way you like, as long as you package it properly.

### Administration

#### Register

Register a new repository to watch.

```text
@tbobm: $register tbobm/open-subjects
@giscord: adding https://github.com/tbobm/open-subjects to the watch list!
```

#### Unregister

Remove the repository from the watch list.

```text
@tbobm: $unregister tbobm/open-subjects
@giscord: removing https://github.com/tbobm/open-subjects from the watch list
```

### Notify

Notify modifications of the repositories in the watch list when:

- Issues or pull requests are created or closed
- New release is created (or new tag)

Example output below:

```text
@giscord: Pull request opened by tbobm
#6 chore(ci): Add github action CI
• Add Github action CI
• Fix lint errors
Reviewers
@tbobm
<https://github.com/tbobm/open-subjects/pulls/6> | Mar 22nd
```

This can be extended to:

- New commits in branch
- Interactions in commits / PRs

## Packaging

Packaging must meet the following criterias:

- Bot shall be installable as a package / executable
  - package.json
  - poetry
  - through cargo
- Documentation
  - Installation process
  - Configuration process
  - Authentification, if required

Packaging `giscord` as an OCI Image is highly encouraged.

Distribution through registries (ghcr.io) or package management (npm, pip) is encouraged.

## Additional targets

- None

## Validations

- None
