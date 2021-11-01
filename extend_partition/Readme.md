<p align="center">
  <h3 align="center">Resize a disk partition with unallocated disk space in Linux </h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="https://youtu.be/PgZu4PN50c8">View Tutorial</a>
  </p>
</p>


<br />
<br />
<br />

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#disk partitioning">Disk Partitioning</a></li>
      </ul>
    </li>
    <li><a href="#More Details">More Details</a></li>
  </ol>
</details>


<br />
<br />
<br />



<!-- ABOUT THE PROJECT -->
## User Guide on Resizing/Extending the disk partition in Linux Machine





<!-- GETTING STARTED -->
## Getting Started

We resize/extend the disk partition in order to use all unallocated disk space.

### Prerequisites

 There is no prerequisites for this process.No in-depth knowledge required however to run all the below code please use sudo or run those commands as root user 
  ```sh
  sudo su
  ```

### Disk Partitioning

1. We need know the details of the partition table for the current machine to check whether there are unallocated space.If so what are their starting and ending sectors.To view these detials run the below command
   ```sh
   cfdisk
   ```
2. Make sure there is a column called free space and make a note of the ending sector of that row.Make a note of the file system name you want to increase or extend.Then exit.


3. Type p and press enter to view the partition table again
   ```sh
   p
   ```
4. See the number of the partition record that you want to remove
   ```sh
   sudo ./splunk start
   ```
5. Type d to delete the partition record and then press enter
   ```sh
   d
   ```   

6. Provide the partition record and press enter

7. Type n and press enter to create a new disk partition.Provide the starting and ending sectors.You can choose the default for both of them but check once for validation purposes
   ```sh
   d
   ``` 

8. Type p and then press enter to check the disk partition table is created in a way that you want 
   ```sh
   d
   ``` 
   
9. If everything looks in a way that you want Type w and then press enter to write the partition table to the disk. 
   ```sh
   d
   ``` 
   
   
<!-- USAGE EXAMPLES -->
## More Details

Use the below link for the official documentation of Splunk

 please refer to the [Documentation](https://docs.splunk.com/Documentation/Splunk/8.2.2/Installation/Chooseyourplatform)





