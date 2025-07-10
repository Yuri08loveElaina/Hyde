root@ip-10-10-140-114:~#  ssh molly@10.10.184.222
The authenticity of host '10.10.184.222 (10.10.184.222)' can't be established.
ECDSA key fingerprint is SHA256:FdZIpBTx8LSeCTcm1GREfTx6rbvASv3/94IuE+Wm0t4.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '10.10.184.222' (ECDSA) to the list of known hosts.
molly@10.10.184.222's password: 
Welcome to Ubuntu 20.04.6 LTS (GNU/Linux 5.15.0-1083-aws x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro

 System information as of Thu 10 Jul 2025 10:42:41 AM UTC

  System load:  0.17               Processes:             113
  Usage of /:   18.6% of 14.47GB   Users logged in:       0
  Memory usage: 17%                IPv4 address for ens5: 10.10.184.222
  Swap usage:   0%

Expanded Security Maintenance for Applications is not enabled.

0 updates can be applied immediately.

7 additional security updates can be applied with ESM Apps.
Learn more about enabling ESM Apps service at https://ubuntu.com/esm


The list of available updates is more than a week old.
To check for new updates run: sudo apt update

Last login: Tue Dec 17 14:37:49 2019 from 10.8.11.98
molly@ip-10-10-184-222:~$ sudo apt update
[sudo] password for molly: 
molly is not in the sudoers file.  This incident will be reported.
molly@ip-10-10-184-222:~$ ls
flag2.txt
molly@ip-10-10-184-222:~$ cat flag2.txt
THM{c8eeb0468febbadea859baeb33b2541b}
molly@ip-10-10-184-222:~$ 
