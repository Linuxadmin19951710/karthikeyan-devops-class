[root@ip-172-31-1-175 ~]# cd /
[root@ip-172-31-1-175 /]# cd /home
[root@ip-172-31-1-175 home]# touch demo.txt
[root@ip-172-31-1-175 home]# ls -ltr
total 0
drwx------. 3 ec2-user ec2-user 95 Oct 16 13:26 ec2-user
-rw-r--r--. 1 root     root      0 Oct 16 16:24 demo.txt
[root@ip-172-31-1-175 home]# chmod 764 demo.txt
[root@ip-172-31-1-175 home]# ls -ltr
total 0
drwx------. 3 ec2-user ec2-user 95 Oct 16 13:26 ec2-user
-rwxrw-r--. 1 root     root      0 Oct 16 16:24 demo.txt
[root@ip-172-31-1-175 home]#


![file_permission_task](https://github.com/user-attachments/assets/8d468fdc-0c87-412c-b1d0-de9db4eb8f2c)
