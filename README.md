# tcptools

## Using "ping"
**Ping www.amazon.com three times**

```
(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.amazon.com
PING d3ag4hukkh62yn.cloudfront.net (108.138.91.214): 56 data bytes
64 bytes from 108.138.91.214: icmp_seq=0 ttl=245 time=31.384 ms
64 bytes from 108.138.91.214: icmp_seq=1 ttl=245 time=77.141 ms
64 bytes from 108.138.91.214: icmp_seq=2 ttl=245 time=17.495 ms
64 bytes from 108.138.91.214: icmp_seq=3 ttl=245 time=35.255 ms
64 bytes from 108.138.91.214: icmp_seq=4 ttl=245 time=39.255 ms
--- d3ag4hukkh62yn.cloudfront.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 17.495/40.106/77.141/19.916 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.amazon.com
PING d3ag4hukkh62yn.cloudfront.net (18.65.233.187): 56 data bytes
64 bytes from 18.65.233.187: icmp_seq=0 ttl=245 time=19.084 ms
64 bytes from 18.65.233.187: icmp_seq=1 ttl=245 time=27.532 ms
64 bytes from 18.65.233.187: icmp_seq=2 ttl=245 time=24.087 ms
64 bytes from 18.65.233.187: icmp_seq=3 ttl=245 time=50.364 ms
64 bytes from 18.65.233.187: icmp_seq=4 ttl=245 time=15.901 ms
--- d3ag4hukkh62yn.cloudfront.net ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 15.901/27.394/50.364/12.163 ms

(base) ywang@Ians-Macbook-Pro ~ % ping -c 5 www.amazon.com
PING d3ag4hukkh62yn.cloudfront.net (18.65.233.187): 56 data bytes
Request timeout for icmp_seq 0
64 bytes from 18.65.233.187: icmp_seq=1 ttl=245 time=16.812 ms
64 bytes from 18.65.233.187: icmp_seq=2 ttl=245 time=39.972 ms
64 bytes from 18.65.233.187: icmp_seq=3 ttl=245 time=19.723 ms
64 bytes from 18.65.233.187: icmp_seq=4 ttl=245 time=31.439 ms
--- d3ag4hukkh62yn.cloudfront.net ping statistics ---
5 packets transmitted, 4 packets received, 20.0% packet loss
round-trip min/avg/max/stddev = 16.812/26.986/39.972/9.283 ms
```
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
| Website           | Stats                         |
| ----------------- | ----------------------------- |
| www.amazon.com    | 17.495/40.106/77.141/19.916 ms |
||15.901/27.394/50.364/12.163 ms|
||16.812/26.986/39.972/9.283 ms|
| www.google.com    | 11.039/26.290/37.309/8.655 ms |
||11.658/33.834/77.469/25.634 ms|
||11.468/23.927/43.504/10.729 ms|
| www.microsoft.com | 9.994/31.542/90.432/29.949 ms |
||13.736/17.636/22.317/2.827 ms|
||11.818/17.687/23.055/4.314 ms|
||12.525/17.715/22.076/4.103 ms|

- There was packet loss for the 2nd ping for www.google.com on the 4th packet.
- The IP address changed for www.amazon.com between pings from 108.138.91.214 to 18.65.233.187.

## Using "tracert"
**www.amazon.com**
- 
