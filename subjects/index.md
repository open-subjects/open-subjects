# Open Subjects

Open subjects is a website offering exercises to learn and train
various tech skills. Most of the subjects are oriented towards
development, yet some additional goals regarding system administration,
DevOps methodologies or infrastructure management might be involved someday!

This aims to provide a context to develop your languages knowledge and getting
some personal projects ideas.

## Quick Start

- Pick a subject
- Request your first validation !

### Validation process

Below are the steps to trigger a validation process for your delivery.

Examples are given using the [Github CLI][github-cli].

??? note "Create a public repository to push your code"
    ```bash
    gh repo create
    ```

??? note "Fork this repository"

    ```bash
    gh repo fork
    ```

??? note "Add a link to your repository in the validations list"

    ```text
    ## Validations

    - @tbobm/open-subjects-hello-world
    ```

??? note "Create a Pull Request"
    ```bash
    gh repo pr create -t "validation: Hello world - tbobm"
    ```

A standardized validation request Pull Request template is available to
facilitates reviewing the different deliveries.

## Contributing

### Generate the documentation

This website's documentation is generated using [`mkdocs`][mkdocs] with
a couple of extensions.

The complete configuration can be found in the [`mkdocs.yml`][open-subjects-mkdocs]
file.

A [requirements.txt][doc-deps] is available.

```bash
git clone https://github.com/open-subjects/open-subjects
pip install -r subjects/requirements.txt
```

The documentation can be generated using the following command:

```console
$ mkdocs build
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/bob/ghub/open-subjects/site
INFO    -  Documentation built in 0.33 seconds
```

If you'd like view the static website built locally:

```console
$ mkdocs serve
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 0.33 seconds
[I 210316 00:10:50 server:335] Serving on http://127.0.0.1:8000
```

[github-cli]: https://github.com/cli/cli/
[mkdocs]: https://www.mkdocs.org/
[open-subjects-mkdocs]: https://github.com/open-subjects/open-subjects/blob/main/mkdocs.yml
