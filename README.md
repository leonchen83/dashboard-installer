# dashboard-installer

```java  

cd dashboard_installer
docker build -t redisrdbcli/dashboard-installer:v1.0.3
docker build -t redisrdbcli/dashboard-installer:latest

# remove local docker images
# docker rmi -f <IMAGEID>

docker login
docker push redisrdbcli/dashboard-installer:v1.0.3
docker push redisrdbcli/dashboard-installer:latest

```