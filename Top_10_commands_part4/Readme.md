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

1. **PS** - The head command is used to view the first lines of any text file. By default, it will show the first ten lines, but you can change this number to your liking by providing the certain number of lines after the n. 
  ```sh
  head -n 5 <filename.txt> (For first 5 lines)
  ```
2. **KILL** - This one has a similar function to the head command, but instead of showing the first lines, the tail command will display the last ten lines of a text file
  ```sh
  tail -n 5 <filename.txt>
  ```
3. **GZIP** - Short for difference, the diff command compares the contents of two files line by line. After analyzing the files, it will output the lines that do not match. 
  ```sh
  diff file1.ext file2.ext
  ```
4. **NETSTAT** - This will display a list of running process and how much CPU each process uses
  ```sh
  top
  ```
5. **CHOWN** - When you’ve been using Linux for a certain period of time, you’ll quickly notice that you can run hundreds of commands every day. As such, running history command is particularly useful if you want to review the commands you’ve entered before.
  ```sh
  history
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
