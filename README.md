# docker-kirjuri
Setup Kirjuri inside docker container

Kirjuri project is available here : https://github.com/AnttiKurittu/kirjuri

- Clone with --recurse-submodules to download submodules : git clone --recurse-submodules https://github.com/jmalghem/docker-kirjuri
- Adapt docker-compose.yaml if needed :
  - Change exposed port for web service
  - Change exposed port for phpmyadmin / or remove this service
  - Change MySQL root password
- You need docker-compose to start the app [Download on GitHub](https://github.com/docker/compose/releases)
- From docker-kirjuri directory run : 
  - ```docker-compose up -d```
  - During the first start, the image is built.
