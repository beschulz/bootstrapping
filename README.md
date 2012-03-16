Some random bootstrapping scripts
=================================

The lxc-squeeze is a copy of the debian lxc-debian lxc-container creation
script. it has been modified to create a squeeze lxc-container instead of
a lenny one. Also some packages have been added.

---

## To Use this script to create an image with openqrm, run:
    mkdir -p /var/lib/lxc/squeeze
    ./lxc-squeeze -p /var/lib/lxc/squeeze
    cd /var/lib/lxc/squeeze/rootfs 
    tar -cvzf /var/www/squeeze.tgz *

now you have a valid image available at http://your-ip/squeeze.tgz
