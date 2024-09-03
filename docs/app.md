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
    Vou retornar em uma api rest (json) o nome do podcast, nome do episódio, imagem de capa, url do vídeo, categoria


``` js
[

    {
        podcastName: "flow",
        episode: "CBUM - Flow #319",
        videoId:"pQSuQmUfS30"
        cover: "https://i.ytimg.com/vi/pQSuQmUfS30/maxresdefault.jpg",
        link: "https://www.youtube.com/watch?v=pQSuQmUfS30",
        categories: ["saúde", "fitness", "esporte"]
    },
    {
        podcastName: "flow",
        episode: "RUBENS BARRICHELLO - Flow #339",
        videoId:"4KDGTdiO4I"
        cover: "https://i.ytimg.com/vi/4KDGTdiO4I/maxresdefault.jpg",
        link: "https://www.youtube.com/watch?v=4KDGTdiO4I",
        categories: ["esporte", "corrida"]
    }
]
```

