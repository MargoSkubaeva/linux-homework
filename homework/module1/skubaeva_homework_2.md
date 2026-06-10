Homework-2.File system and permissioons.
Task-1
cd/
ls -l

cd /ect
ls

cd /home
ls

Task-2
mkdir ~/lab2
cd ~/lab2
 
> file.txt
cp file.txt file_copy.txt
mv file_copy.txt  file_renamed.txt

In file.txt hardlink.txt
In -s file.txt symlink.txt

find ~ -name "file.txt"

Example result:
/home/user/lab2/file.txt

Task-3
ls -l file.txt
chmod 444 file.txt 
chmod 444 u+w file.txt

umask
umask 022

Task-4
sudo useradd trainee
sudo usermod -aG sudo trainee

cat /etc/passwd

Example result:
trainee:x:1001:1001::/home/trainee:/bin/bash
