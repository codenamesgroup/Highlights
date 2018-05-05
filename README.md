# Highlight Microservice - Chompy

> This service constructs 8 'key phrases' by processing all reviews from a restaurant. It finds one sentence that matches each 'key phrase' and if possible, a photo that matches as well.

![alt text](https://i.imgur.com/lfj8OpMl.png)

## Related Projects

  - [Proxy Server](https://github.com/codenamesgroup/jornelas-proxy)
  - [Navbar](https://github.com/codenamesgroup/search-navbar-service)
  - [Map and Image Carousel](https://github.com/codenamesgroup/Maps-and-Image-Carousel-Service)
  - [Reviews](https://github.com/codenamesgroup/Reviews-Service)
  - [Sidebar](https://github.com/codenamesgroup/Bottom-right-sidebar)
  - [Tips](https://github.com/codenamesgroup/Tips)
  - [Restaurant Title](https://github.com/codenamesgroup/Title-Bar-Service)

## Table of Contents

1. [Usage](#usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

The HTML page is found at /:roomid

The API endpoint is /highlights/reviews/:roomid & ;highlights/reviews/:roomid

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node >= 6.13.0

## Development

### Installing Dependencies

From within the root directory:
```sh
$ npm install -g webpack
$ npm install
$ npm start
```

