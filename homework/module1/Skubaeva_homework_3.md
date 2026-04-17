Homework-3

Task-1
1.ps aux
2.top
3.echo $$
Result-5418

Task-2
1.sleep 1000 &
2.jobs
3.fg
4.kill %1
5.nohup sleep 1000 &

Task-3
1.nice -n 10 sleep500 &
2.jobs -1
3.renice 5 -p PID
4.ulimit -a

Task-4
1.df -h
2.free -h
