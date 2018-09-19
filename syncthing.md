```
iocage fetch --plugins --name "syncthing" dhcp="on" vnet="on" allow_raw_sockets="1" boot="on" bpf=yes
```
```
iocage stop syncthing
```
```
mkdir -p /mnt/tank03/iocage/jails/syncthing/root/mnt/tank02/video
```
```
iocage fstab -a syncthing /mnt/tank02/video
```
```
iocage start syncthing
```
```
iocage console syncthing
```
```
service syncthing stop
```
```
pw addgroup merc && pw groupmod merc -g 3000 && pw useradd -n merc -u 816 -d /nonexistent -s /usr/sbin/nologin
```
```
chown -R 
```