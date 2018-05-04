# -node_exporter-cannot-execute-binary-file-Exec-format-error
Hello, I am a student trying to understand and learn how prometheus work in mininet environment. 
These are the steps that I followed:
- downloaded prometheus-2.2.1.linux-amd64.tar.gz using 'wget' command
- downloaded node_exporter-0.16.0-rc.3.linux-amd64.tar.gz using 'wget' command
- extract node_exporter using tar -xzf node_exporter-0.16.0-rc.3.linux-amd64.tar.gz
- change directory to node_exporter-0.16.0-rc.3.linux-amd64.tar.gz and this happened..

root@mininet-vm:~/node_exporter-0.16.0-rc.3.linux-amd64# ls
LICENSE  node_exporter  NOTICE
root@mininet-vm:~/node_exporter-0.16.0-rc.3.linux-amd64# ./node_exporter -h
bash: ./node_exporter: cannot execute binary file: Exec format error

Environment:
root@mininet-vm:~/node_exporter-0.16.0-rc.3.linux-amd64# uname -a
Linux mininet-vm 4.2.0-27-generic #32~14.04.1-Ubuntu SMP Fri Jan 22 15:32:27 UTC 2016 i686 i686 i686 GNU/Linux

Please help!
