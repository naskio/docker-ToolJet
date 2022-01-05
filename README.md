# docker-ToolJet

Docker compose configuration for ToolJet, ready to use

## prerequisites

- [Postgres](https://hub.docker.com/r/postgres/)

## Step-by-step instructions

- Configure `.env` file
- Run `docker-compose up -d`
- seed the database with `docker-compose run server npm run db:seed`
- This seeds the database with a default user with the following credentials: email: `dev@tooljet.io`
  password: `password`
- ToolJet client would now be served at the URL you've set in `TOOLJET_HOST`

## Further information

Read more at the [ToolJet website](https://docs.tooljet.com/docs/deployment/docker)