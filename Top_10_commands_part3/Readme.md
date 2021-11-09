<p align="center">
  <h3 align="center">TOP 10 USEFUL COMMANDS IN LINUX PART 3</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="">View Tutorial</a>
  </p>
</p>


<br />
<br />
<br />

1. **HEAD** - The head command is used to view the first lines of any text file. By default, it will show the first ten lines, but you can change this number to your liking by providing the certain number of lines after the n. 
  ```sh
  head -n 5 <filename.txt> (For first 5 lines)
  ```
2. **TAIL** - This one has a similar function to the head command, but instead of showing the first lines, the tail command will display the last ten lines of a text file
  ```sh
  tail -n 5 <filename.txt>
  ```
3. **DIFF** - Short for difference, the diff command compares the contents of two files line by line. After analyzing the files, it will output the lines that do not match. 
  ```sh
  diff file1.ext file2.ext
  ```
4. **TOP** - This will display a list of running process and how much CPU each process uses
  ```sh
  top
  ```
5. **HISTORY** - grep is a command-line utility for searching plain-text data sets for lines that match a regular expression.
  ```sh
  cat <filename> | grep -i <keyword>
  ```
6. **HOSTNAME** - The Linux truncate command is often used to shrink or extend the size of each FILE to the specified size.
  ```sh
  truncate -s 0 <filename>
  ```
7. **USERS** - uname is a command-line utility that prints basic information about the operating system name and system hardware
  ```sh
  uname -p
  uname -a
  uname -n
  ```
8. **CHMOD** - help command as told before just displays information about shell built-in commands
  ```sh
  <any command> --help
  uname --help
  ```
9. **GETFACL** - Ping is a computer network administration software utility used to test the reachability of a host on an Internet Protocol network.
  ```sh
  ping google.com
  ```
10. **YUM INSTALL** - This works only whilst using ping.It displays the detail about data sent and transmitted
  ```sh
  ctrl + C
  ```

<!-- USAGE EXAMPLES -->
## More Details

I Found many Beautiful Resource online which explains a bit more about chmod and other commands 

 please refer to the [Beautiful Resource 1](https://www.hostinger.in/tutorials/linux-commands)
 
 
  please refer to the [Chmod Resource](https://www.computerhope.com/unix/uchmod.htm)
