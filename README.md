**Credits to** 
 - http://developers.redhat.com/blog/2014/05/05/running-systemd-within-docker-container/

Use this image as a base for creating Docker images needed systemd.

Run this as privileged with mount for /sys/fs/cgroup
```
docker run –privileged -d -v /sys/fs/cgroup:/sys/fs/cgroup:ro hrishikesh/systemd-in-docker
```
