**Ping www.google.com three times**
```
(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.google.com   
PING www.google.com (142.251.211.228): 56 data bytes
64 bytes from 142.251.211.228: icmp_seq=0 ttl=57 time=29.659 ms
64 bytes from 142.251.211.228: icmp_seq=1 ttl=57 time=28.819 ms
64 bytes from 142.251.211.228: icmp_seq=2 ttl=57 time=11.039 ms
64 bytes from 142.251.211.228: icmp_seq=3 ttl=57 time=24.623 ms
64 bytes from 142.251.211.228: icmp_seq=4 ttl=57 time=37.309 ms
--- www.google.com ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 11.039/26.290/37.309/8.655 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.google.com
PING www.google.com (142.251.211.228): 56 data bytes
64 bytes from 142.251.211.228: icmp_seq=0 ttl=57 time=24.186 ms
64 bytes from 142.251.211.228: icmp_seq=1 ttl=57 time=22.021 ms
64 bytes from 142.251.211.228: icmp_seq=2 ttl=57 time=11.658 ms
Request timeout for icmp_seq 3
64 bytes from 142.251.211.228: icmp_seq=4 ttl=57 time=77.469 ms
--- www.google.com ping statistics ---
5 packets transmitted, 4 packets received, 20.0% packet loss
round-trip min/avg/max/stddev = 11.658/33.834/77.469/25.634 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.google.com
PING www.google.com (142.251.211.228): 56 data bytes
64 bytes from 142.251.211.228: icmp_seq=0 ttl=57 time=43.504 ms
64 bytes from 142.251.211.228: icmp_seq=1 ttl=57 time=20.718 ms
64 bytes from 142.251.211.228: icmp_seq=2 ttl=57 time=18.881 ms
64 bytes from 142.251.211.228: icmp_seq=3 ttl=57 time=25.063 ms
64 bytes from 142.251.211.228: icmp_seq=4 ttl=57 time=11.468 ms
--- www.google.com ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 11.468/23.927/43.504/10.729 ms
```