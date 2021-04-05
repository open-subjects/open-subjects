# Common Validation rules

## Validation request requirements

In order to ease reviewing validation requests, ensure you match the following
requirements before applying for a review.

???+ success "Why the requirements?"

    The goal is to ease reviewing and offer your the occasion
    to conform to the Open Source standards such as documentation .

The repository you submit **must** conform to the following.

### Requirements

Proper documentation **must** be easily accessible (i.e.: [README.md][github-readme],
[mkdocs][mkdocs] or anything that is viewable and maintanable).

???+ todo "Validation requests"
    - program _should_ be able to execute the example(s)
    - program _should_ accept input given in the subject description excepted
    if adapting the format is relevant
    - program _may_ output information in other formats than specified in the subject

???+ todo "Linting"
    - Repository **must** conform to at least one community linter ([pylint][pylint],
    [tslint][tslint], [`go fmt`][gofmt]).
    - You **must** include information regarding the linting convention you use.
    - You _may_ tweak configuration in certain parts (line length up to `110 chars`),
    but try to be as close as possible to the community guidelines for your language !

???+ todo "Packaging"
    - At least one method of packaging **must** be made available.
    - You should use your language packaging method (`setup.py`, `npm`) and may
    use [Docker][docker] to explore the concept of containers !
    - Creating [OCI][oci] enables you to distribute your application easily.

???+ todo "Documentation"
    - Describe the program usage
    - Describe installation process (generate executable or install system-wide)
    - You _may_ provide additional examples
    - Listing additional features is highly encouraged !

[docker]: https://www.docker.com/docker
[github-readme]: https://guides.github.com/features/wikis/
[mkdocs]: https://www.mkdocs.org/
[pylint]: https://pylint.org/
[tslint]: https://palantir.github.io/tslint/
[gofmt]: https://blog.golang.org/gofmt
[oci]: https://opencontainers.org/
