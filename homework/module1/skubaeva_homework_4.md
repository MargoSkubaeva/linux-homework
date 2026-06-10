Task-1
sudo apt update
sudo apt install tree
tree --version
sudo apt remove tree

Task-2
systemctl status cron
sudo systemctl stop cron
systemctl status cron
sudo systemctl start cron
sudo systemctl enable cron

Task-3
cd
tail -10 syslog
journalctl -p err
journalctl | grep cron

Task-4
cd~
nano myscript.sh
chmod +x myscripte.sh
sudonano /ect/systemd/system/myscript.service
sudo systemctl daemon-reload
sudo systemctl start myscript.service
systemctl status myscript.service
cat ~/dates.txt



