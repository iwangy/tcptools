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