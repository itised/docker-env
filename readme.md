### To Install: ###

1. Add repository to composer.json:
```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/itised/docker-env.git"
    }
]
```

2. Require docker-env in composer.json
```json
"require-dev": {
    "itised/docker-env": "dev-master"
}
```

3. Run `./vendor/bin/install-docker-env` from project root to copy files and ensure the proper .env fields exist

4. Set the .env values:

`COMPOSE_PROJECT_NAME`
: The name docker will use for the containers

`DC_HOST_PORT`
: The port on the host machine that will be mapped to port 80 in the nginx container

`DC_SITE`
: The path to the root of your project on your host machine