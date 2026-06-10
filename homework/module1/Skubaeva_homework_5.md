Homework-5
Task-1 Network diagnostics
Executed commands
ip a
ping -c 4 8.8.8.8
ss -tulpn

Local interface IP adress:10.0.2.15
The internet conection is working because pinging to 8.8.8.8 was successful without packet loss
Among the lisstening ports aaaaaare local systeem services on ports 53 and 631

Task-2
ssh-keygen -t ed22519
nano ~/.ssh/config
Host myserver
 HostName 10.0.2.15
 User margarita
 IdentityFile ~/.ssh/id_ed25519
ssh myserver

Task-3
echo "test" > test.txt
scp test.txt margarita@10.0.2.15:/home/margarita/
ssh margarita@10.0.2.15 "mkdir -p ~/sync_folder"
rsync -av ./ margarita@10.0.2.15:~/sync_folder/
sftp margarita@10.0.2.15
ls

