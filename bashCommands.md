#### Bash commands to help with docker, typescript and webpack building
Prints out list of directories that hold commands used in the command line
  * echo $PATH

Concatenates files, view contents of files, etc
  * cat
  * cat /etc/passwd

---
**One line command**
    * docker-compose -f Yarn-Docker/docker-compose.yml run --entrypoint bash \
    * --rm \
    * -v /$PWD/:/app \
    * -w /app yarn

    or

    docker-compose -f Yarn-Docker/docker-compose.yml run --entrypoint bash \
    -v /$PWD/:/app \
    -w /app yarn

---
