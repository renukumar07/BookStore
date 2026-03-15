bookstore

https://docs.spring.io/spring-boot/how-to/build.html
https://springdoc.org/

http://localhost:8081/actuator/info
http://localhost:8081/actuator
http://localhost:8081/actuator/health

http://localhost:8081/swagger-ui/index.html

./mvnw spotless:apply

docker compose -f infra.yml up -d

docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:sts
docker run -d -p 8000:8000 -p 9000:9000 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:sts

Portainer login local
admin
adminadminadmin

https://taskfile.dev/docs/installation

https://docs.portainer.io/start/install-ce/server/docker

http://localhost:8081/api/products?page=1
