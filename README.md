# IP Network Broadcast Address Calculator

```
#!/usr/bin/env python3
#Use: ./ipcalc.py <ip/cidr>
#Alt: ./ipcalc.py <ip> <mask>

```
# Example :
```
>> ipcalc.py 192.167.2.53/22

INFO | 
------------------------
Address | 192.167.2.53
Mask | 255.255.252.0
Cidr | 22
Network | 192.167.0.0
Broadcast | 192.167.3.255
------------------------
```


```
CLASS A (1 - 126) 255.0.0.0.0 [11111111 00000000 00000000 00000000]
CLASS B (128 - 191) 255.255.0.0 [11111111 11111111 00000000 00000000]
CLASS C (192 - 223) 255.255.255.0 [11111111 11111111 11111111 00000000]

192.168.1.1 = 255.255.255.0 = [11111111 11111111 11111111 00000000]
/22 = 255.255.252.0 [CLASS B] = [11111111 11111111 11111100 00000000]

```
