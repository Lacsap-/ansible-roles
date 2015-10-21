# deluge-web in docker ansible role

- Should work on any distro
- Require Docker and docker-py installed on your machine.
- This role will pull and run a dokuwiki container listening on port 8116.
- You cannot restore via ansible yet and the volume will be mounted somewhere
in /var/lib/docker because of a permission problem with Docker
- To find the location of your data type ``` docker inspect dokuwiki | grep Source ```
