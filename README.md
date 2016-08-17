# Entorno React.js

## Project parts:

* Rails 5 API: https://github.com/mrpatiwi/entorno-react-api
* Express.js + React.js Frontend: https://github.com/mrpatiwi/entorno-react-web
* React-native Mobile app: https://github.com/mrpatiwi/EntornoReactMobile

## Setup for deployment

**Requisites: Docker and Docker-compose**

```sh
git clone https://github.com/mrpatiwi/entorno-react.git
cd entorno-react

git clone https://github.com/mrpatiwi/entorno-react-web.git
git clone https://github.com/mrpatiwi/entorno-react-api.git
```


Set:

```sh
export POSTGRES_PASSWORD=PASSWORD
export SECRET_KEY_BASE=SECRET_KEY_BASE
```

Run:

```sh
docker-compose run -d
```
