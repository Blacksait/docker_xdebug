# Docker Xdebug

## How to use

Just copy docker-compose.yml from dist example

    cp docker-compose.dist.yml docker-compose.yml

Change volumes path

    volumes:
        /Applications/MAMP/htdocs/Hireo:/app

Then build

    docker-compose build

And run composition

    docker-compose up -d

