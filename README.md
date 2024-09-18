```
lscpu | grep -E '^Thread|^Core|^Socket|^CPU\('
```
```
free -g -h -t
```
```
tar -xf
```
```
lsb_release -a
```
```
lshw -c memory
```
```
lusrmgr.msc
```
```
ps -aux | grep -i xxx
```
```
env | grep -i xxx
```
```
check enable virtualization:
lscpu | grep -i vmx 
```
```
grep MemTotal /proc/meminfo || free -g
```
```
Proxy switchyomega
```
```
.ssh/config
Host *
    ServerAliveInterval 240
```
[DEFAULT]
debug = False
log_dir = /var/log/kolla/freezer
client_id = dev7-cont-01
jobs_dir = /etc/freezer/scheduler/conf.d
os_username = admin
os_password = fiBBcndpo6Ttrfz4J5R447kzI0tUBBjgcduNaWst
os_auth_url = https://cloud7-internal.sadad.test:5000
os_project_name = admin
os_project_domain_name = Default
os_user_domain_name = Default
