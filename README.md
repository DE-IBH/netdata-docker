# netdata

These are docker images for [netdata](http://my-netdata.io/) based
on the official *Debian GNU/Linux* or *Alpine Linux* packages.


## Tagged Docker Images

Images are tagged according to the installed netdata version.

* [`1.9.0`, `latest` Dockerfile](https://github.com/DE-IBH/netdata-docker/blob/master/netdata-1.9.0-alpine/Dockerfile)

  [![Layers](https://images.microbadger.com/badges/image/ibhde/netdata:latest.svg)](https://images.microbadger.com/badges/image/ibhde/netdata:latest)

* [`1.6.0` Dockerfile](https://github.com/DE-IBH/netdata-docker/blob/master/netdata-1.6.0-debian/Dockerfile)

  [![Layers](https://images.microbadger.com/badges/image/ibhde/netdata:1.6.0.svg)](https://images.microbadger.com/badges/image/ibhde/netdata:1.6.0)

## Usage

```
$ docker run -it -v /sys:/host/sys:ro -v /proc:/host/proc:ro -p 19999:19999 ibhde/netdata
```
