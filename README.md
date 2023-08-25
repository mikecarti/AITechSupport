# NeuroWeb
Complete backend project

To run it 
1) install docker
2) install docker-compose
3) *optional* install portainer

```
git clone https://github.com/NeuroSquare/NeuroWeb -b dev
cd NeuroWeb
docker-compose up --build (-d for detached)
```

To stop it / Rerun
```
docker-compose down --remove-orphans (stop)
docker-compose up --build (-d for detached) (run)
```
