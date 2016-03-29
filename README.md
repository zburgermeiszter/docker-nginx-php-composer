# Docker Nginx PHP7 Composer stack#

Image building and composer dependency installing is defined in Makefile.
So simply run the following command in the repository root.
```
make
```

It will install the following:
- Docker compose (as a container)
- Composer
- Composer dependencies

To launch the stack run the following command:
```
docker-compose up -d
```