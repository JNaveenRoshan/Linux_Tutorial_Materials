

<p align="center">
  <h3 align="center">How to monitor a specific file in Linux</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Tutorial</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Adding Audit Rule</a></li>
      </ul>
    </li>
    <li><a href="#More Details">More Details</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## How to Monitor/Audit a File or Folder in Linux 





<!-- GETTING STARTED -->
## Getting Started

To monitor or audit a file follow these simple steps.

### Prerequisites

 If you are using any versions of the Linux **Debian**.You may not have the folder audit under the location /var/log so you need to install the auditd package,However if you are using centOS please do ignore the below step
* npm
  ```sh
  sudo apt install auditd
  ```

### Adding Audit Rule

1. Check if any existing audit rules 
   ```sh
   sudo auditctl -l

   ```
2. We want the back_log limit to be around 8k 
   ```sh
   sudo auditctl -s
   ```
3. One can add a audit rule by the following command
   ```sh
   sudo auditctl -w path_to_file -p permissions -k key_name
   ```
   **Note**
   -path_to_file meaning the folder/file location you want to monitor
   
   -permissions corresponds to the permissions that you want to use
   
   -key_name can be anything that you want to use to search for (Custom name)
   
   For more details check the More Details section
   
4. Check whether the custom audit rule is added
   ```sh
   sudo auditctl -l
   ```
5. However any rules you add using auditctl command is temporary when the machine boots up all the rules will wiped

6. To have a permanent set of custom audit rules you need to go to the loaction
   ```sh
   cd /etc/audit/rules.d/
   ```
7. Open the file named audit.rules
   ```sh
   sudo nano audit.rules
   ```
8. Add the following lines at the end of the file
   ```sh
   -w path_to_file -p permissions -k key_name
   ```
9. Save the File 

10. Restart the service
   ```sh
   sudo service auditd restart
   ```
11. Search for the above created custom audit rule in your audit.log file
   ```sh
   sudo ausearch -k key_name
   ```
   **Note:**
   key_name corresponds to the custom name you have used on creating the custom audit rule

<!-- USAGE EXAMPLES -->
## More Details

I found a beautiful resource online which speaks in detail about the audit rules

 please refer to the [Documentation](https://www.digitalocean.com/community/tutorials/how-to-write-custom-system-audit-rules-on-centos-7)





