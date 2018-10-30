# devops

아래를 다운받는다
https://github.com/teamsmiley/SQL-Angeles.git

임의의 폴더에 압축을 푼 뒤
아래의 windows 부터 따라한다

https://github.com/teamsmiley/SQL-Angeles/blob/dev/devops/Study-04/Study-04.md


ip 확인하는건
vagrant ssh 로 쉘에 뒤
ipconfig 실행하고
두 번째 eth0: 뒤에 나오는 inet 뒤의 ip 주소


eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 172.19.0.76  netmask 255.255.255.240  broadcast 172.19.0.79
        inet6 fe80::215:5dff:fe38:100  prefixlen 64  scopeid 0x20<link>
        ether 00:15:5d:38:01:00  txqueuelen 1000  (Ethernet)
        RX packets 430981  bytes 644614017 (614.7 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 87660  bytes 6453506 (6.1 MiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        
        
여기서 inet 뒤의 ip 주소를 복사한 뒤 브라우저 주소 입력창에 :8080을 붙여서 입력, 즉
아래같이 입력

172.19.0.76:8080
