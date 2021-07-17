$ docker build --build-arg DEVEL=yes -t devcontainer_local_django:dev .

$ docker run -it --rm -v $(pwd):/app/src devcontainer_local_django:dev bash

$ cookiecutter gh:pydanny/cookiecutter-django



