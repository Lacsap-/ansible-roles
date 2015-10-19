# quassel-core in docker ansible role

- Works on debian 8
- Require Docker and docker-py installed on your machine.
- This role will pull and run a [quassel-core](https://hub.docker.com/r/lacsap/quassel-core/) container listening on port 4242.
- You can put your quasselcore.conf and quassel-storage.sqlite in the template folder and change config_exist to true to restore a config.
- Enter any username/password when first connecting.
