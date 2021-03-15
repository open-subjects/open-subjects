# open-subjects

[![Subject lint](https://github.com/tbobm/open-subjects/workflows/open-subjects/badge.svg)](https://github.com/tbobm/open-subjects/workflows/open-subjects/)

Publicly available subject ideas to sharpen your development skills.

This repository is used to aggregate exercise ideas and the corresponding submissions.

## Submit your answer

If you want to review your code, you do the following:

- Create a public repository to push your code
- Fork this repository
- Add a link to your repository in the validation list
- Create a Pull Request

```text
## Validations

- @tbobm/open-subjects-hello-world
```

See the ["review" pull request template](./.github/PULL_REQUEST_TEMPLATE/review.md)

## Questions

Feel free to reach out using the [discussions][gh-discussions] tab !

## Issue

Found something weird / unclear / wrong / impossible to do in a subject ?

Report it through [an issue][gh-issue-new]

## Contributing

Every contribution is welcomed !

Feel free to make use the ["subject" pull request template](./.github/PULL_REQUEST_TEMPLATE/subject.md).

A [cookiecutter][cookiecutter] template is available in the [`./template`](./template/) directory.

```console
$ cookiecutter template/
subject_name [Subject name]: my subject
$ ls
my-subject
```

_cookiecutter can be installed using `pip install cookiecutter`_

## Subjects

### Icali

See [icali/README.md](./subjects/icali/README.md).

Develop a CLI program that creates icals from csv files.

### Giscord

See [giscord/README.md](./subjects/giscord/README.md).

Create a Github Discord Bot.

[cookiecutter]: https://cookiecutter.readthedocs.io/
[gh-discussions]: https://github.com/tbobm/open-subjects/discussions
[gh-issue-new]: https://github.com/tbobm/open-subjects/issues/new
