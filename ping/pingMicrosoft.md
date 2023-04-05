**Ping www.microsoft.com three times**
```
(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.microsoft.com
PING e13678.dscb.akamaiedge.net (23.45.229.117): 56 data bytes
64 bytes from 23.45.229.117: icmp_seq=0 ttl=58 time=16.050 ms
64 bytes from 23.45.229.117: icmp_seq=1 ttl=58 time=13.736 ms
64 bytes from 23.45.229.117: icmp_seq=2 ttl=58 time=17.994 ms
64 bytes from 23.45.229.117: icmp_seq=3 ttl=58 time=22.317 ms
64 bytes from 23.45.229.117: icmp_seq=4 ttl=58 time=18.084 ms
--- e13678.dscb.akamaiedge.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 13.736/17.636/22.317/2.827 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.microsoft.com
PING e13678.dscb.akamaiedge.net (23.45.229.117): 56 data bytes
64 bytes from 23.45.229.117: icmp_seq=0 ttl=58 time=13.470 ms
64 bytes from 23.45.229.117: icmp_seq=1 ttl=58 time=20.703 ms
64 bytes from 23.45.229.117: icmp_seq=2 ttl=58 time=19.391 ms
64 bytes from 23.45.229.117: icmp_seq=3 ttl=58 time=11.818 ms
64 bytes from 23.45.229.117: icmp_seq=4 ttl=58 time=23.055 ms
--- e13678.dscb.akamaiedge.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 11.818/17.687/23.055/4.314 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.microsoft.com
PING e13678.dscb.akamaiedge.net (23.45.229.117): 56 data bytes
64 bytes from 23.45.229.117: icmp_seq=0 ttl=58 time=22.076 ms
64 bytes from 23.45.229.117: icmp_seq=1 ttl=58 time=20.026 ms
64 bytes from 23.45.229.117: icmp_seq=2 ttl=58 time=20.960 ms
64 bytes from 23.45.229.117: icmp_seq=3 ttl=58 time=12.989 ms
64 bytes from 23.45.229.117: icmp_seq=4 ttl=58 time=12.525 ms
--- e13678.dscb.akamaiedge.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 12.525/17.715/22.076/4.103 ms

```