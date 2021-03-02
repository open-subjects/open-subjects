# subject template

## Install cookiecutter

Template is rendered using [cookiecutter](https://cookiecutter.readthedocs.io/).

```console
$ pip install cookiecutter
cookiecutter --help
Usage: cookiecutter [OPTIONS] TEMPLATE [EXTRA_CONTEXT]...

  Create a project from a Cookiecutter project template (TEMPLATE).

  Cookiecutter is free and open source software, developed and managed by
  volunteers. If you would like to help out or fund the project, please get
  in touch at https://github.com/audreyr/cookiecutter.
```

## Bootstrap your subject

Create a template using the `cookiecutter` command with the `template/`
directory as the `TEMPLATE`.

```console
$ cookiecutter template/
subject_name [Subject name]: my subject
$ ls
my-subject
```
