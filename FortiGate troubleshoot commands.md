### FortiGate commands for ldap log
```shell
diagnose debug application fnbamd -1
diagnose debug application authd -1
diagnose debug enable
```
```shell
diagnose debug disable
```
### Fortigate commands for tcpdump
```shell
diag sniffer packet any '' 3 1000
```
```shell
diag sniffer packet any 'host 192.168.10.2 or host 192.168.10.3' 3 100
```
```shell
diag sniffer packet any 'host 192.168.10.2 or host 192.168.10.3 and (port 80 or port 443)' 3 100
```
