# Setup

## Copy files
```
.env-example to .env
```

## Source Code

1. For existing app, create `src` folder at the root of this directory, then copy all files from existing project to the `src` folder.

## Common Commands
```
docker-compose run --rm composer install
docker-compose run --rm npm run dev
```

## Note
1. If reverse-proxy is running. please use that, pointing to this host.