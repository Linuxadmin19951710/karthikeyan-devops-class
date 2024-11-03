
![network task ip and top](https://github.com/user-attachments/assets/09c6d857-8775-477e-a5e8-f3f840ded787)

![network task connectivity](https://github.com/user-attachments/assets/0eebc51c-bb66-4a8a-80fc-17db4c373ffc)
![network task port](https://github.com/user-attachments/assets/13e51770-0285-4113-8129-5bca45357d52)

[root@ip-172-31-1-175 ~]#
Server:         172.31.0.2
Address:        172.31.0.2#53

Non-authoritative answer:
Name:   guvi.in
Address: 172.67.70.207
Name:   guvi.in
Address: 104.26.4.88
Name:   guvi.in
Address: 104.26.5.88
Name:   guvi.in
Address: 2606:4700:20::ac43:46cf
Name:   guvi.in
Address: 2606:4700:20::681a:458
Name:   guvi.in
Address: 2606:4700:20::681a:558

[root@ip-172-31-1-175 ~]# top
top - 19:21:37 up 17 min,  1 user,  load average: 0.00, 0.00, 0.00
Tasks: 105 total,   1 running, 104 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.0 us,  6.2 sy,  0.0 ni, 93.8 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :    765.7 total,    207.3 free,    271.4 used,    407.9 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.    494.3 avail Mem

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND
      1 root      20   0  109376  18656  10856 S   0.0   2.4   0:00.78 systemd
      2 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kthreadd
      3 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 rcu_gp
      4 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 rcu_par_gp
      5 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 slub_flushwq
      6 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 netns
      8 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/0:0H-events_highpri
     10 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 mm_percpu_wq
     11 root      20   0       0      0      0 I   0.0   0.0   0:00.43 kworker/u30:1-events_unbound
     12 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_kthre
     13 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_rude_
     14 root      20   0       0      0      0 I   0.0   0.0   0:00.00 rcu_tasks_trace
     15 root      20   0       0      0      0 S   0.0   0.0   0:00.03 ksoftirqd/0
     16 root      20   0       0      0      0 S   0.0   0.0   0:00.38 pr/ttyS0
     17 root      20   0       0      0      0 S   0.0   0.0   0:00.34 pr/tty0
     18 root      20   0       0      0      0 I   0.0   0.0   0:00.06 rcu_preempt
     19 root      rt   0       0      0      0 S   0.0   0.0   0:00.00 migration/0
     20 root     -51   0       0      0      0 S   0.0   0.0   0:00.00 idle_inject/0
     21 root      20   0       0      0      0 I   0.0   0.0   0:00.12 kworker/0:1-cgroup_destroy
     22 root      20   0       0      0      0 S   0.0   0.0   0:00.00 cpuhp/0
     24 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kdevtmpfs
     25 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 inet_frag_wq
     26 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kauditd
     27 root      20   0       0      0      0 S   0.0   0.0   0:00.00 khungtaskd
     28 root      20   0       0      0      0 S   0.0   0.0   0:00.00 oom_reaper
     30 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 writeback
     31 root      20   0       0      0      0 S   0.0   0.0   0:00.01 kcompactd0
     32 root      25   5       0      0      0 S   0.0   0.0   0:00.00 ksmd
     33 root      39  19       0      0      0 S   0.0   0.0   0:00.01 khugepaged
     34 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 cryptd
     35 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kintegrityd
     36 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kblockd
     37 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 blkcg_punt_bio
     38 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 tpm_dev_wq
     39 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 md
     40 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 md_bitmap
     41 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 edac-poller
[root@ip-172-31-1-175 ~]#
[root@ip-172-31-1-175 ~]# ping guvi.in
PING guvi.in (104.26.5.88) 56(84) bytes of data.
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=1 ttl=54 time=1.39 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=2 ttl=54 time=1.70 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=3 ttl=54 time=1.58 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=4 ttl=54 time=1.49 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=5 ttl=54 time=1.58 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=6 ttl=54 time=1.83 ms
64 bytes from 104.26.5.88 (104.26.5.88): icmp_seq=7 ttl=54 time=1.51 ms
^C
--- guvi.in ping statistics ---
7 packets transmitted, 7 received, 0% packet loss, time 6009ms
rtt min/avg/max/mdev = 1.390/1.580/1.828/0.133 ms
[root@ip-172-31-1-175 ~]# traceroute guvi.in
traceroute to guvi.in (172.67.70.207), 30 hops max, 60 byte packets
 1  244.5.0.15 (244.5.0.15)  5.671 ms 244.5.0.141 (244.5.0.141)  7.945 ms *
 2  240.1.184.4 (240.1.184.4)  0.299 ms 240.1.184.5 (240.1.184.5)  0.314 ms 240.1.184.6 (240.1.184.6)  0.293 ms
 3  240.2.216.9 (240.2.216.9)  1.738 ms 240.2.216.10 (240.2.216.10)  1.719 ms  1.683 ms
 4  151.148.14.58 (151.148.14.58)  0.980 ms 151.148.14.60 (151.148.14.60)  1.638 ms 151.148.14.58 (151.148.14.58)  1.613 ms
 5  151.148.14.61 (151.148.14.61)  5.479 ms  5.453 ms 151.148.14.59 (151.148.14.59)  2.226 ms
 6  108.162.247.69 (108.162.247.69)  3.076 ms 108.162.247.77 (108.162.247.77)  1.453 ms 108.162.247.69 (108.162.247.69)  3.303 ms
 7  172.67.70.207 (172.67.70.207)  1.355 ms  1.372 ms  1.461 ms
[root@ip-172-31-1-175 ~]#

[root@ip-172-31-1-175 ~]# telnet guvi.com 9000
Trying 104.21.79.166...
telnet: connect to address 104.21.79.166: Connection timed out
Trying 172.67.146.154...
telnet: connect to address 172.67.146.154: Connection timed out
Trying 2606:4700:3037::ac43:929a...
telnet: connect to address 2606:4700:3037::ac43:929a: Network is unreachable
Trying 2606:4700:3031::6815:4fa6...
telnet: connect to address 2606:4700:3031::6815:4fa6: Network is unreachable
[root@ip-172-31-1-175 ~]#



