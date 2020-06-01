# linux_apps_nx_camera_enc

## 1. Display help

root@riscv64:~# nx_camera_enc -h   
Usage : ./nx_camera_enc -d  [target prefix]   
 Options :   
   -d [target prefix] : output target prefix   
   -g [Gop]           : GoP value (def:30)   
   -b [Bitrate]       : encoding bitrate in Kbytes (def:4096(4MB))   
   -n [number of GoP] : number of GoPs for file dividing. (def:1)   
  

## 2. Encoding GOP(30), File Interval( 5 GOP), Bitrate(2MB) , Output Prefix(/home/root/output)
root@riscv64:~# nx_camera_enc -g 30 -n 5 -b 2048 -d /home/root/output
