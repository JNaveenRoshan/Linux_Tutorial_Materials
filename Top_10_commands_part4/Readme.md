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
6. **IFCONFIG** - ifconfig stands for "interface configuration." It is used to view and change the configuration of the network interfaces on your system.
  ```sh
  ifconfig -a
  ```
7. **XARGS** - Xargs is a great command that reads streams of data from standard input, then generates and executes command lines
  ```sh
  xargs [options] [command]
  ```
8. **DPKG** - dpkg is the main package management program in Debian and Debian based System. It is used to install, build, remove, and manage packages. Aptitude is the primary front-end to dpkg.
  ```sh
  dpkg -i <package file in .deb extension>
  ```
9. **MOUNT** - All files in a Linux filesystem are arranged in form of a big tree rooted at ‘/‘.These files can be spread out on various devices based on your partition table, initially your parent directory is mounted(i.e attached) to this tree at ‘/‘, others can be mounted manually using GUI interface(if available) or using mount comman.
  ```sh
  mount
  ```
10. **TTY** - The tty command of terminal basically prints the file name of the terminal connected to standard input. 
  ```sh
  tty
  ```

<!-- USAGE EXAMPLES -->
## More Details

I Found many Beautiful Resource online which explains a bit more about Xargs and mount 

 please refer to the [Beautiful Xargs Resource 1](https://www.tecmint.com/xargs-command-examples/)
 
 
  please refer to the [Mount Resource](https://linuxize.com/post/how-to-mount-and-unmount-file-systems-in-linux/)
