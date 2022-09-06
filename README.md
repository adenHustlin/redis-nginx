# redis-nginx

```bash
docker-compose up -d
```
<img width="1286" alt="Screen Shot 2022-09-04 at 4 14 58 AM" src="https://user-images.githubusercontent.com/75873455/188672016-19408694-21e8-4dc5-9f97-8ca4a1ef43ab.png">





<img width="790" alt="Screen Shot 2022-09-07 at 12 17 07 AM" src="https://user-images.githubusercontent.com/75873455/188672621-d4ebd553-37a2-4674-8fc7-8b4e85961053.png">

Assuming we need to run two different web application server on virtual environment 
By using nginx we can distribute client requests to  written servers in upstream section

- localhost:80 will lead to rather 81 or 82 port which are servers running on docker

Also possible to define desired algorithmn that you want to use for loadbalancing

Simple reverse proxy, loadbalancing practice

