# Docker Magento2 development environment


Build images
```
cd container-data
./rebuild.sh
cd ..
```

```
cd container-apache_php
./rebuild.sh
cd ..
```

Run for the first time
```
cd container-magento
docker-compose -f docker-compose-dev.yml build
cd ..
```

Start environment and tail logs
```
cd container-magento
docker-compose -f docker-compose-dev.yml start
docker-compose -f docker-compose-dev.yml logs -f
cd ..
```

