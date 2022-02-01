## KT 인터넷 관리자모드 연결방법 설정
- 포트포워딩 설정: KT에서 제공한 공유기에서 라즈베리파이로 포트포워딩을 설정(SSH와 Web 관리자를 위한 포트 2개를 구성)
- 라즈베리파이 접속 후 포트포워딩 정보 확인
~~~
$ sudo iptables -L
Chain INPUT (policy ACCEPT)
target     prot opt source               destination

Chain FORWARD (policy ACCEPT)
target     prot opt source               destination

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination
$ sudo iptables -L -t nat
Chain PREROUTING (policy ACCEPT)
target     prot opt source               destination

Chain INPUT (policy ACCEPT)
target     prot opt source               destination

Chain POSTROUTING (policy ACCEPT)
target     prot opt source               destination

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination
~~~
### 포트포워딩 설정과 확인
~~~
$ sudo iptables -I POSTROUTING -t nat -o eth0 -j MASQUERADE
$ sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 8888 -j DNAT --to 172.30.1.254:8899
$ sudo iptables -L -t nat
Chain PREROUTING (policy ACCEPT)
target     prot opt source               destination
DNAT       tcp  --  anywhere             anywhere             tcp dpt:8888 to:172.30.1.254:8899

Chain INPUT (policy ACCEPT)
target     prot opt source               destination

Chain POSTROUTING (policy ACCEPT)
target     prot opt source               destination
MASQUERADE  all  --  anywhere             anywhere

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination
~~~
### 포트포워딩 설정 유지하기
- 참고: [iptables-persistent를 이용한 방화벽 설정 및 ip 차단](https://darrengwon.tistory.com/699), [참고](https://dknny.tistory.com/12)
~~~
$ sudo apt install iptables-persistent netfilter-persistent
$ sudo netfilter-persistent save
~~~
