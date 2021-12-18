<p align="center">
  <h3 align="center">TOP 10 USEFUL COMMANDS IN LINUX PART 4</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="https://youtu.be/GrvrBXXmSLs">View Tutorial</a>
  </p>
</p>


<br />
<br />
<br />

1. **PS** - Linux provides us a utility called ps for viewing information related with the processes on a system which stands as abbreviation for “Process Status”. ps command is used to list the currently running processes and their PIDs along with some other information depends on different options. 
  ```sh
  ps
  ```
2. **KILL** - The kill command sends a signal to specified processes or process groups causing them to act according to the signal
  ```sh
  kill <pid>
  ```
3. **GZIP** - gzip command compresses files. Each single file is compressed into a single file. The compressed file consists of a GNU zip header and deflated data. 
  ```sh
  gzip <filename>
  gzip -k <filename>
  ```
4. **NETSTAT** - Netstat command displays various network related information such as network connections, routing tables, interface statistics, masquerade connections, multicast memberships etc.
  ```sh
  netstat -a
  netstat -at
  netstat -au
  ```
5. **CHOWN** - chown command is used to change the file Owner or group. Whenever you want to change ownership you can use chown command.
  ```sh
  chown <owner_name> <file_name>
  ```
6. **IFCONFIG** - If you want to know the name of your host/network simply type hostname. Adding a -i to the end will display the IP address of your network.
  ```sh
  hostname
  hostname -i
  ```
7. **XARGS** - users command in Linux system is used to show the user names of users currently logged in to the current host. It will display who is currently logged in according to FILE. If the FILE is not specified, use /var/run/utmp. /var/log/wtmp as FILE is common
  ```sh
  users
  ```
8. **DPKG** - chmod is another Linux command, used to change the read, write, and execute permissions of files and directories.
  ```sh
  chmod a=rw <filename.ext> (More Info Check the link below)
  ```
9. **MOUNT** - For each file, getfacl displays the file name, owner, the group, and the Access Control List (ACL).
  ```sh
  getfacl
  ```
10. **TTY** - Install a package in Centos use yum install if in Debian use apt install
  ```sh
  yum install <package_name>
  apt install <package_name>
  ```

<!-- USAGE EXAMPLES -->
## More Details

I Found many Beautiful Resource online which explains a bit more about chmod and other commands 

 please refer to the [Beautiful Resource 1](https://www.hostinger.in/tutorials/linux-commands)
 
 
  please refer to the [Chmod Resource](https://www.computerhope.com/unix/uchmod.htm)
