## php docker environment
```
// run before
mkdir /srv/logs
cp -R ./www /srv/www
touch /srv/logs/access.log
touch /srv/logs/error.log

// run
docker-compose up -d
```
