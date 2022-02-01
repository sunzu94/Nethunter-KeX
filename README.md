***Nethunter & kex***

Modified (new) version of **nethunter** and **kex** 

### How Fix kex error
### No matching vnc server,no session,black screen,etc.

Download these two files and copy to location mentioned below and set permission.
**chmod +x nethunter** in termux /usr/bin ,
**chmod +x kex** in kali command line .



Main users : People who use Kali nethunter rootless - Android

Nethunter is a program to start Kali linux in termux and kex client program for managing vnc connection.

### kex.sh

Location : /usr/bin/kex 

Description : A program to start,**repair**,stop,manage,reset configuration files of kex.

Prerequisites : A termux installed with kali nethunter rootless 

Usage : # In termux

        $ nethunter kex <option>

        # Inside kali command line 

        ┌──(kali㉿localhost)-[~]
└─$kex < option >

### nethunter.sh 

Location : /data/data/com.termux/files/usr/bin/nethunter

Description : A program to start kali linux installed on termux

Prerequisites : A termux installed with kali nethunter rootless

Usage : Entering **nethunter** or **nh** in termux which open kali command line. 
 
Example :$nethunter

 ┌──(kali㉿localhost)-[~]
└─$
![Screenshot](https://github.com/AioonT/kex/blob/main/.jpg?raw=true)
![This is an image](https://www.kali.org/docs/nethunter/nethunter-rootless/010-NH-Rootless-Installation_Start_s.png)

Kali rootless : https://www.kali.org/docs/nethunter/nethunter-rootless/
Kali Nethunter : https://www.kali.org/docs/nethunter/
Kali NetHunter (Rootless Edition) : https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/-/blob/master/nethunter-rootless/README.md



i.Possible kex error due to updating which remove necessary files for kex because treating it as a obsolete.

ii.Deletion of configuration files like xstartup

