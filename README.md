# LaTeX Annotated Bibliography

A dockerized LaTeX-based approach to generating an annotated bibliography.

## Instructions

* Update `paper/annot.*` files.
* Install docker
* Install docker-compose
* Run `docker-compose run build`

The first time you run the build it will take a long time. But once your base image is built, it is fast--until you decide to delete docker images. Your final document will be outputed as `paper/annot.pdf`.

