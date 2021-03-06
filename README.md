# Democritus Dates

[![PyPI](https://img.shields.io/pypi/v/democritus-dates.svg)](https://pypi.python.org/pypi/democritus-dates)
[![Build Status](https://travis-ci.com/democritus-project/democritus-dates.svg?branch=main)](https://travis-ci.com/democritus-project/democritus-dates)
[![codecov](https://codecov.io/gh/democritus-project/democritus-dates/branch/main/graph/badge.svg?token=V0WOIXRGMM)](https://codecov.io/gh/democritus-project/democritus-dates)

Democritus functions<sup>[1]</sup> for working with and using dates and times.

[1] Democritus functions are <i>simple, effective, modular, well-tested, and well-documented</i> Python functions.

## Usage

Coming soon...

## Development

If you want to contribute to this project, make sure you have [docker][docker] and [docker-compose][docker-compose] installed (if you don't see: [installing docker][docker-install]).

Once you have docker installed, you should [fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) and [clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) the repo.

Then you can both *test* and *lint* this project using the docker-compose commands below!

### Testing

To test this project, run the following command from the root directory of the repository:

```shell
docker-compose run test
```

To see what this command does, take a look at the `test` service in the `docker-compose.yml` file.

### Linting

To lint<sup>1</sup> this project, run the following command from the root directory of the repository:

```shell
docker-compose run lint
```

To see what this command does, take a look at the `lint` service in the `docker-compose.yml` file.

### Dev

To drop into a "dev" environment which is an [IPython][ipython] shell with all of the requirements and this project loaded, run the following command from the root directory of the repository:

```shell
docker-compose run dev
```

To see what this command does, take a look at the `dev` service in the `docker-compose.yml` file.

## Credits

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter) and Floyd Hightower's [Python project template](https://github.com/fhightower-templates/python-project-template).

---

1 - You can read more about what linting is and why it is helpful [here][linting-intro]

[docker-compose]: https://docs.docker.com/compose/
[docker-install]: https://docs.docker.com/get-docker/
[docker]: https://www.docker.com/get-started
[linting-intro]: https://dbader.org/blog/python-code-linting
[ipython]: https://ipython.org/
