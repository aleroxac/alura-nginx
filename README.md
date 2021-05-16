# alura-nginx
Implementação das 3 principais funcionalidades do Nginx com base no conteúdo asimilado durante o treinamento Nginx da Alura.

## Recursos
- HTTP WebServer
- API Gateway
- Reverse Proxy
- Load Balancer

## Requisitos
- git
- docker
- docker-compose

## Modo de uso
``` shell
git clone github.com/aleroxac/alura-nginx && cd alura-nginx
docker-compose -f docker-compose.yml up -d

xdg-open http://localhost:8080

xdg-open http://localhost:8081
xdg-open http://localhost:8081/proxy

xdg-open http://localhost:8082
xdg-open http://localhost:8082/service1
xdg-open http://localhost:8082/service2

xdg-open http://localhost:8083
xdg-open http://localhost:8083/lb

docker-compose -f docker-compose.yml down
```