![file_creation_task2](https://github.com/user-attachments/assets/2364cf9c-7af5-46dc-8093-f437d7d2bb14)
![file_creation_task1](https://github.com/user-attachments/assets/d15ee6ca-2d00-47ce-8874-a1bc6887eb25)
 mkdir my_folder
[root@ip-172-31-1-175 ~]# cd my_folder
[root@ip-172-31-1-175 my_folder]# touch my_file.txt
[root@ip-172-31-1-175 my_folder]# vi my_file.txt
[root@ip-172-31-1-175 my_folder]# touch another_file.txt
[root@ip-172-31-1-175 my_folder]# vi another_file.txt
[root@ip-172-31-1-175 my_folder]# cat another_file.txt >> my_file.txt
[root@ip-172-31-1-175 my_folder]# cat another_file.txt
this is the second text file
contents of this file, needs to be concatenated with first file
[root@ip-172-31-1-175 my_folder]# cat my_file.txt
creating folder and files
this is the first file
this is the second text file
contents of this file, needs to be concatenated with first file
[root@ip-172-31-1-175 my_folder]# touch file1
[root@ip-172-31-1-175 my_folder]# ls -ltr
total 8
-rw-r--r--. 1 root root  93 Oct 16 15:58 another_file.txt
-rw-r--r--. 1 root root 143 Oct 16 15:59 my_file.txt
-rw-r--r--. 1 root root   0 Oct 16 16:01 file1
[root@ip-172-31-1-175 my_folder]# touch file1.txt file2.txt file3.txt file4.txt file5.txt file6.txt file7.txt file8.txt file9.txt file10.txt file11.txt file12.txt file13.txt file14.txt file15.txt file16.txt file17.txt file18.txt file19.txt file20.txt
[root@ip-172-31-1-175 my_folder]# ls
another_file.txt  file10.txt  file12.txt  file14.txt  file16.txt  file18.txt  file1.txt   file2.txt  file4.txt  file6.txt  file8.txt  my_file.txt
file1             file11.txt  file13.txt  file15.txt  file17.txt  file19.txt  file20.txt  file3.txt  file5.txt  file7.txt  file9.txt
[root@ip-172-31-1-175 my_folder]# mv file1.txt file1.yml
[root@ip-172-31-1-175 my_folder]# mv file2.txt file2.yml file3.txt file3.yml
mv: target 'file3.yml' is not a directory
[root@ip-172-31-1-175 my_folder]# mv file2.txt file2.yml
[root@ip-172-31-1-175 my_folder]# mv file3.txt file3.yml
[root@ip-172-31-1-175 my_folder]# mv file4.txt file4.yml
[root@ip-172-31-1-175 my_folder]# mv file5.txt file5.yml
[root@ip-172-31-1-175 my_folder]# ls
another_file.txt  file10.txt  file12.txt  file14.txt  file16.txt  file18.txt  file1.yml   file2.yml  file4.yml  file6.txt  file8.txt  my_file.txt
file1             file11.txt  file13.txt  file15.txt  file17.txt  file19.txt  file20.txt  file3.yml  file5.yml  file7.txt  file9.txt
[root@ip-172-31-1-175 my_folder]# ls | tail -5
file6.txt
file7.txt
file8.txt
file9.txt
my_file.txt
[root@ip-172-31-1-175 my_folder]# ls | grep .yml
file1.yml
file2.yml
file3.yml
file4.yml
file5.yml
[root@ip-172-31-1-175 my_folder]#
