docker-compose up -d  
docker-compose down
docker-compose restart
docker ps
docker volume ls
docker volume inspect VOLUME_NAME
docker logs CONTAINER_NAME
docker exec -it mukto_apache /bin/bash
docker exec -i mukto_mysql mysql -uUSERNAME -pPASSWORD mukto < ~/Downloads/mukto.sql
docker exec mukto_php php artisan


#production
docker-compose -f docker-compose.prod.yml up -d