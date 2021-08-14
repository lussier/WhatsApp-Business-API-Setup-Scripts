Inspect general log:

```
docker run -it --privileged --pid=host debian nsenter -t 1 -m -u -n -i sh
cd /var/lib/docker/volumes/installation_mysqlLogs/_data
``` 