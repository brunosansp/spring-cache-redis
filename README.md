# Aplicação simples do redis

### Rodar um container redis
> docker run --name my-redis -p 6379:6379 -d redis

### verificar o resultado no redis
> docker exec -it my-redis sh
> 
> redis-cli
> 
> keys *
> 
> get products::1