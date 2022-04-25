# PelisRandom

Información sobre películas de los 70's 80's 90's

## Documentación

El formato de los archivos JSON es el siguiente:

```json
{
  "title": "[MOVIE_TITLE]",
  "file": "[FILE_LOCATION]",
  "start": "000",
  "final": "1234",
  "total": "1234.567890",
  "age": "[MOVIE_YEAR]",
  "desc": "[DESCRIPTION]",
  "director": "[MOVIE_DIRECTOR]",
  "genres": [
    { "code" :"AC", "name": "Acción" },
    { "code" :"RO", "name": "Romance" }
  ],
  "volume": "100",
  "wide": "169",
  "censored": "",
  "extra": "",
  "size": "[BYTES_SIZE]"
}
```

La lista de géneros disponibles es la siguiente:

```json
[
  { "code" :"AC", "name": "Acción" },
  { "code" :"AN", "name": "Animación" },
  { "code" :"AV", "name": "Aventuras" },
  { "code" :"BE", "name": "Bélico" },
  { "code" :"C-F", "name": "Ciencia ficción" },
  { "code" :"F-N", "name": "Cine" },
  { "code" :"CO", "name": "Comedia" },
  { "code" :"DESC", "name": "Desconocido" },
  { "code" :"DO", "name": "Documental" },
  { "code" :"DR", "name": "Drama" },
  { "code" :"FAN", "name": "Fantástico" },
  { "code" :"INF", "name": "Infantil" },
  { "code" :"INT", "name": "Intriga" },
  { "code" :"MU", "name": "Musical" },
  { "code" :"RO", "name": "Romance" },
  { "code" :"TV_SE", "name": "Serie de TV" },
  { "code" :"TE", "name": "Terror" },
  { "code" :"TH", "name": "Thriller" },
  { "code" :"WE", "name": "Western" },
  { "code" :"ZO", "name": "Zombies" }
]
```
[![pages-build-deployment](https://github.com/FrangaL/PelisRandom/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/FrangaL/PelisRandom/actions/workflows/pages/pages-build-deployment)
