
# Connecting the DI meter through SSH

This is a quick start guide for Connecting a meter through SSH



## Authors

- Nagarjuna A
- Manikanthan Shiyam

## Content
- Using Command prompt
- Using Xshell/Putty/Multi Putty
- Using WinSCP for transferring files to the meter

## Pre Requisites:
    1. Meter IP address
        Eg: 10.176.100.139
    2. Username/Host name
        Eg: root
    3. Password
    4. Active VPN connection
    5. Software Tools:
        a. Command prompt
        b. X-shell
        c. Winscp
## Command prompt
This section describes the connecting a meter in Command prompt

Procedure/Steps to connect meter in cmd:

    1. Open cmd
    2. Run the Command: ssh hostname@meter ip address
        hostname: root
        IP address: 10.176.100.139
        Eg: ssh root@10.176.100.139
![CMD Screenshot](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/Connecting%20meter%20using%20SSH.jpg)

    3. Enter the password to connect to meter
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/Password.JPG)

    4. Result: Ash prompt
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/Meter%20connection.JPG)

## X Shell

This section describes the connecting a meter in X Shell

Procedure/Steps to connect meter in X-Shell:

    1. Open X-shell
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/X-Shell.JPG)

    2. Click File -->New and enter the below details
        Name: hostname  Eg: 10.176.100.139
        Protocol: SSH
        Port number: 22
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/X-shell-new.jpg)

![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/X-Shell%20config.png)

    3. Go to Authentication, Enter the username & password and Click on connect

        Username: root
        Password: ****
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/X-Shell%20config%20Auth.jpg)
     
    4. Result: Ash prompt
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/ash%20prompt.JPG)
    
## This section describes the connecting a meter in WinSCP

Procedure/Steps to connect meter in WinSCP:

    1. Open WinSCP
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/WInSCP%20homepage.JPG)

    2. Add the below configuration in WinSCP and Click on Login to connect the meter
            File protocol: SCP
            Hostname: 10.176.100.139
            Port number: 22
            Username: root
            Password: ****
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/WinSCP%20config.JPG)

![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/WInSCP%20connection.JPG)

    3. Copy the files from the directory and paste in WinSCP to transfer the files to meter
![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/WinSCP%20paste.jpg)

![](https://github.com/Nagarjunarjun/Nagarjuna/blob/main/WinSCP%20copying.JPG)

    5. Locate the file in WinSCP after file transfer is completed
