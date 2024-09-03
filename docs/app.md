# Podcast Manager

### Descrição
Um app ao estilo netflix, aonde possa centralizar diferentes episódios de podcasts separados por categoria

### Domínio
Podcasts feitos em vídeo


### Features
    - Listar os episódios em sessões de categorias
        - [saúde, fitness, menstalidade, humor]
    - Filtrar episódios por nome de podcast


## Como

#### Feature:
    Listar os episódios em sessões de categorias

### Como vou implementar:
    GET: retorna lista de episódios

    response
``` js
[

    {
        podcastName: "flow",
        episode: "CBUM - Flow #319",
        videoId:"pQSuQmUfS30"
        categories: ["saúde", "fitness", "esporte"]
    },
    {
        podcastName: "flow",
        episode: "RUBENS BARRICHELLO - Flow #339",
        videoId:"4KDGTdiO4I"
        categories: ["esporte", "corrida"]
    }
]
```


    GET: retorna lista de episódios baseado em um parâmetro envidado pelo user do Nome do Podcast

