## Filesystem

Check the content of the cgroups:

* cd /sys/fs/cgroup
* ls -al

Check the content of the memory cgroup:

* ls -al memory

Docker resource limits:

* docker run --rm --memory 256M -d alpine:3.12 sleep 1000
* ls -al memory/docker/<container-id>
* cat memory/docker/<container-id>/memory.limit_in_bytes