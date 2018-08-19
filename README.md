# 42-init
## System and Network Administration Project

This project gives you the opportunity to discover system and network basic commands, <br>
many of the services used on a server machine, as well as a few ideas of <br>
scripts that can be useful for SysAdmins on a daily basis. <br>

## Network

1. Get the list of the network interfaces of the machine without displaying any detail for these interfaces. Only the list of names. <br>
2. Identify and display the Ethernet interface characteristics <br>
3. Identify the MAC address of the Wi-Fi card <br>
4. Identifiy the default gateway in the routing table <br>
5. Identify the IP address of the DNS that responds to the following url: slash16.org <br>
6. Get the complete path of the file that contains the IP address of the DNS server you’re using <br>
7. Query an external DNS server on the slash16.org domain name (ie. : google 8.8.8.8) <br>
8. Find the provider of slash16.org <br>
9. Find the external IP of 42.fr <br>
10. Identify the network devices between your computer and the slash16.org domain <br>
11. Use the output of the previous command to find the name and IP address of the
device that makes the link between you (local network) and the outside world <br>
12. Check that the server with the 10.51.1.253 IP address is reachable from your computer. <br>
13. Use the Reverse DNS to find out the name of the server linked to the 10.51.1.81 IP address <br>
14. What file contains the local DNS entries? <br>
15. Make the intra.42.fr address reroute to 46.19.122.85 <br>

## System

1. In what file can you find the installed version of your Debian? <br>
2. What command can you use to rename your system? <br>
3. What file has to be modified to make it permanent? <br>
4. What command gives you the time since your system was last booted? <br>
5. Name the command that determines the state of the SSH service. <br>
6. Name the command that reboots the SSH service. <br>
7. Figure out the PID of the SSHD service. <br>
8. What file contains the RSA keys of systems that are authorized to connect via SSH? <br>
9. What command lets you know who is connected to the System? <br>
10. Name the command that lists the partition tables of drives? <br>
11. Name the command that displays the available space left and used on the system
in an humanly understandable way <br>
12. Figure out the exact size of each folder of /var in a humanly understandable way
followed by the path of it. <br>
13. Name the command that find, in real time, currently running processes <br>
14. Run the ‘tail -f /var/log/syslog‘ command in background <br>
15. Find the command that kills the background command’s process <br>
16. Find the service which makes it possible to run specific tasks following a regular
schedule <br>
17. Find the command which gives the list of firewall rules <br>
18. With the previous command, authorize only IP addresses from 10.0.0.0/8 to connect
to your system <br>
19. With the previous command, forbid all others IP <br>

## Scripting

1. Write a script which displays only the login, UID and Path of each entry of the
/etc/passwd file. <br>
2. Write a script which updates all the package sources, then all the packages, and then
logs everything in a file named /var/log/update_script.log. Create a scheduled
task for this script, once per week at 4 AM. <br>
3. Write a script which displays the list of files from the folder given as parameter,
sorted by size. <br>
4. Write a script which monitors the modifications made to the /etc/crontab file and
sends an e-mail to root if the file is modified. Create a scheduled task to run this
script everyday at midnight. <br>

#### More about School 42 you can find here: https://en.wikipedia.org/wiki/42_(school)
