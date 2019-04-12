## php docker environment
```
// before run
mkdir /srv/logs
cp -R ./www /srv/www
touch /srv/logs/access.log
touch /srv/logs/error.log

// run
docker-compose up -d
```
