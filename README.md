# This is a boilerplate project for using Vuejs with Bootstrap incorporated with a Django backend..

Based heavily off of : https://github.com/rokups/hello-vue-django with adjustments.
Pull it down make changes & npm run build 

### Features

* Django backend in `./backend`
* vuejs (v2) frontend in `./frontend`
* Hot-reload with vue-loader
* eslint linter integration
* Makefile to make your life easy


### Development environment setup

These steps will install all required dependencies including development ones, run migrations and start dev server.

```bash
make dev
make migrate
make run
```

### Deployment

These steps will install production dependencies and build vuejs application to `static/dist` folder.

```bash
make prod
make build
```


