# Instalación de Jenkins en Docker
````
git clone https://github.com/falconsoft3d/jenkis-docker-compose.git
docker-compose up -d
````

````
http://localhost:8080/
````

````
docker exec 79dc42e0a318 cat /var/jenkins_home/secrets/initialAdminPassword
````

# docker swarm
```
docker swarm init
docker-compose build
docker stack deploy jenkis -c docker-compose.yml
docker stack ls
```


# My contact data
```
Marlon Falcón Hernández | Valencia | Spain
* ERP, CRM y Software: https://www.marlonfalcon.com
» Email: mfalconsoft@gmail.com , falconsof.3d@gmail.com
» Github: https://github.com/falconsoft3d
» linkedin: https://linkedin.com/in/marlon-falcón-3a2aa9a4
```
