# docker-logitechmediaserver

Docker image for Logitech Media Server (SqueezeCenter, SqueezeboxServer, SlimServer)



Run with:

```
docker run -t -i --rm=true --net="host" \
      -v "/mnt/user/appdata/LogitechMediaServer":"/config":rw \
	  -v "/mnt/music":"/music":ro \
	  -v "/var/run/dbus":"/var/run/dbus":rw \
      -v "/etc/localtime":"/etc/localtime":ro \
      snoopy86/logitechmediaserver
```
