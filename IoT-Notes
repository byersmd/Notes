# Welcome to the IOT 210B: Internet of Things: Protocols & Networks

This course focuses on connecting devices to the cloud. Youâ€™ll be introduced to
networking, frameworks, application protocols, data representations, security and
the tools used to connect devices to the internet of things. This course builds on
what you learned in the first course (110A), using the Raspberry Pi to understand how
things are connected and represented on the internet. Some of the networks weâ€™ll cover
include ZigBee, Thread, Bluetooth and WiFi. Youâ€™ll explore ecosystems such as IFTT,
Amazon Skills Kit (ASK), and Philips Hue.

This course does not assume any prior knowledge of networking protocols.

This course does assume some amount of Python programming ability.

## Disclaimer

The materials of this course are the property of the University of Washington, and
are not to be posted on the internet or other forums.

They are for the personal use of the students attending the course.


## Instructor and Classroom Information

**Online Meeting Room:** https://uwtest.zoom.us/j/583388263

**Instructor: Drew Gislason**, Email: gislad@uw.edu

**TA: Bryan Palmer**, Email: bpalmer@uw.edu

**Class Sessions:** Thursdays 6:00pm - 9:00pm Pacific, March 30th - June 1st, 2017

**Class Location:** 2445 140th Avenue N.E., Ste. B-100, Bellevue, WA 98005-1879 (Links to an external site.), Room 210

**In-Class Wi-Fi:**  
SSID: **UW-IoT110-R**  
Password: **piIoT110**  (Note: "I" in IoT is  "capital I" and not "capital L")

Topics include:

* Networking and application protocols
* How data is represented on the internet
* Connecting devices to the internet of things
* Securing devices and transactions
* IOT Ecosystems (e.g IFTTT, Philips Hue, Amazon Web Services and Alexa)

## Various Links

[UW-PCE IoT Website](https://www.pce.uw.edu/certificates/internet-of-things)  
[IOT 210B: INTERNET OF THINGS: PROTOCOLS & NETOWRKS](https://www.pce.uw.edu/internet-of-things-protocols-and-networks)  
[Canvas](https://canvas.uw.edu/courses/1113347/pages/front-page)  
[GitLab Home for Labs](https://gitlab.com/Gislason/iot-210B-student)  
[GitLab Home for Slides](https://gitlab.com/Gislason/iot-210B-slides)  

## Setting up RPi3

[RPi3 Setup](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/PI_SETUP.md)

## Assignments and Syllbus

Week | Date | Lab | Description
----- | ------ | ---- | -----
W1 | Mar 30 | [Lab 1](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab1/lab.md) | Setup, Introduction to Networking (OSI 7-Layer Model), TCP/IP, UDP/IP, Sockets
W2 | Apr 6  | [Lab 2](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab2/lab.md) | HTTP, REST, URLs, APIs, Curl, UDP Multicast, Heroku, IPv6 vs IPv4
W3 | Apr 13 | [Lab 3](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab3/lab.md) | JSON vs XML, SSE vs Websockets, MQTT with MQTT-SN, Google Protobufs
W4 | Apr 20 | [Lab 4](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab4/lab.md) | ZigBee Part 1
W5 | Apr 27 | [Lab 5](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab5/lab.md) | ZigBee Part 2
W6 | May 4  | [Lab 6](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab6/lab.md) | ZigBee Part 3, Bluetooth, 6LoWPAN (Thread)
W7 | May 11 | [Lab 7](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab7/lab.md) | Securing IoT Devices and Transactions
W8 | May 18 | [Lab 8](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab8/lab.md) | Philips Hue API, Twitter, other APIs
W9 | May 25 | [Lab 9](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab9/lab.md) | Amazon AWS IoT and Alexa API
W10 | Jun 1 | n/a   | Capstone Projects (Hackathon)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework Week 1

The homework for this week is to complete the Week1 Lab, All parts A-C.

**Reminder: GitLab Repo with your instructor [Drew Gislason](emailto:gislad@uw.edu?subject=GitLab Repo)

This includes all of the following

* Set up Raspberry Pi 3
* Installed Python 2.7
* Installed Flask (python library)
* Installed sense_hat (python library)
* Program to display IPv4 address on boot-up (ipaddr.py)
* Installed Git
* Git clone https://gitlab.com/Gislason/iot-210B-student into Pi3
* Ran and explored the ipv4_udp_server.py, ipv4_udp_client.py
  ipv4_tcp_server.py, ipv4_tcp_client.py which use sockets

The instructions for these can be found in the following files

[Lab Overview](https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab1/lab.md)
[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartA.md) Setup  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartB.md) RPi3 SenseHat and Autoboot  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartC.md) Sockets 

# Main Project Links

[Canvas](https://canvas.uw.edu/courses/1113347/pages/front-page)  
[GitLab Home for Labs](https://gitlab.com/Gislason/iot-210B-student)  
[GitLab Home for Slides](https://gitlab.com/Gislason/iot-210B-slides)  
 

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 1 - Setup, Introduction to Networking (OSI 7-Layer Model), TCP/IP, UDP/IP, Sockets

## Lab Objectives

In this lab you'll learn the following:

* How to setup your Raspberry Pi 3, and all of the tools we'll use for this lab
* How to use SSH (for a headless Pi3)
* The OSI 7-Layer Model of networking
* Where to find specifications for the various layers
* TCP/IP vs UDP/IP
* What a socket is, and how to program sockets in Python
* A Practical way to boot into a Python program on the Raspberry Pi3

## Details

1. **Lecture:** First, we'll have a brief introductory **lecture** about the course, the instructor,
the Internet of Things.
2. **Lab:** In Part A of this lab, you will set up your Raspberry Pi3 (Pi3) and GitLab so you
are ready for the rest of the course. Those who took course 110A have already done
this step.
3. **Lecture:** Next, we'll have a **lecture** about the OSI 7 Layer Model of Networking and explore some
networking concepts.
4. **Lab:** Part B of this lab shows how to set up the Raspberry Pi3 to Autoboot into a program.
Specifically, this Python program will display the IP address of your Pi3 (ipaddr.py).
5. **Lecture:** Another lecture, this time on sockets. What is a socket, how does it work?
6. **Lab:** Part C of this lab will use **sockets** to send/recieve packets, both under
TCP/IP and UDP/IP


## Homework

See the homework link below.

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartA.md) Setup  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartB.md) RPi3 SenseHat and Autoboot  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartC.md) Sockets  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/homework.md) Run through all the labs (Parts A, B and C)  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab1 - PartA (Setup)

In this section of the lab you will

* Set up your Raspberry Pi3
* Install Python 2.7 on Rpi3
* Install Flask Python Library on Rpi3
* Install SenseHat Python Library on Rpi3
* Create a GitLab repo for this class
* Clone the Student GitLab repo on RPi3

## Setup Rpi3

[RPi3 Setup](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/PI_SETUP.md)

## Install Python

[Install Python](https://www.python.org)

## Install Pip

[Install Pip](https://pip.pypa.io/en/stable/installing/)

## Install Flask Python Library

[Install Flask](http://flask.pocoo.org/docs/0.12/installation)

Or simply use pip:  
```
pi$ pip install Flask
```

## Install SenseHat Python Library

![SenseHat](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/rpi_sensehat.png)

The SenseHat library is used to interact with the various sensors and actuators on the
SenseHat device.

```
pi$ pip install sense_hat
```

## Install Git and Curl

Git comes pre-installed on both MAC and The Raspberry Pi 3.

### Install Git on Windows

[Git Tools, includes Curl](https://git-scm.com)

## Git Training

[Git Training](https://try.github.io/levels/1/challenges/1)

## Create GitLab Repo

Create an account if needed (if you don't already have a GitLab account). Then create a
project named something like "iot210-MyName".

Share a link to this project with your instructor Drew Gislason: [gislad@uw.edu](emailto:gislad@uw.edu?subject=GitLab Repo)

See [GitLab](http://www.gitlab.com)

## Clone the Student GitLab Repo

Choose a place for Git Repos and clone the repo

```
cd /where/i/keep/my/git/repos
git clone https://gitlab.com/Gislason/iot-210B-student.git
```

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartA.md) Setup  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartB.md) RPi3 SenseHat and Autoboot  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartC.md) Sockets  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/homework.md) Run through all the labs (Parts A, B and C)  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab1 - PartB (RPi3 SenseHat and Quiz)

![SenseHat](https://gitlab.com/Gislason/iot-210B-student/blob/master/images/rpi_sensehat.png)

In this section of the lab you will

* Learn how to get your local IP Address and autoboot into program
* Explore the SenseHat features

## Autoboot

With an embedded device, it's sometimes useful to boot the device headless (no keyboard
or screen). SSH works well as a terminal window into the device.

Source code is in the `iot-210B-student/Lab1/src` folder.

Copy the file `ipaddr.py` to the Pi3 home directory

```
scp Lab1/src/ipaddr.py pi@iotXxxx/home/pi
```

Add the following line to /etc/rc.local near the end (just before exit 0)

```
python /home/pi/ipaddr.py &
```

Cold boot your Pi3. Once Linux boots up, it should display a 'P' to help you orient
your SenseHat display. Then (after about 10 seconds), it will display your IP address

```
10.0.1.8
```

A couple of improvements that could be made to ipaddr.py:

1. Find a better way to get your local IP address other than connecting to an external site
2. Find a way to know when Wi-Fi has completed connecting and is ready for use


## Explore SenseHat

If you haven't already, install sense_hat package for python.

```
pip install sense_hat
```

In the `iot-210B-student/docs` folder you will find 'Essentials_SenseHAT_v1.pdf`

Open that file and try out the examples in your RPI3. 

Make a Python Program that does something interesting. Show your instructor (or cat
if working remotely)

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartA.md) Setup  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartB.md) RPi3 SenseHat and Autoboot  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartC.md) Sockets  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/homework.md) Run through all the labs (Parts A, B and C)  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab1 - PartC (Sockets)

In this section of the lab you will

* Learn the difference between TCP/IP and UDP/IP
* Learn how to use sockets from both a Client and Server Perspective

These apps can be run from the Raspberry Pi in terminal windows, or on your PC

## UDP

From `iot-210B-student/Lab1/src` 

In one terminal window, run:  
```
$ python ipv4_udp_server.py
```

The server will sit and wait for incoming packets

In another terminal window, run:  
```
$ python ipv4_udp_client.py
```

Experiment with different IP ports and messages. You can even send a message to someone else's
PI.

```
$ python ipv4_udp_client.py message ip_addr port
```

Ports can be anything from 1024 - 65000. Ports < 1024 are reserved for various services.


## TCP

From `iot-210B-student/Lab1/src` 

In one terminal window, run:  
```
$ python ipv4_tcp_server.py
```

The server will sit and wait for an incoming connection

In another terminal window, run:  
```
$ python ipv4_tcp_client.py
```

Experiment with different IP ports and messages. You can even send a message to someone else's
PI.

```
$ python ipv4_tcp_client.py message ip_addr port
```

Ports can be anything from 1024 - 65000. Ports < 1024 are reserved for various services.

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartA.md) Setup  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartB.md) RPi3 SenseHat and Autoboot  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/LabPartC.md) Sockets  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/homework.md) Run through all the labs (Parts A, B and C)  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

## Setting up RPi3 for the IoT 110,210,320 Classes

### Summary of Setup Steps
* [OPT] Download OS from RaspberryPi Foundation
* ( 1) Set Hardcoded Screen Resolution for mini HDMI monitor
* ( 2) Expand the filesystem
* ( 3) Setup WiFi connection
* ( 4) Establish a Command Line Interface (CLI)
* ( 5) Ensure a US Keyboard mapping
* ( 6) Set up a hostname unique for your PI (using its last 4 digits MAC address for wlan)
* ( 7) Enable Serial Ports and GPIO for Labs
* ( 8) Set up local hostname resolution for the IOT class (or home) network
* ( 9) SSH -> iot1234
* (10) Mapping PI filesystem into host's
* (11) Update OS and install a few utilities and check versions

<hr>
### [OPTIONAL] Downloading and burning a new image (if you wish to have the latest OS or burn your own image)
[RASPBIAN JESSIE WITH PIXEL](https://www.raspberrypi.org/downloads/raspbian/)
Image with PIXEL desktop based on Debian Jessie

[RASPBIAN JESSIE LITE](https://www.raspberrypi.org/downloads/raspbian/)
Minimal image based on Debian Jessie

[Optional Configuration Link](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-2-first-time-configuration/using-the-whole-sd-card?view=all)
<hr>
### STEP 1: Mini Display 480x800 pixels

**Skip this step if using a desktop HDMI display (as opposed to the the one used in Class IoT 110A.**

This display will not boot a screen on default.  The config.txt file must be
modified according to the instructions on Adafruit.  (config.txt is located on the SD card and you must insert the card into your host computer to edit)
[Display Config Changes](https://learn.adafruit.com/adafruit-5-800x480-tft-hdmi-monitor-touchscreen-backpack/raspberry-pi-config)
In case that site goes down, here's a summary of the changes in config.txt:
```
# uncomment if hdmi display is not detected and composite is being output
hdmi_force_hotplug=1

# uncomment to force a specific HDMI mode (here we are forcing 800x480!)
hdmi_group=2
hdmi_mode=87
hdmi_cvt=800 480 60 6 0 0 0
```
<hr>
#### [GENERAL INFO] Check the Raspberry PI Settings/Preferences
Start > Preferences > Raspberry Pi Configuration
![Raspberry Pi Settings](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/Preferences.png)

<hr>

### STEP 2: Expanding Filesystem
**Objective:** The default SD card operating systems shipped out of the box
often are not expanded to the full extent of the size of the SD card.  This is
also true if you have downloaded an operating system image (see above) and
burned it onto the card.  The image size may only be 1-2GB but the card might be
8GB to 64GB for example.  We therefore will want to have ALL of the SD card
file system available to the RPi. It is very important to do this at the **VERY
BEGINNING OF SETUP** otherwise you may find yourself out of disk space and in a
"bricked" state.  In this case, you will need to perform the OPTIONAL step above
and start over with a fresh image install.<br><br>
![Expand File System](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/expand.png)

After expanding and rebooting as required, open a terminal and check to ensure
that the filesystem was indeed expanded.<br><br>
![File System Size Check](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/df_dash_h.png)
<br>
<hr>
### STEP 3: Setup WiFi Connection
Apple Airport access points have been configured for our IoT classroom.  There
are 2 access points because they each have a limit of 50 client connections.  
To attempt to keep things simple we will join to only one of the access points
(UW-IoT110-R) until we either have:<br>
a) run out of 50 client connections<br>
  or<br>
b) we have a failure on one access point.<br>

Using the mouse and hovering over the WiFi connection ICON, select SSID and
enter the password given below:<br>
Airports have SSIDs of UW-IoT110-R (primary) and UW-IoT110-L (secondary).  
Password: **piIoT110**  (Note: "I" in IoT is  "capital I" and not "capital L")
<br><br>
![WiFi Settings Panel](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/SSID.png)
<br>
<hr>
### STEP 4: Command line shell ###
For MacOSX or Linux users, just use the normal "terminal" for your Command Line
Interface (CLI).<br>

For Windows users, it maybe best to download the GIT Bash tool (git is built
into Linux and MacOSX terminal shells).
[Download GIT](https://git-scm.com/downloads)

NOTE: For the following command line entries we use the following to
indicate which machine you are on.
```
pi$  => this is a command on the RPi3

host$ => this is a command on your development host (Windows PC or MAC)
```

#### Check to see if connected to the public Internet
```
pi$ ping google.com
```

#### Determine IP address of RPi
```
pi$ ifconfig | grep "inet addr"
=> inet addr:192.168.10.19  Bcast:192.168.1.255  Mask:255.255.255.0
```


### Step 5: Ensure a US Keyboard Mapping
![Keyboard Setting](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/Keyboard.png)


### Step 6: Setup a unique hostname based on wlan MAC
```
pi$ ifconfig | grep wlan0  
=> wlan0     Link encap:Ethernet  HWaddr b8:27:eb:e9:12:34  
=> choose the last 4 digits of the MAC => [1234]

pi$ sudo vi /etc/hostname

=> remove current hostname and replace with "iot1234"
=> using the [HWaddr] from above network queries
```
Alternatively the hostname can be set from the Preferences panel.
![Hostname Preferences UI](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/hostname.png)

### Step 7: Enable I2C Serial Port (and GPIO if Pixel OS) for Labs
![Raspberry Pi I/O Port Settings](https://gitlab.com/Gislason/iot-210B-student/raw/master/images/interfaces.png)

#### Reboot
```
pi$ reboot
```

<hr>
### STEP 8: Using Hostname Resolution on Network
```
// start the avahi-daemon network service
pi$ systemctl status avahi-daemon
  => Verify that the hostname matches the name changed to above
Loaded: loaded (/lib/systemd/system/avahi-daemon.service; enabled)
Active: active (running) since Sun 2016-11-13 23:15:20 UTC; 15min ago
Main PID: 438 (avahi-daemon)
  Status: "avahi-daemon 0.6.31 starting up."
  CGroup: /system.slice/avahi-daemon.service
          â”œâ”€438 avahi-daemon: running [iot1234.local]
          â””â”€465 avahi-daemon: chroot helper

host$ ping iot1234
PING iot1234.home (192.168.10.19): 56 data bytes
64 bytes from 192.168.10.19: icmp_seq=0 ttl=64 time=10.863 ms
64 bytes from 192.168.10.19: icmp_seq=1 ttl=64 time=7.657 ms
64 bytes from 192.168.10.19: icmp_seq=2 ttl=64 time=7.024 ms      

```
<hr>
### STEP 9: Setting up SSH
**Objective:** Establishing ssh connection is the most universal way to connect
two computers together over a network (local or global).  This also automatically
provides public key infrastructure (PKI) security which is the standard for
Internet Security.  Establishing SSH keys allows for password free log in
between systems which is not only convenient (when a trust is established) but
essential when automating connectivity --as we will be doing for our class.  We
will be using SSH to routinely log into our machines as well as utilizing a
capbility known as SSHFS (i.e. File System mapping over SSH).

```
// ------- RPi KEY SETUP ----------
// log into RPi iot1234 (with password => "raspberry")
host$ ssh pi@iot1234  // answer yes to the one time prompt for host signature
                            // passwd default: "raspberry"
pi$ cd .ssh                 // change dir to .ssh if it exists, mkdir if it doesn't
pi$ ssh-keygen              // generate an ssh key (RSA)
=> Enter file in which to save the key (/home/pi/.ssh/id_rsa):
                            // hit <enter> 3 times

pi$ cp id_rsa.pub  id_rsa_iot1234.pub
pi$ exit                    // success! now exit and set up an SSH key for host
```

**(IF YOU ALREADY HAVE AN SSH HOST KEY PLEASE SKIP THE HOST PORTION)**

```
// ------- HOST KEY SETUP ----------
// generatate (or use) a ssh key on the host (IF YOU ALREADY HAVE A KEY
host$ cd ~/.ssh
host$ ssh-keygen            
=> Enter file in which to save the key (/home/pi/.ssh/id_rsa):
                            // hit <enter> 3 times

host$ cp id_rsa.pub id_rsa_XYZ.pub  // Use a unique XYZ id from your host machine
host$ scp id_rsa_XYZ.pub pi@iot1234:.ssh
host$ ssh pi@iot1234                // enter passwd (for the last time!)

// install the ssh host key on iot708c
pi$ cd .ssh
pi$ cat id_rsa_XYZ.pub >> authorized_keys
pi$ exit  

// test the ssh key
host$ ssh pi@iot1234  // should be passwd free now!
pi$ exit  
```
<hr>
### STEP 10: Mapping PI filesystem into host's
**Objective:** It is *very convenient* to map the RPi's filesystem into your
development host as if it is just another folder on your host.  This allows the
use of native and powerful code friendly editors (e.g. Atom or Sublime) in which
to edit source code.  Because the RPi's file system is mapped there is no need
to transfer code back and forth to the RPi.  In Linux-speak mapping a target
filesystem like this is known as *mounting the file system*.

Create a folder on the RPi under ```Documents/``` called ```GIT_REPOS``` 
(e.g. Documents/GIT_REPOS)

Must install sshfs capability in order to mount file system then...
#### sshfs for MacOSX
[FUSE for macOS](https://osxfuse.github.io/)   // install **BOTH** fuse and sshfs pkgs

Create directories on development host to mount each PI (e.g. PI_MOUNT_1234)
then mount them using sshfs.

``` sh
host$ sshfs pi@iot1234:Documents/GIT_REPOS PI_MOUNT_1234/ -C

```

disconnect from the PI file systems
```
host$ umount PI_MOUNT_1234/
```

#### sshfs for Windows 7/8/10
[SSHFS Win10](https://igikorn.com/sshfs-windows-10/)   // install Win sshfs pkg

Follow the instructions to set up a GUI based SSHFS capability for Windows
development hosts.

<hr>
### STEP 11: Update OS and install a few utilities and check versions
**Objective:** It is always a good idea to keep Linux systems such as the
Debian OS (Raspbian) updated with the latest improvements coming from the large
open source community such as enjoyed by the Raspberry Pi platform.  As a final
stage of our PI setup we will make sure we have an updated OS.

``` bash
host$ ssh pi@iot1234

pi$ sudo apt install rpi-update
pi$ sudo rpi-update
pi$ uname -a

```

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

A Special Thank You to Josh Welschmeyer for the Heroku instructions

# Homework

The homework is to set up your own Heroku account and host quizical.py (or your own app).
Provide a link to your instructor.

**Important:** create a NEW folder NOT inside your student repository, as you can't have a git
repository inside another one.

```
  my_student_git_repo
  my_heroku_git_repo
```

Heroku URLs use two random words, and a random # (e.g. frozen-castle-53348)

# Installing and Running Heroku Steps in Detail

## Step 1) Sign Up / Verify Account etc.

[http://www.heroku.com](http://www.heroku.com)

## Step 2) Setting up local machine

### Install Python 2.7

- Windows [http://docs.python-guide.org/en/latest/starting/install/win/](http://docs.python-guide.org/en/latest/starting/install/win/)

- OSX [http://docs.python-guide.org/en/latest/starting/install/osx/](http://docs.python-guide.org/en/latest/starting/install/osx/)

- Linux [http://docs.python-guide.org/en/latest/starting/install/linux/](http://docs.python-guide.org/en/latest/starting/install/linux/)


### Install Depenedencies

#### Install Pip

Download [https://bootstrap.pypa.io/get-pip.py](https://bootstrap.pypa.io/get-pip.py)

- Windows / OSX `python get-pip.py`

- Linux (sudo apt-get install python-pip)

#### Other Dependencies

- sudo pip install flask

#### Install heroku CLI
 
[https://devcenter.heroku.com/articles/heroku-cli#download-and-install](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)

`$ heroku login`

## Step 3) Create Heroku App

```bash
$ heroku create --buildpack heroku/python
Creating app... done, thawing-hamlet-90035
https://thawing-hamlet-90035.herokuapp.com/ | https://git.heroku.com/thawing-hamlet-90035.git

$ git init
Initialized empty Git repository in <PATH>.git/

$ heroku git:remote -a thawing-hamlet-90035
set git remote heroku to https://git.heroku.com/thawing-hamlet-90035.git
```

## Step 4)

Define Procfile

```text
web: gunicorn app:app --log-file=-
```

Define requirements.txt

```text
Flask
Flask-HTTPAuth
gunicorn
```

## Step 5)

```bash
git add
git commit
git push heroku master
```

-----

## Notes:

**using the heroku cli**

```bash
$ heroku help
$ heroku apps                # list all apps
heroku logs                  # display logs for your app
heroku config:set KEY=VALUE  # set config variable
heroku config:get KEY        # get config variable
heroku config:unset KEY      # unset config variable
```

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 2 - HTTP, REST, URLs, APIs, Curl, UDP Multicast, Heroku, IPv6 vs IPv4

## Lab Objectives

In this lab you'll learn the following:

* Learn common IP protocols: HTTP, REST, URLs, and APIs
* Learn curl, a useful tool for APIs
* Use that knowledge with Quizical Flask Server
* The difference between IPv6 and IPv4
* How to multicast to a network
* How to create an application in the cloud using Heroku)


## Homework

Setup a free Heroku account for hosting your own IoT applications. Host Quizical and send
a link to me.


## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) 
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) IPv4 vs IPv6, understand some issues with IPv6    
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/homework.md) Move Quizical to your own free Heroku account  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab7 Part A - Cryptographics 

In this section of the lab you will learn

* Hash functions and when to use them
* Encryption algorithms and when to use them
* Public-key algorithms and when to use them

We'll use the Rapsberry Pi for exploring cryptography.

## Step 1 - Install pycrypto

Install pycrypt on your Rapsberry Pi

Either: 

```
pi$ sudo apt-get install python-crypto
```

Or do: 

```
pi$ sudo apt-get install python2.7-dev
pi$ sudo pip install pycrypto
```

Verify installation worked

```
pi$ python
>>> from Crypto.Hash import SHA256
>>> hash = SHA256.new('Hello World').hexdigest()
>>> print 'hash len(' + str(len(hash) / 2) + ') ' + hash
```

## Step 2 - Hash Algorithms

This explores hashing by making a user/password file.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab7/src
pi$ iotsha256.py
```

Try entering a few different users and passwords by pressing Enter (no name)
to create new users.

Try logging into each account by typing username and password.

Try logging in with the wrong password.

Let's examine the file passwords.txt.

Easy: guess the password for user 'hello'.

Bonus: See if you can determine the password for user "drew".


## Step 3 - Block Cipher (AES)

This lab uses MQTT to send/receive encrypted text.

This uses a global built-in key.

```
pi$ python mqtt_subscribe_aes.py
```

In another SSH terminal window on your Raspberry PI, run the MQTT
publish application. This requires you to enter a key

```
pi$ python mqtt_publish_aes.py secretkey
```

Publish some lines of text. Notice the text is encoded on sending,
and decoded on receiving at the Subscriber.

Try changing your key on the subscriber (by editing the mqtt_subscribe_aes.py).

Make sure to change the key on the cmdline for the publisher.

Note: the AES key must either by 16 bytes (AES-128) or 32 bytes (AES-256)


## Step 4 - Public Key (RSA)

```
pi$ python iotpki.py The quick brown fox jumped over the lazy dog.
```

## Step 5 - Signing a Public Key

Sign

Signing a message can be useful to check the author of a message and make
sure we can trust its origin. Next is an example on how to sign a message.
The hash for this message is calculated first and then passed to the
sign() method of the RSA key.

Start by running python from SSH on the Rapsberry Pi.

**Signing** 

```
$pi python
>>> from Crypto.Hash import SHA256
>>> from Crypto.PublicKey import RSA
>>> from Crypto import Random
>>> random_generator = Random.new().read
>>> key = RSA.generate(1024, random_generator)
>>> text = 'my_signature'
>>> hash = SHA256.new(text).digest()
>>> signature = key.sign(hash, '')
>>> public_key = key.publickey()
```

**Verify**

Knowing the public key, it is easy to verify a message. The plain text is sent
to the user along with the signature. The receiving side calculates the hash
value and then uses the public key verify() method to validate its origin.

```
>>> text = 'my_signature'
>>> hash = SHA256.new(text).digest()
>>> public_key.verify(hash, signature)
True

>>> text = 'not_my_signature'
>>> hash = SHA256.new(text).digest()
>>> public_key.verify(hash, signature)
False
```

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) WPA2 and Access Points  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) TLS and self-signed certs  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) Move Quizical to your own free Heroku account  


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

Lab2 Part B - Quizical, A more complicate API, with secure tokens

# Quizical

Quizical is a multiple-choice quiz engine using Python and Flask. It's
designed to instruct how APIs can be designed, and how to use all HTTP VERBs
in actual commands. It will later be used to host an application on the
internet.

Go to the GitLab Wiki to see the Quizzical documentation.

## Overview

The instructor will run Quizical on his machine for those working in the classroom. Everyone
on the local network should be able to participate.

If you are working remotely, or wish to run your own quiz, run quizzical yourself (it can
run in the raspberry PI). See Remote Instructions.


## Quiz Client

Open another terminal window for the Client application, quiz.py

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab2/src
pi$ python quiz.py
```

You should log in with your firstname, last initial, and your lastname as your password. For
example, if your name is matt smith, your username is `matts` and your password is `smith`.

```
Enter Username (e.g. me): me
Enter Password (e.g. pass): pass
token=smUG5gJ83hxiOgQFRXv5

Quiz: osi7layer question: 1
What best describes the PHY layer?
 A. It is the physical modulation layer (e.g. wireless or wired)
 B. It is for medical (physician) devices
 C. It is for signal quality (fidelity)
 D. It is the study of plants (phytology)
Your answer: A

Wait for your instructor to post the next question
```

Make sure wait after posting each answer, otherwise, the quiz will stop. This isn't a rich UI
quiz engine, just a simple demonstration.

# Remote Instructions

In one terminal window run the Quizical Server.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab2/src
pi$ python quizical.py
```

If you want to move on to the next question, you must act as your own instructor. Use
curl to do this in yet another terminal window: Copy the token into to use with curl.

```
pi$ curl localhost:5000/api/v1/login/drewg?pwd=gislason
pi$ curl localhost:5000/api/v1/teacher/quiz?token=smUG5gJ83hxiOgQFRXvF -X PUT \
-d '{"question":"2","answer":"C"}'
```

To end the quiz, use {"name":"done"} for the data.

To see quiz results for all students, use:

```
$pi curl localhost:5000/api/v1/teacher/results?token=smUG5gJ83hxiOgQFRXvF
```

FYI, `localhost` and `127.0.0.1` are the same.


## Try Making Your own Quiz or adding your own users

Modify quizical.py to contain your own multiple choice quiz.

For now, you'll need to modify the quizical.py program. However, the API could
be extended to POST new quizzes and to add/remove users.

Host quizical on your own PI (see instructions for remote use), and try out your
quiz.


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

Lab2 Part B - IPv6 vs IPv4

# Use ifconfig to find out your 

```
$pi ifconfig | grep inet

  inet 127.0.0.1 netmask 0xff000000 
  inet6 ::1 prefixlen 128 
  inet6 fe80::1%lo0 prefixlen 64 scopeid 0x1 
  inet6 fe80::494:eaba:18ea:2955%en0 prefixlen 64 secured scopeid 0x4 
  inet 172.27.40.103 netmask 0xffffff00 broadcast 172.27.40.255
  inet6 fc00:1::c38:b3d9:1366:80a2 prefixlen 64 autoconf secured 
  inet6 fc00:1::75b2:dd8:f250:2de9 prefixlen 64 autoconf temporary 
  inet6 fc00:1::d932 prefixlen 64 dynamic 
  inet6 fe80::3072:afff:febc:95b1%awdl0 prefixlen 64 scopeid 0x8 
  inet6 fe80::68e4:5bb7:4b84:cd5f%utun0 prefixlen 64 scopeid 0xa 
  inet6 fe80::5b8e:9097:223c:7003%utun1 prefixlen 64 scopeid 0xb 
```

# Printing Routes

  Windows: route print

  MAC / Linux: netstat -nr


# IPv6 client and server

This lab is very simple. Take a look at the ipv6client.py and ipv6server.py

In a terminal window, run

```
$pi cd ~/Documents/Git/iot-210B-student/Lab2/src
$pi python ipv6server.py
```

In another terminal window, run

```
$pi cd ~/Documents/Git/iot-210B-student/Lab2/src
$pi python ipv6client.py
```

# Experiments

Try sending data to another server in the same classroom (on the same subnet).

Try sending data to another server across the internet (elsewhere)

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

Lab2 Part D - Multicast

Note: If working remotely, you will want to have a terminal on your PC, or have two
Raspberry Pi devices on your same Wi-Fi (or wired) network.

Broadcasts do not go to yourself.


# Step 1 - Setup UDP Server

Open an SSH Terminal into the RPi3. Run the UDP server.

```
$pi cd ~/Documents/Git/iot-210B-student/Lab2/src
$pi python ipv4_udp_server.py
```

# Step 2 - Find Multicast Address on your RPi3

Look for the Bcast interface. This isn't really a broadcast,
but a multicast on your subnet. (e.g. 172.22.194.255)

```
$pi ifconfig | grep inet
```

# Step 3 - Run UDP Client

**Open another SSH terminal** into your RPi3.

Modify the UDP client default address to broadcast. Important,
You must also modify the socket options to allow broadcasting.


Try sending messages to each other unicast (e.g. to iot40a2.local) and broadcast to all in the room


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
# Quizical Documentation

Quizical is an easy to use quiz API.


## APIs

Verb   | API                             | Description
------ | ------------------------------- | --------------------------------------------------------
GET    | /api/v1/login/{name}            | Login to Quizical. Receive a token for subsequent calls.
PUT    | /api/v1/profile                 | Used to change user password. Requires the login token.
GET    | /api/v1/student/question        | Get the current question with possible answers.
GET    | /api/v1/student/answer          | Your quiz results so far.
PUT    | /api/v1/student/answer          | Answer a question. Write once.
GET    | /api/v1/teacher/quiz            | Get the current quiz
PUT    | /api/v1/teacher/quiz            | Start a new quiz, move quiz on to next question, etc...
POST   | /api/v1/teacher/quiz            | Create a new quiz (clears all student answers)
DELETE | /api/v1/teacher/quiz            | Delete a quiz by name
GET    | /api/v1/teacher/results         | Results for all students
GET    | /api/v1/teacher/admin           | Get the list of students
POST   | /api/v1/teacher/admin           | Post a list of students


## CURL Script Examples

Curl is a general purpose tool. Below are the important bits.

```
  curl http://vcabin.swiftwater.lab/api/v1/student/{name}/question \
    -X verb \
    -H "Content-Type: application/json" \
    â€“d 'data'
    --verbose
```
It's available by default on the Mac (in the Terminal app), and in Windows via Cygwin or the Windows 10 Bash shell.

The --verbose is not needed, but can help understand HTTP, and can be useful for debugging.

The `Content-Type: application/json` header is not needed, as quizical.py assumes JSON.

For all examples below, the student is named "me" and the password "pass", and the login token is "xxxx".

The quizical.py application is assumed to be hosted at `https://frozen-castle-53348.herokuapp.com` (port 443).

### /api/v1/login/{name}

**Methods: GET**

Login to Quizical. Receive a token for subsequent calls

```
curl https://frozen-castle-53348.herokuapp.com/api/v1/login/me?pwd=pass
```

Returns a token, in JSON form, that must be used on all subsequent calls as a parameter.

```
{"token":"xxxx"}
```

If either the username or password is wrong, a `403 Forbidden` is returned.

### /api/v1/profile

**Methods: PUT**

Used to change user password. Requires the login token.

```
curl https://frozen-castle-53348.herokuapp.com/api/v1/profile?token=xxxx -X PUT -d '{"newpwd":"pass"}'
```


### /api/v1/student/question

**Methods: GET**

Get the current question with possible answers.

```
curl https://frozen-castle-53348.herokuapp.com/api/v1/student/question?token=xxxx
```

Returns the current quiz name and question, with all possible answers.

```
{"quizname":{"1":[ "ques"," a1"," a2"," a3"," a4" ]}}
```


### /api/v1/student/answer

**Methods: GET, PUT**

Returns your quiz results so far (GET), or allows a question to be answered (PUT).

Note: Each question can only be answered once (that is, if you PUT a second time it will return with the
answer unchanged).

```
# get answers so far
curl https://frozen-castle-53348.herokuapp.com/api/v1/student/answer?token=xxxx

# Answer question 2 with multiple choice 'D'
curl https://frozen-castle-53348.herokuapp.com/api/v1/student/answer?token=xxxx -X PUT -d '{"2":"D"}'
```

Returns `200 OK` and the following JSON:

```
{"correct":True,"results":"1/4","answers":{"1":"B","2":"D"}}
```

In the results above, the student has gotten one answer right out of 4.

If token is not valid, then returns `403 Forbidden`.


### /api/v1/teacher/quiz

**Methods: GET, PUT, POST, DELETE**

This API allows the teacher to view (GET), create (POST), start/continue (PUT) and delete (DELETE) quizzes.

```
# get the current quiz
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx

# create a new quiz
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx -X POST \
-d '{"python":{"questions":{"1":["ques"," A", "*B"],"2":["ques","*A"," B"]}}}'

# start the quiz
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx -X PUT -d '{"name":"python","question":"1","answer":"B","reset":true}'

# go to question 2 in quiz
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx -X PUT -d '{"question":"2","answer":"D"}'

# delete a quiz
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx -X DELETE -d '{"name":"python"}'
```

A quiz is defined by a unique name and a set of questions. Each question is an array, where element 0 is the
question, and all other elements are the answers. The 1st character of each answer must either be a space (for
incorrect answer) or with a '*' to indicate correct answer.

The '*' is removed (so the student doesn't know the correct answer) when viewing the question through the
`/api/v1/student/question` interface.

Returns 400 Bad Request if the quiz is not in the proper form.

### /api/v1/teacher/results

**Methods: GET**

This API allows the teacher to retrieve results of the quiz for all students. The option `anon`
allows the student names to be anonymous.

```
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/results?token=xxxx?anon=1
```
{
  "drewg": { "results":"4/4", "answers":{"1":"A","2":"C","3":"D","4":"C"}}
}

### /api/v1/teacher/admin

**Methods: GET**

Get the list of students (GET) or post a list of students (POST)

```
# get the list of students
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/admin?token=xxxx

# post a new list of students
curl https://frozen-castle-53348.herokuapp.com/api/v1/teacher/quiz?token=xxxx -X POST \
-d '{"name1":{"pwd":"pass","access":0,"token":"-","answers":"-"}}'
```

Returns JSON list of students.

```
{"name1":{"pwd":"pass","access":0,"token":"-","results":"-","answers":{}}}
```

Returns 400 Bad Request if student list is not in the proper form.
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework

The homework is to install the Texas Instruments ZigBee Software on your
Microsoft **Windows** laptop. If you run macOS or Linux, you'll need to
install a Windows virtual machine.

Many of the embedded tools run on Windows only (some only on older versions
such as Window 7 or even Windows XP). All the tools we use in class should
run on Windows 10 just fine.

# Step 1 - Hardware - CC2650 LaunchPad

You'll need at least one Texas Instruments CC2650 Launchpad. If working
remotely, get 2.

I recommend you order from DigiKey (as you can get it in a couple of days or less).

https://www.digikey.com/en/product-highlight/t/texas-instruments/launchxl-cc2650-launchpad-kit

See also: http://www.ti.com/tool/launchxl-cc2650

**Optionally** get an 802.15.4 Sniffer (to watch packets).

http://www.ti.com/tool/cc2531emk

Digi-Key has it labled wrong (RFID rather that 802.15.4), but this is a sniffer: 

https://www.digikey.com/product-detail/en/texas-instruments/CC2531EMK/296-28921-ND/2231688


# Step 2 - Download the SimpleLink App in your Phone

If you have a smart phone (Android or Apple), you can Download
the Texas Instruments `Simplelink Starter` app from Apple App
Store or Google Play.

If you have the CC2650 LaunchPad hardware, you can verify it all
works, as it has a Bluetooth application ready to go out-of-box.

1. Plug LaunchPad into power (you can use one of your USB chargers or your laptop
2. Launch the SimpleLink Starter app
3. Press (and hold!) the BTN-2 button on the LaunchPad
4. Select the LaunchPad from the menu of Bluetooth Smart Devices
5. Select Mission Control
6. Turn on/off LEDs
7. Try out buttons (it will indicate on screen the state of BTN-1 and 2


# Step 3 - Download and Install Texas Instruments Software

http://processors.wiki.ti.com/index.php/CC2650_LaunchPad_User%27s_Guide_for_ZigBee

Follow the instructions down to and including the "Software" heading,
including downloading and installing

* Z-Stack Home 1.2.2a SDK
* TI-RTOS for SimpleLink Wireless MCUs
* IAR for ARM (EWARM) Embedded WorkBench ARM (see IAR below)

We'll be going through the "Porting Z-Stack Home) and setting up
the actual LaunchPad boards with ZigBee programs in class.

# Step 4 - Download and Install IAR

IAR (https://www.iar.com) Embedded WorkBench for ARM is a C compiler
and debugging environment. ARM processors for ZigBee, Thread and
Bluetooth are very popular and IAR EWARM is supported by NXP, TI,
SiLabs and others.

If you already have **IAR 7.40.2 for ARM** or later installed on
your Windows machine, you are fine.

IAR has a 30-day free trial. If you've already used a 30-day trial and can't
install it, call IAR and explain your are taking the UW IoT 210 course and
they should give you another 30-day free trial.

https://www.iar.com/iar-embedded-workbench/#!?currentTab=free-trials

Do NOT install the KickStart size-limited version, as it cannot build
the ZigBee programs. Choose the 30-day time-limited version instead.

# Step 5 - Download and Install Ubiqua Protocol Analyzer

If you got the Sniffer, or want to analyze packets, you can
use the following software.

www.ubilogix.com

Download 30-Day free trial




[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 3 - Google Protobufs, JSON vs XML, Schemas, SSE vs Websockets, MQTT with MQTT-SN, 

## Lab Objectives

In this lab you'll learn:

* How to add Google protobufs into Python, how to create .proto files and use them in applications.
* The difference between JSON and XML.
* How to use JSON and XML schemas.
* How to use Websockets and SSE.
* How to connect an MQTT-SN broker to an MQTT broker to support lossy networks.


## Homework

Set up an account and install ZigBee Home Automation 1.2 from www.ti.com. 

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartA.md) Google Protobufs and how to use them  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartB.md) JSON,XML and Schemas  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartC.md) WebSockets and SSE  
[PART D](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartD.md) MQTT and MQTT-SN  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab2/homework.md) Install ZigBee Home Automation 1.2  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab3 Part A - Google Protobufs and How to Use Them

Total Lab Time: 45 minutes

In this section of the lab you will

* Learn what Google protobufs are, and when to use them
* Learn what a .proto file is, and how to design one
* How to install Google protobufs on the Pi for Python
* Take the quiz using protobufs (instead of JSON)

## Some Useful Protobuf Links

**Tutorials**  
https://developers.google.com/protocol-buffers/
https://developers.google.com/protocol-buffers/docs/pythontutorial

**Source**  
https://github.com/google/protobuf
https://github.com/google/protobuf/releases

## Step1 - Verify you have enough disk space (you'll need about 2G free)

Open a terminal window on your RPi3 with ssh. Then check disk space.

```
$pi df -h
Filesystem      Size  Used Avail Use% Mounted on
/dev/root        59G  4.2G   52G   8% /
devtmpfs        459M     0  459M   0% /dev
tmpfs           463M     0  463M   0% /dev/shm
tmpfs           463M  6.3M  457M   2% /run
tmpfs           5.0M  4.0K  5.0M   1% /run/lock
tmpfs           463M     0  463M   0% /sys/fs/cgroup
/dev/mmcblk0p1   63M   21M   43M  34% /boot
tmpfs            93M     0   93M   0% /run/user/1000
```

Make sure you have at least 2G Avail on /dev/root.

## Step 2 - Install Google Protobufs 3.2 on your Raspberry Pi

Open another ssh terminal into the RPi3.

A release file from `https://github.com/google/protobuf/releases`
is already in the git project. Make sure to pull the latest.

Then, unzip that project into a new folder.

```
pi$ cd ~/Documents/Git/iot-210B-student
pi$ git pull
pi$ cd ~/Documents
pi$ unzip Git/iot-210B-student/Lab3/src/protobuf-3.2.0.zip
pi$ ls protobuf-3.2.0
```
You should see many files/folders in folder `protobuf-3.2.0`.


## Step 3 - Install the tools needed to build protobufs

The RPi3 by default doesn't have autoconf, automake or libtool installed.
Install those.

```
pi$ sudo apt-get update
pi$ sudo apt-get install autoconf automake libtool
```

# Step 4 - Building protoc

The configure is fairly fast.

The **make takes a REALLY LONG TIME** on the RPi. It took 7 minutes on my MAC. It
took over 45 minutes on my Pi. We'll stop here and wait for it to complete. While
we're waiting, more lecture!

```
pi$ cd ~/Documents/protobuf-3.2.0
pi$ ./configure
pi$ make
```

# Step 5 - Installing protoc

Once done making, then install protoc.

```
pi$ sudo make install
pi$ sudo ldconfig # refresh shared library cache.
pi$ protoc --version
    libprotoc 3.2.0 
```

# Step 6 - Add Protobufs to Python

Next, you need to add protobufs to your python folders. This should take
about 3 minutes.

```
pi$ cd ~/Documents/protobuf-3.2.0/python
pi$ python setup.py build
pi$ python setup.py test
pi$ sudo python setup.py install
```

# Step 7 - Running the Address Book Application

Now that everything is installed, you can actually use protobufs in your RPi3.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ python list_people.py book
Person ID: 1
  Name: Drew
  E-mail address: drewg@rockisland.com
  Home phone #: 555-1212
Person ID: 2
  Name: Alicia Gislason
  E-mail address: alicigislason@icloud.com
  Work phone #: 444-2222
```

Or try adding an entry

```
pi$ python add_person.py book
```

# Step 8 - Try Creating a Protobuf Program from Scratch

The following simple.proto file defines a single integer. 

```
syntax = "proto3";
message Test1 {
  int32 a = 1;
}
```

The program simple.py won't run until a file called "simple_pb2.py" is
created.

```
pi$ python simple.py
```

Notice it fails to run (can't import simple_pb2.py). Now, compile the
simple.proto file into a python module.

```
pi$ protoc --python_out=. simple.proto
pi$ python simple.py
    Enter number: 150
    created 'simple.bin'
```

Use hexdump to display the binary file `simple.bin`. If you set
`Test1.a = 150`, should be the bytes `08 96 01`.

```
hexdump simple.bin
```

Try running the program and entering other values. Try changing the
messgage Test1 in 'simple.proto' and modifying the Python program to
enter other things.

Next Lab:  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartB.md) Lab3 Part B - JSON, XML and Schemas

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab3 Part B - JSON, XML and Schemas

In this section of the lab you will create a Flask API that can take
protobufs, XML or JSON as input and output.

* Learn to convert between JSON and XML
* Learn to use a schema
* Learn how to handle JSON, XML and Protobufs in one Flask API
* Learn base64

# Step 1 - JSON, XML Protobuf Protocols

Examine the files `book.json`, `book.xml` and `book`. All three
files contain the same data encoded with different protocols.

* book.json - JSON format of address book
* book.xml - XML format of address book
* book - protobufs format of address book

```
cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ more book.json
pi$ more book.xml
pi$ hexdump book
```

# Step 2 - On-Line Validating

The following links define the JSON, XML and Protobug protocols.

http://www.json.org  
https://www.w3schools.com/xml/
https://developers.google.com/protocol-buffers/docs/pythontutorial
https://developers.google.com/protocol-buffers/docs/proto3

The following links allow you to validate data.

http://www.freeformatter.com/xml-validator-xsd.html  
http://jsonlint.com  
http://yura415.github.io/js-protobuf-encode-decode/  

Try creating some of your own JSON, XML and Protobuf Message files.

# Step 2 - Schemas

A Schema validates the content of your message, to make sure the
correct fields are present and the data is in the proper form.

Use the JSON file `person.json' and validate it against the schema
`person.jsd` in the online formatter below.

Use the XML file `order.xml` and validate it against the schema
`order.xsd`.

https://jsonschemalint.com/#/version/draft-04/markup/json
http://www.freeformatter.com/xml-validator-xsd.html  

There is no "schema" for protobufs that I'm aware of.

Try making modifications to the schema or the data. Make it wrong
and see if the validators catch it.


# Step 3 - Run multi_server, a Multiple Protocol Server

The python program `multi_server` can serve up JSON, XML and Protobuf
formatted data.

**API:**  
See simple.proto  

VERB | Route | Description | Data
---- | ----- | ----------- | ----
GET | /api/v1/simple | Get current number in (defaults to JSON format) | '{"number":3}'
PUT | /api/v1/simple | Set current number in (defaults to JSON format) | '{"number":3}'

In one terminal window on RPi3, run the multiple protocol server `multi_server.py`.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ python multi_server.py
```

In another terminal window on the RPi3 or your PC, try sending data in various forms.

Examples of payloads to the multiple protocol server.

```
// get current number
pi$ curl 127.1:5000/api/v1/simple

// set current number to 23
pi$ curl 127.1:5000/api/v1/simple -X 'PUT' -d '{"number":23}' -H 'Content-Type: application/json' --verbose

// set current number to 53 in XML
pi$ curl 127.1:5000/api/v1/simple -X 'PUT' -d '<number>53</number>' -H 'Content-Type: application/xml' --verbose

// set current number to 150 in Protobufs
pi$ curl 127.1:5000/api/v1/simple -X 'PUT' -d 'CJYB' -H 'Content-Type: application/protobuf' --verbose
```

# Step 4 - Base64

Base64 is an ASCII text represenation of binary data. It uses 64 ASCII character
(a-z,A-Z,0-9,+/) to encode the binary data. The resulting data is 33% larger,
but can be transmitted/parsed by ASCII protocols such as HTTP.

You can manually create a base64 representation of a protobuf Test1.a number by
doing the following in Python Idle.

```
pi$ python
import base64
str = '\x00\x11\x22\xfe'
str
data = base64.b64encode(str)
data
```

Protobufs is binary protocol. The following example assumes you've created
the simple_pb2.py from LabPartA.

```
pi$ python
import base64
import simple_pb2
myvar = simple_pb2.Test1()
myvar.a = 150
str = myvar.SerializeToString()
str
data = base64.b64encode(str)
data
```

Next Lab:  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartC.md) Lab3 Part C - WebSockets and Server Sent Events

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab3 Part C - WebSockets and Server Sent Events

In this section, you'll learn

* How to use WebSockets
* How to use SSE

git clone https://github.com/websocket-client/websocket-client

# Step 1 - Install Webcosket

See: https://github.com/websocket-client/websocket-client

Open a terminal window into the Pi3 and install the websocket-client

```
pi$ cd ~/Documents
pi$ git clone https://github.com/websocket-client/websocket-client.git
pi$ cd websocket-client
pi$ sudo python setup.py install
```

Note: on my Mac, I apparently had a different websocket client installed
for Python. So I ended up downloading this package and using git clone.


# Step 2 - Use a WebSocket Client

A convenient WebSocket server is at `ws://echo.websocket.org/`

From the open terminal window on the Pi.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ ws_client.py
```

# Step 3 - SSE

Below is a curl script that will work with an SSE Client. However, I
wasn't able to find an on-line SSE Server (and didn't make one).

The `http_client.py` can easily be modified to perform the SSE client
functionality (just an added header, and keep open the socket).

I'll leave task to the student (optional).

```
pi$ curl host_ip/path/to/sse -H 'Accept: text/event-stream'
```

You can see one that works in your browser at:
`http://demo.howopensource.com/sse/`

You can also install flask-sse. I did not think we would have time to
install this and get it running with the other topics this lab.

See `https://pypi.python.org/pypi/Flask-SSE`


Next Lab:  
[PART D](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/LabPartD.md) Lab3 Part D - MQTT and MQTT-SN

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab3 Part D - MQTT and MQTT-SN

In this section, you'll learn

* About the MQTT and MQTT-SN protocols
* How to access MQTT from the Web and from Python Applications

# Step 1 - Try out HiveMQ

MQTT is a widely adopted protocol (AWS uses it for example). A variety
of companies make MQTT broker and client (publisher and subscriber)
software.

HiveMQ is an online MQTT Broker that is enterprise quality.

1. Open a web browser to `http://www.hivemq.com/try-out/`
2. Click on the `Try the websocket client`
3. Pick a username/password
4. Set Keep Alive time to 300 (5 minutes) and Connect
5. You should see Topic `testtopic/1`
6. Add a subscription to `testtopic/1`
7. Type in a Message and Publish it
8. Let's all add a subscription to topic `iot210`
9. Type in Messages and Publish them to topic `iot210`

# Step 2 - Install Paho Python Client MQTT

```
pi$ sudo pip install pah-mqtt
```

Then, open 2 terminal windows on the Raspberry Pi, one for the publisher,
one for the subscriber (both of which are clients of a broker at iot.eclipse.org):

In the 1st terminal window, run the publisher

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ python mqtt_publish.py
```

In the 2nd terminal window, run the subscriber

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab3/src
pi$ python mqtt_publish.py
```

Try sending various messages to the iot210 group. Notice, we now have a
group chat.

# Step 3 - Extend the program

See if you can extend the program to allow topic: to go to a specific topic
to allow for individual or other group chats.

Example

```
Enter topic: string to post to individuals or other groups
```

# Step 4 - MQTT-SN

We'll learn about this in lecuture, but will implement during the ZigBee
or more embedded portion.


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Week 4

A number of people didn't have the right software installed, or have the
correct hardware at Week for, so I've included more complete instructions below
and we'll try again for Week 5.

Week 4 Homework (in preparation for Week 5) is to install the following software,

The software (Texas Instruments ZigBee Stack, IAR Embedded WorkBench for ARM, and Ubilogix Ubiqua)
all require Windows at this point.

For those of you with only a MAC computer, or Linux, you can follow along with the class.

I do not currently have instructions for TI Code Composer Studio 6.x at this time.

* The primary thing in this class is to learn ZigBee
* The secondary thing is to learn about TI and their tools


# Step 1 - Hardware - CC2650 LaunchPad

You'll need at least one Texas Instruments CC2650 Launchpad. If working
remotely, get 2.

**I recommend you order from DigiKey** (as you can get it in a couple of days or less).

https://www.digikey.com/en/product-highlight/t/texas-instruments/launchxl-cc2650-launchpad-kit

See also: http://www.ti.com/tool/launchxl-cc2650

**Optionally** get an 802.15.4 Sniffer (to watch packets).

http://www.ti.com/tool/cc2531emk

Digi-Key has it labled wrong (RFID rather that 802.15.4), but this is a sniffer: 

https://www.digikey.com/product-detail/en/texas-instruments/CC2531EMK/296-28921-ND/2231688

The Optional HW is useful to examine over-the-air packets. The sniffer is used
with Protocol Analyzers such as WireShark or Ubilogix Ubiqua.


# Step 2 - Download the SimpleLink App in your Phone

If you have a smart phone (Android or Apple), you can Download
the Texas Instruments `Simplelink Starter` app from Apple App
Store or Google Play.

If you have the CC2650 LaunchPad hardware, you can verify it all
works, as it has a Bluetooth application ready to go out-of-box.

1. Plug LaunchPad into power (you can use one of your USB chargers or your laptop
2. Launch the SimpleLink Starter app
3. Press (and hold!) the BTN-2 button on the LaunchPad
4. Select the LaunchPad from the menu of Bluetooth Smart Devices
5. Select Mission Control
6. Turn on/off LEDs
7. Try out buttons (it will indicate on screen the state of BTN-1 and 2

Some people said they had trouble with the Android App, but iOS worked fine.

# Step 3 - Download and Install Texas Instruments Software

You'll need to sign up for a free TI account.

http://processors.wiki.ti.com/index.php/CC2650_LaunchPad_User%27s_Guide_for_ZigBee

Follow the instructions down to and including the "Software" heading,
including downloading and installing

* Z-Stack Home 1.2.2a SDK
* TI-RTOS for SimpleLink Wireless MCUs

We'll be going through the "Porting Z-Stack Home) and setting up
the actual LaunchPad boards with ZigBee programs in class.

Make sure to download **version 2.21.00.06 of the TI-RTOS** and drivers for the CC2650.
Download that exact version to have the same results as I do in class.

[Download Z-Stack Home 1.2.2a](http://www.ti.com/tool/z-stack-archive)
[Download TI-RTOS for SimpleLink Wireless MCUs](http://software-dl.ti.com/dsps/dsps_public_sw/sdo_sb/targetcontent/mcusdk/index.html)


# Step 4 - Download and Install IAR

IAR (https://www.iar.com) Embedded WorkBench for ARM is a C compiler
and debugging environment. ARM processors for ZigBee, Thread and
Bluetooth are very popular and IAR EWARM is supported by NXP, TI,
SiLabs and others.

If you already have **IAR 7.40.2 for ARM** or later installed on
your Windows machine, you are fine.

IAR has a 30-day free trial. If you've already used a 30-day trial and can't
install it, call IAR and explain your are taking the UW IoT 210 course and
they should give you another 30-day free trial.

https://www.iar.com/iar-embedded-workbench/#!?currentTab=free-trials

Do NOT install the KickStart size-limited version, as it cannot build
the ZigBee programs. Choose the 30-day time-limited version instead.

# Step 5 - Download and Install Ubiqua Protocol Analyzer

Sign up for a free Ubilogix accunt.

Install the following Ubilogix Ubiqua software. It can be used to analyze
packets.

If you did not get the TI sniffer, do not worry, you can analyze packets from
a file. The sniffer is only needed to record data packets, not play them back.

[Ubilogix Ubiqua Free Trial](https://www.ubilogix.com/ubiqua#trial)
[Ubilogix Main Site](www.ubilogix.com)


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 4 - ZigBee Part1 

## Lab Objectives

In this lab you'll learn:

* What ZigBee is, and what problem space it solves
* What tools are used to build ZigBee Applications
* How build a ZigBee Application for the TI CC2650
* How to build a ZigBee network

## Homework

None (other than completing the labs we do in class)

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab4/LabPartA.md) ZigBee Light
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab4/LabPartB.md) ZigBee Network
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab4/homework.md) Finish Lab Work  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab4 Part A - A First ZigBee Application - Sample OnOff Switch

Total Lab Time: 1 hour

In this section of the lab you will learn

* How to use IAR Ebedded Workbench for ARM
* Learn about the TI ZigBee Stack, and how to port it to the 2650 Launchpad
* Examine the ZigBee OnOff Switch Application

You will need a Windows computer (version 7 or later, preferably version 10, 32-bit or 64-bit)
for this lab.

This lab assumes the tools are already installed. Tools used in this lab:

* TI ZigBee Stack and RTOS
* IAR EWARM 30-day eval (or standard version). Do NOT use the Kickstarter, as this won't build the ZigBee images.

See [Lab 3 Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab3/homework.md) for how to install the tools on Windows.

# Step 1 - Exploring IAR Embedded Workbench for ARM

Note: IAR moves projects are not backward compatible: once a project is opened with a new version
of IAR, it can't be opened with a previous version.

The TI software compiles without error or warning and was tested with IAR 7.4, but other versions (such as
the current 8.11


# Step 2 - Porting Z-Stack Home 1.2.2a to the CC2650 LaunchPad


See http://processors.wiki.ti.com/index.php/CC2650_LaunchPad_User%27s_Guide_for_ZigBee

**Important:** The use SampleLight (not SampleSwitch) as the base project, since a
Light is functional all on it's own (without a network).

BTN-1 will toggle the light if we are successful.

Note: This will be a ZigBee Coordinator (project type selectable in IAR)

We'll also set the -DDEFAULT_CHANLIST and -DZDAPP_CONFIG_PAN_ID in
Tools/f8wConfig.cfg so we don't interfere with each other during class.

Start following instructions "Porting Z-Stack Home 1.2.2a to the CC2650 LaunchPad" in class

# Step 3 - Programming the CC2650 Launchpad

When programming devices for the first time, the entire Flash memory should be erased:
select "Project->Download->Erase Memory" in IAR.


Next Lab:  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab4/LabPartB.md) Lab4 Part B ZigBee Switch

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab4 Part B - First ZigBee Network - Light and Switch

Total Lab Time: 30 minutes

In this section of the lab you will

* Go through the process of porting a ZigBee Application from 1 board to another
* Examine the ZigBee OnOff Light Application

# Step 1 - Same Steps, but for Switch

This assumes you've completed Part A

Now, do the same instructions, but use the SampleSwitch.

The Sample Switch will be a ZigBee Router (later we can do an end-device) 

In IAR, use the same settings in Tools/f8wConfig.cfg for 
the -DDEFAULT_CHANLIST and -DZDAPP_CONFIG_PAN_ID


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Week 5

Next week, we'll explore Bluetooth Low Energy (aka Bluetooth Smart)

Install the BLE stack from Texas Instruments BLE-STACK-2-2-1 for the CC2650:

http://www.ti.com/tool/ble-stack

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartA.md) ZigBee Network Demonstrated  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartB.md) Use Ubiqua Protocol Analyzer  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/homework.md) Install Texas Instruments Bluetooth Low Energy Stack  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 5 - ZigBee Part 2

## Lab Objectives

In this lab you'll learn:

* How to form a ZigBee Network
* How to commission a new node and join a ZigBee Network using EZ-Mode
* How to capture ZigBee over-the-air (OTA) packets
* How to decode ZigBee packets
* ZigBee Security (including AES 128-bit)

## Homework

Install the Texas Instruments Bluetooth stack

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartA.md) ZigBee Network Demonstrated  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartB.md) Use Ubiqua Protocol Analyzer  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/homework.md) Install Texas Instruments Bluetooth Low Energy Stack  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab4 Part A - A ZigBee Network

In this section of the lab, you'll learn

* How easy compiling SHOULD be
* How to form a ZigBee Network
* How to commission a new node and join a ZigBee Network using EZ-Mode

# Step 1 - Installing Tools

Install the Texas Instruments Flash-Programmer-2 (I download version 1.7.5).

http://www.ti.com/tool/launchxl-cc2650
http://www.ti.com/tool/flash-programmer


# Step 1 - Compiling

Compiling ZigBee Applications for the CC2538, using JTAG to download code.

1. Open IAR
2. Go to File/Open/Workspace
3. Navigate to C:\TI\Z-Stack Home 1.2.2a.44539\Projects\zstack\HomeAutomation\SampleLight\CC2538
4. Open the .eww
5. Press F7 to compile the project
6. Done!
7. In Workspace, examine file Application/zcl_samplesw.c
8. In Workspace, examine file Tools/f8wConfig.cfg

Note: the .eww and .ewp are XML files that can be edited. Don't do this unless you back up
and are VERY careful. We do it to change paths sometimes (fater than add/files in IAR).

The TI software compiles without error or warning and was tested with IAR EWARM 7.4,
but other versions (such as the current 8.11.1) may cause warnings or issues. If
you have paid for a license, you get access to MyIAR, which allows downloading
older versions.


# Step 2 - Forming a 2-Node Network

Note: If you have a sniffer, and are in class, you can capture the Over-the-Air
data at

```
Pan ID: 0xd6d6
Channel: 11
```

1. Turn on the ZigBee Coordinator / OnOffLight
2. Turn on ZigBee End Device / OnOffSwitch
3. Press SW2 on ZC
4. Press SW2 on ZED
5. In a few moments they will be connected.
6. Press SW1 on ZED to toggle light on ZC


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartA.md) ZigBee Network Demonstrated  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartB.md) Use Ubiqua Protocol Analyzer  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/homework.md) Install Texas Instruments Bluetooth Low Energy Stack  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab5 Part B - Decoding with Ubiqua

In this section of the lab, you'll learn 

* How to capture ZigBee over-the-air (OTA) packets
* How to decode ZigBee packets
* ZigBee Security (including AES 128-bit)

You will need a Windows PC (or Virtual Machine) to run Ubiqua.

# Step 1 - Exploring Ubiqua

Copy the file from Lab5 to you Windows PC.

1. Run Ubiqua
2. From File Menu run File/Open and choose "EZ-Mode Commissioning.cubx"
3. We'll examine the packets in this file in detail


For exploring AES-128, go to:

http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartA.md) ZigBee Network Demonstrated  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/LabPartB.md) Use Ubiqua Protocol Analyzer  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab5/homework.md) Install Texas Instruments Bluetooth Low Energy Stack  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Week 6

Go to side wolfssl.com, explore their offerings (all open source)

https://wolfssl.com/wolfSSL/Home.html

Download wolfssl-3.11.0.zip (see Download tab)

We'll use this next week to explore concepts like PKI

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartA.md) ZigBee Routing  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Beacons  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Profiles  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/homework.md) Install Wolf-SSL tools  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 6 - ZigBee, Bluetooth Low Energy, and 6LoWPAN (Thread)

## Lab Objectives

In this lab you'll learn:

* How to program your TI LaunchPad CC2650 for ZigBee Communications
* What Bluetooth Beacons are and how to make them on your Raspberry PI
* What 6LoWPAN and Thread are
* How to program your TI LaunchPad CC2650 for BLE Communications
* Sample tutorial, LauncPad

## Homework

Install Wolf-SSL Security tools.

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartA.md) ZigBee Routing  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Profiles  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Beacons  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/homework.md) Install Wolf-SSL tools  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab6 Part A - ZigBee Routing

In this section of the lab, you'll learn

* How to program the CC2650 for ZigBee (with an HA On-Off Switch)
* How to commission a new node and join a ZigBee Network using EZ-Mode
* Explore ZigBee Routing

# Step 2 - Examining the ZigBeeRouting.cubx

To see routing in action, open the ZigBeeRouting.cubx file

https://gitlab.com/Gislason/iot-210B-student/blob/master/Lab6/files/ZigBeeRouting.cubx


# Step 1 - Install the SmartRF Flash Programmer2

The SmartRF Flash Programmer 2 tool installs on your **Windows Laptop**.

http://www.ti.com/tool/flash-programmer

Make sure to install FLASH-PROGRAMMER-2:


# Step 2 - Flashing the CC2650 Board

Two .hex files have been prepared for you:

* [ZStackCoreEndDevice.hex](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/files/ZStackCoreEndDevice.hex)
* [SampleSwitch.hex](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/files/SampleSwitch.hex)

The ZStackCoreEndDevice.hex file is the ZigBee stack.

The SampleSwitch.hex file is the application file.

Intel .hex is a common output notation for binary files that also include location for the binary.

https://en.wikipedia.org/wiki/Intel_HEX

To program the boards

1. Copy the two .hex files to a file folder on your Windows PC.
2. Run the SmartRF Flash Programmer 2 program
3. Plug in your LaunchPad CC2650 Board into USB
4. Refresh the SmartRF list of Connected Devices until your CC2650 is recognized
5. Select the CC2650 in Connected Devices (in grey)
6. Indicate you want to program Multiple images on the Main Tab
7. Indicate you want to Erase, Program and Verify with CRC Check
8. Press the Play button to initiate programming the flash memory on the CC2650

The ZigBee device is programmed to auto-join and to auto-detect a light.


![SmartRFFlashProgrammer2](images/flashprogrammer2.jpg)

# Step 3 - Toggle the Light

Press BTN-1 (Near the large chip) to toggle the ZigBee Coordinator Light.

Wait for instruction, then press BTN-2 to enter EZ-Mode and toggle both ZigBee
Coordinator and ZigBee Router Light.

We may move the Router down the hallway to show true (out of range) multi-hop.

## Note for Remote Students

Since the CC2650 Doesn't support a ZigBee Coordinator, it may be tough to make a ZigBee
network! :-)

However, the part does support the MAC Full Function Device (Coordinator) and a
MAC Reduced Function Device (End-Device), so two LaunchPad CC2650 can be used for
an 802.15.4 Network.

See http://www.ti.com/product/CC2650/toolssoftware


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartA.md) ZigBee Routing  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Beacons  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Profiles  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/homework.md) Install Wolf-SSL tools  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)


# Lab6 Part C - Bluetooth Beacons

* How to 
* How to display the beacon in your iPhone or Android

# Step 1 - Install the Physical Web App

Enable Bluetooth in your phone / tablet.

Get the app.

https://itunes.apple.com/us/app/physical-web/id927653608?mt=8&ign-mpt=uo%3D4

https://play.google.com/store/apps/details?id=physical_web.org.physicalweb&hl=en

There may be other ways to show the Beacons in your phone / tablet (Chrome is
supposed to have it built-in. I haven't found out how to enable.


# Step 2 - Cause your Rapsberry PI 3 to start emitting Eddystone-URL Beacons

Configure your RPi as a beaconing device.

Note: if you have trouble with unable to resolve hostname, try looking at the files

pi@iot40a2:~ $ nano /etc/hostname  
pi@iot40a2:~ $ sudo nano /etc/hostname  

```
$ ssh pi@<my_ip_addr>

# verify HCI is available
pi$ hciconfig -h

# Enable bluetooth
pi$ sudo hciconfig hci0 up

# Set the bluetooth device to advertise and not connectable
pi$ sudo hciconfig hci0 leadv 3

# Enter beacon data
pi$ sudo hcitool -i hci0 cmd 0x08 0x0008 15 02 01 06 03 03 aa fe 0d 16 aa fe 10 00 03 70 63 65 2e 75 77 02 00 00 00 00 00 00 00 00 00 00

```

15 02 01 06 03 03 aa fe 0d 16 aa fe 10 00 03 70 63 65 2e 75 77 02 00 00 00 00 00 00 00 00 00 00
sudo hcitool -i hci0 cmd 0x08 0x0008 1d 02 01 06 03 03 aa fe 15 16 aa fe 10 00 03 74 69 6e 79 75 72 6c 00 6d 71 6f 63 70 37 62 00 00



http://tinyurl.com/mqocp7b

For a description of the format of the beacons

https://github.com/google/eddystone/tree/master/eddystone-url


You've only got 32-bytes total for the BLE beacon.



# Step 3 - Make your own beacons

## Beacon Format

See format of beacon at:

https://github.com/google/eddystone/tree/master/eddystone-url

## TinyURL and goo.gl make short URLs

TinyURL allows you to create a short URL for a much longer one

https://tinyurl.com

https://tinyurl.com/lhzansa is the same as https://www.pce.uw.edu/certificates/internet-of-things

Google also does the same thing with URL shortener: https://goo.gl

## Use echo and Hexdump to get the ASCII codes for your URL

```
pi$ echo "pce.uw.edu" >x.txt
pi$ hexdump -C x.txt
```

## Eddystone Format in Detail

0x08  #OGF = Operation Group Field = Bluetooth Command Group = 0x08
0x0008  #OCF = Operation Command Field = HCI_LE_Set_Advertising_Data = 0x0008

15  Length. The hexadecimal 15 converts to 21 decimal which is the number of bytes that follow  
02  Length  
01  Flags data type value  
06  Flags data  
03  Length  
03  Complete list of 16-bit Service UUIDs data type value  
aa  16-bit Eddystone UUID  
fe  16-bit Eddystone UUID  
0d  Length. The hexadecimal 0f converts to 15 decimal which is the number of bytes that follow  
16  Service Data data type value  
aa  16-bit Eddystone UUID  
fe  16-bit Eddystone UUID  
10  Frame Type = URL  
00  TX Power (this should be calibrated)  
03  URL Scheme (http:// = 0x02)(https:// = 0x03).  
70  â€˜pâ€™ in hexadecimal  
63  â€˜câ€™ in hexadecimal  
65  â€˜eâ€™ in hexadecimal  
2e  â€˜.â€™ in hexadecimal  
75  â€˜uâ€™ in hexadecimal  
77  â€˜wâ€™ in hexadecimal  
08  .edu (.edu = 0x02)  
00  
00  
00  
00  
00  
00  
00  
00  
00  
00  

https://tinyurl.com/lhzansa


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartA.md) ZigBee Routing  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Beacons  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Profiles  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/homework.md) Install Wolf-SSL tools  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab6 Part C - BlueTooth Low Energy (BLE) Project Zero

In this Lab, you'll learn

* About the Project 0 BLE Application
* How to program the LaunchPad CC2650 for BLE
* How to program your board from Cloud Tools
* How to use Code Composer Studio
* Resources for doing your own BLE experiments


# Resources

There are a couple resources I would suggest you should look into:
 
1. SimpleLink Academy (http://software-dl.ti.com/lprf/simplelink_academy/overview.html) â€“ this is probably the best place for a beginner to start. If you are already familiar with TI-RTOS, I would suggest you start with the BLE Fundamentals lab. These labs use Project Zero which is a really good starter project for a peripheral role.
2. SimpleLink Github page (https://github.com/ti-simplelink/ble_examples) â€“ here we host many examples outside of the SDK. The ble_examples-2.2 branch has the latest examples for the CC2650 including several beacon examples.
3. TI BLE Wiki (https://github.com/ti-simplelink/ble_examples) â€“ this has a lot of useful information and resources. I would suggest looking at the beacon app notes and reference design.

# Step 1 - The Cloud Tools

https://dev.ti.com

CCS Cloud is Cloud Composer Studio in the cloud.



# Step 2 - Installing TI Bluetooth Software

If you haven't already, install the BLE stack for the CC2650. This will allow you to make local
applications with Code Composer Studio

http://www.ti.com/product/CC2650/toolssoftware

Get the BLE-STACK-2-1-1 (for CC2650)   http://www.ti.com/tool/ble-stack


# Step 3 - Installing Tools

## Putty

This tool will allow you to use the serial port for monitoring. It's also useful for SSH.

http://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

## Google Chrome

If you don't already have it installed, install Google Chrome. This is required by
the TI Cloud Tools.

[Google Chrome Download](https://www.google.com/chrome/browser/features.html?brand=CHBD&gclid=CPSFgZSC19MCFZIBaQodVtEHXA&dclid=CO_qm5SC19MCFY5ofgodprwOOw)


# Step 4 We'll Go Through This BLE Tutorial Together

Go to https://dev.ti.com

http://dev.ti.com/tirex/content/cc26xx_bluetooth_smart/cc26xx_bluetooth_smart__2.01.00.44423/Projects/ble/ProjectZero/project0_resources/prz/index.html

http://software-dl.ti.com/lprf/simplelink_academy/overview.html#videos


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartA.md) ZigBee Routing  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Beacons  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/LabPartB.md) Bluetooth Profiles  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab6/homework.md) Install Wolf-SSL tools  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Week 7

Try turning the Raspberry Pi into an access point.
See Lab7/docs/setting-up-a-raspberry-pi-as-a-wifi-access-point.pdf

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 7 - IoT Security

## Lab Objectives

In this lab you'll learn:

* How to secure your IoT devices and transactions
* What are the different cryptographic algorithms and their uses
* How to set up the Rapsberry Pi as an Access Point with WPA2
* How TLS works and how to create self-signed certs for lab work
* How to create a secure web page

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) TLS and self-signed certs  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) WPA2 and Access Points  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) Move Quizical to your own free Heroku account  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab7 Part A - Cryptographics 

In this section of the lab you will learn

* Hash functions and when to use them
* Encryption algorithms and when to use them
* Public-key algorithms and when to use them

We'll use the Rapsberry Pi for exploring cryptography.

## Step 1 - Install pycrypto

Install pycrypt on your Rapsberry Pi

Either: 

```
pi$ sudo apt-get install python-crypto
```

Or do: 

```
pi$ sudo apt-get install python2.7-dev
pi$ sudo pip install pycrypto
```

Verify installation worked

```
pi$ python
>>> from Crypto.Hash import SHA256
>>> hash = SHA256.new('Hello World').hexdigest()
>>> print 'hash len(' + str(len(hash) / 2) + ') ' + hash
```

## Step 2 - Hash Algorithms

This explores hashing by making a user/password file.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab7/src
pi$ iotsha256.py
```

Try entering a few different users and passwords by pressing Enter (no name)
to create new users.

Try logging into each account by typing username and password.

Try logging in with the wrong password.

Let's examine the file passwords.txt.

Easy: guess the password for user 'hello'.

Bonus: See if you can determine the password for user "drew".

Hint: http://md5decrypt.net/en/Sha256/

## Step 3 - Block Cipher (AES)

This lab uses MQTT to send/receive encrypted text.

This uses a global built-in key.

```
pi$ python mqtt_subscribe_aes.py
```

In another SSH terminal window on your Raspberry PI, run the MQTT
publish application. This requires you to enter a key

```
pi$ python mqtt_publish_aes.py secretkey
```

Publish some lines of text. Notice the text is encoded on sending,
and decoded on receiving at the Subscriber.

Try changing your key on the subscriber (by editing the mqtt_subscribe_aes.py).

Make sure to change the key on the cmdline for the publisher.

Note: the AES key must either by 16 bytes (AES-128) or 32 bytes (AES-256)


## Step 4 - Public Key (RSA)

```
pi$ python iotpki.py The quick brown fox jumped over the lazy dog.
```

## Step 5 - Signing a Public Key

Sign

Signing a message can be useful to check the author of a message and make
sure we can trust its origin. Next is an example on how to sign a message.
The hash for this message is calculated first and then passed to the
sign() method of the RSA key.

Start by running python from SSH on the Rapsberry Pi.

**Signing** 

```
$pi python
>>> from Crypto.Hash import SHA256
>>> from Crypto.PublicKey import RSA
>>> from Crypto import Random
>>> random_generator = Random.new().read
>>> key = RSA.generate(1024, random_generator)
>>> text = 'my_signature'
>>> hash = SHA256.new(text).digest()
>>> signature = key.sign(hash, '')
>>> public_key = key.publickey()
```

**Verify**

Knowing the public key, it is easy to verify a message. The plain text is sent
to the user along with the signature. The receiving side calculates the hash
value and then uses the public key verify() method to validate its origin.

```
>>> text = 'my_signature'
>>> hash = SHA256.new(text).digest()
>>> public_key.verify(hash, signature)
True

>>> text = 'not_my_signature'
>>> hash = SHA256.new(text).digest()
>>> public_key.verify(hash, signature)
False
```

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) TLS and self-signed certs  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) WPA2 and Access Points  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) Move Quizical to your own free Heroku account  


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab7 Part B - Making an encrypted website using self-certs

In this lab, you'll learn about Nginx

Steps:

1) Update the system

`pi$ sudo apt update`

2) Install Nginx Web Server

```
pi$ sudo apt install nginx
pi$ sudo service nginx start
```

3) Verify Nginx is working http://<YOUR_IP>
   Verify that Nginx SSL is NOT working https://<YOUR_IP>

4) Generate OpenSSL Certificate

```bash
$ ./generate_key.sh
Generating a 2048 bit RSA private key
.........................................................................+++
.......+++
writing new private key to '{hostname}.key'
-----
You are about to be asked to enter information that will be incorporated
into your certificate request.
What you are about to enter is what is called a Distinguished Name or a DN.
There are quite a few fields but you can leave some blank
For some fields there will be a default value,
If you enter '.', the field will be left blank.
-----
Country Name (2 letter code) [AU]:US
State or Province Name (full name) [Some-State]:Washington
Locality Name (eg, city) []:Bellevue
Organization Name (eg, company) [Internet Widgits Pty Ltd]:IOT 110
Organizational Unit Name (eg, section) []:IOT 110 (B) Spring
Common Name (e.g. server FQDN or YOUR name) []:Josh Welschmeyer
Email Address []:joshwelschmeyer@gmail.com
```

5) Create the folders to store generated keys

`$ sudo mkdir -p /etc/ssl/certs/iot /etc/ssl/certs/iot/private`

6) Copy the keys to the created folders

```bash
$ sudo cp {hostname}.crt /etc/ssl/certs/iot
$ sudo cp {hostname}.key /etc/ssl/certs/iot/private
```

7) Stop Nginx

```
pi$ sudo service nginx stop
```

8) Update the Nginx Configuration

Remove the currently enabled site configuration

```
pi$ sudo rm /etc/nginx/sites-enabled/default
```

Copy the new site configuration

Edit the iot-nginx.conf for your local hostname.

```
pi$ nano iot-nginx.conf
pi$ sudo cp iot-nginx.conf /etc/nginx/sites-enabled
```

9) Start your Flash application as a background process

```
pi$ pwd
/home/pi/Documents/Git/iot-210B-student/Lab7/src
pi$ python apserver.py &
```

10) Start Nginx

```
pi$ sudo service nginx start
pi$ hostname -I
  172.22.194.141
```

11) On your desktop, curl to your IP address (returned by hostname)

```
curl 172.22.194.141/api/v1?hello=world
```


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) TLS and self-signed certs  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) WPA2 and Access Points  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) Move Quizical to your own free Heroku account  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)


# Lab7 Part C - Making your Rapsberry PI an Access Point

We're going to follow the Ada Fruit Tutorial.

See gitlab.com/Gislason/iot-210B-student/Lab3


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartA.md) Cryptographics  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartB.md) TLS and self-signed certs  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab7/LabPartC.md) WPA2 and Access Points  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) Move Quizical to your own free Heroku account  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Lab8

Obtain an Echo Dot if you want to do the Alexa Programming from home
with your own Echo Dot.

I'll try to provide an MQTT bases solution for remote students who
don't want to own an Echo Dot.

Obtain an AWS IoT Button. I plan to provide a means of programming
the button to work with ASK.

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 8 - APIs, including DropBox, PhilipsHue, IFTTT

## Lab Objectives

In this lab you'll learn:

* How to connect to and use various IoT APIs
* Concepts around connecting IoT Devices to the Cloud

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartA.md) DropBox API  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartB.md) Philips Hue API  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartC.md) IFTTT API  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) None  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab8 Part A - Dropbox API

In this section of the lab you will learn:

* How add the Dropbox API to a python program
* How to "salt" passwords so they can't be easily hacked

We'll use the Rapsberry Pi for exploring cryptography.

## Step 1 - Setup a Dropbox Account

Create a Dropbox account and login

1. On your desktop PC, go to https://www.dropbox.com/developers/apps/create
and choose "Dropbox API App" (not the Business API)
2. Choose "App Folder - Access to a single folder created specifically for your app."
3. Name the app "iot210", and Create the app.
4. On the iot210 app Settings tab, choose Generate Access Token.
5. You'll need this token (a long string of random ASCII characters), so leave page open

## Step 2 - Install dropbox on your Raspberry Pi

Install dropbox on your Rapsberry Pi

```
ssh pi@{my.pi.ip.addr}
pi$ sudo pip install dropbox
```

Verify installation worked

```
pi$ python
>>> import dropbox
```

## Step 3 - Python Program To Try Out Dropbox API

This step uses the same login program we used last week, but modified
to use dropbox (now called dropbox_sha256.py in Lab8) for file storage.

You'll need to add the token from step 1 into the program for it to work.


```
pi$ cd ~/Documents/Git/iot-210B-student
pi$ git pull
pi$ cd Lab8/src
pi$ nano dropbox_sha256.py
  add your dropbox token, WriteOut(^O), then Exit(^X)
```

Then, run the program. It should behave like it did last week (able
to create new users and login as existing users).

On your PC web browser, Go to: https://www.dropbox.com/home/Apps/iot210.
Notice there is no "filename.txt".

Now run the program.

```
pi$ dropbox_sha256.py
```

Notice the file "passwords.txt" has been created in the Application Folder
at https://www.dropbox.com/home/Apps/iot210.

Try entering a few different users and passwords by pressing Enter (no name)
to create new users.

Try logging into each account by typing username and password.

Try logging in with the wrong password.

Let's examine the file passwords.txt on DropBox.


## Step 3 - Password Challenge

Challenge: An existing user of "drew" is in the file unbreakable(??)
`passwords.txt`.

See http://md5decrypt.net/en/Sha256/

Thanks to 


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartA.md) DropBox API  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartB.md) Philips Hue API  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartC.md) IFTTT API  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) None  


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab8 Part B - Philips Hue API

In this section of the lab you will learn:

* How add the Philips Hue API to a python program
* How to toggle a light base on Hue API

## Step 1 - Install Philips Hue API

Install Philips Hue API on your Raspberry PI

```
pi$easy_install phue
```
or

```
$ sudo pip install phue
```

See also https://github.com/studioimaginaire/phue for more installation instructions.

## Step 2 - Determine address of Philips Hue Gatewaay

In your browser, go to: https://www.meethue.com/api/nupnp

This should tell you the IP address of the Philips Hue Bridge.

Enter this IP address into hue_color.py (see line 8, BRIDGE_IP)

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab8/src
pi$ nano hue_color.py
  BRIDGE_IP   = '10.0.1.6'
```

## Step 3 - Try Out the hue_color.py program

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab8/src
pi$ python 
```

## Step 4 - Explore Philips Developer's Portal

Register (it will send you an email), then use the emailed link to log in.

https://developers.meethue.com/user/login
https://developers.meethue.com/documentation/getting-started
https://developers.meethue.com/documentation/lights-api

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartA.md) DropBox API  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartB.md) Philips Hue API  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartC.md) IFTTT API  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) None  


[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab8 Part C - ifthisthenthat (IFTTT)

In this section of the lab you will learn:

* What IFTTT is
* How to use IFTTT
* How to develop for IFTTT
* How to integrate IFTTT into your Python programs

## Step 1 - Sign Up for IFTTT

https://ifttt.com

## Step 2 - Create an action using the IFTTT Website

On your PC, sign up for twitter if you don't already have an account at

https://twitter.com

Then go to IFTTT to Create New Applet (click on your username, new Applet).

https://ifttt.com

This should bring you to a page of if[this]thenthat.

Click on "This" to connect to a trigger. Connect to twitter (making a tweet
on a particular hashtag. I used `#iot210`.

You'll need to allow IFTTT access to your twitter account.

Then click on "That" to connect the action. In this case, send an SMS.
It will ask for your phone #, and will text a code to your phone.

Enter the code.

Now IFTTT will connect the trigger (tweeting) to the action (texting).

Unfortunately, IFTTT doesn't do this immediately. It says it will
happend within the hour.


## Step 3 - IFTTT in a Python Program

Go to https://ifttt.com/maker_webhooks

Click on the documentation button. This will generate a unique key
for you. You can test it by doing the following:

```
curl -X POST https://maker.ifttt.com/trigger/ping/with/key/{mykey}

curl -X POST https://maker.ifttt.com/trigger/{event}/with/key/{mykey}
curl -X POST -H "Content-Type: application/json" -d '{"value1":"1","value2":"2","value3":"2"}' https://maker.ifttt.com/trigger/{event}/with/key/{mykey}
```

On your raspberry Pi, you must add the key to the program `ifttt_ping.py`.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab8/src
pi$ nano ifttt_ping.py
pi$ python ifttt_ping.py
```

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartA.md) DropBox API  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartB.md) Philips Hue API  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab8/LabPartC.md) IFTTT API  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab/homework.md) None  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Homework for Lab9 - Capstone Projects

The Capstone project should be completed before, during the final class or shortly
thereafter.

Feel free to work in teams, or to create individual projects.

Use technology you learned during class (HTTP, JSON, RESTful APIs, Cloud Hosting like Heroku,
Cryptography, MQTT, Philips Hue API, IFTTT, DropBox, AWS, etc...) to create something
interesting to you.

Check in the source code to your own GitLab account, and send me a link via Canvas InBox Email.

https://canvas.uw.edu/conversations#filter=type=inbox

## Some Capstone Ideas

(Feel free to use your own ideas)

* Create something with IFTTT that involves your Raspberry Pi
* With the LaunchPad CC2560, create a Philips Hue Switch (use API)
* Create a LaunchPad C2650 MAC Network that toggles other CC2650 lights
* Use Bluetooth Beacons to make a â€œperson is presentâ€ application (e.g. auto door unlock, or find my kid)
* Create an MQTT publish/subscribe private Internet of Things
* Using Heroku (for hosted app) and Dropbox (for hosted data), create an IoT hub
* Turn your Raspberry Pi into a IoT hub for controlling things
* Create a Restful API on the Web that allows someone
* Create an AWS Lamba Skill and win a Limited edition Alexa Dev Shirt https://developer.amazon.com/alexa-skills-kit/alexa-developer-skill-promotion

Any idea is acceptible as long as it demonstrates something to do with the internet of things.

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Week 9 - Amazon Web Services (AWS) IoT and Alexa APIs

## Lab Objectives

In this lab you'll learn:

* How to create an AWS account
* How to install Python tools for AWS on your Rapsberry Pi
* How to connect to AWS IoT APIs using your Raspberry Pi

## Lab Links

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartA.md) AWS Security and S3  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartB.md) AWS Dash Button  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartC.md) AWS and Alexa  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/homework.md) Capstone Projects  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab 9 Part A - Amazon Web Services AWS IoT, Security and S3

In this section of the lab you will learn:

* How to create an AWS account
* How to install Python tools for AWS on your Rapsberry Pi
* How to connect to AWS IoT APIs using your Raspberry Pi
* Allow a "thing" to publish/subscribe using AWS MQTT

We'll use the Rapsberry Pi for exploring cryptography.

## Step 1 - Create an Amazon AWS Account

Go to https://aws.amazon.com/free/
Go to [Amazon AWS](https://aws.amazon.com) and sign up.

This page has a good overview of all the AWS products. We'll be concentrating
on IoT products (IoT Platform and Button).


## Step 2 - Install the AWS Command-Line Tools

First, install the AWS command-line tools on your Raspberry Pi. Also install
boto3 and AWSIoTPythonSDK at this time.

```
pi$ sudo easy_install awscli
pi$ sudo easy_install boto3
pi$ sudo easy_install AWSIoTPythonSDK
```

Verify AWS command-line tools installed.

```
pi$ aws --version
```

Next, create the ~/.aws/ folder and copy the config file (that says we'll be
using `us-west-2` region). AWS segments things in regions.

```
pi$ cd ~/Documents/Git/iot-210B-student/Lab9/src
pi$ mkdir ~/.aws/
pi$ cp config ~/.aws/
```

## Step 2.A Create and Copy Credentials

* Login to Console at https://aws.amazon.com
* Go to IAM (Identity and Access Manager)
* Create Group with all Full IoT Access called iot210
* Create User with group you just created iot210 for programmatic access
* You will need the access_id and secret_key


```
pi$ aws configure
aws configure
          AWS Access Key ID [None]: accesskey
          AWS Secret Access Key [None]: secretkey
          Default region name [None]: us-west-2
          Default output format [None]:
```

Use us-west-2 for your region


## Step 3 - Create a Thing

```
pi$ aws iot create-thing --thing-name "thingName"
pi$ aws iot list-things
```

## Step 4 - Create the Public/Private Keys and Certificate

On your desktop browser, go to the AWS Primary Root Certificate Authority
https://www.symantec.com/content/en/us/enterprise/verisign/roots/VeriSign-Class%203-Public-Primary-Certification-Authority-G5.pem

This file has already been saved for you as `awsIotRootCert` since it is the same for all users of AWS.


```
pi$ cd ~/Documents/Git/iot-210B-student/Lab9/src
pi$ aws iot create-keys-and-certificate --set-as-active --certificate-pem-outfile cert.pem --public-key-outfile publicKey.pem --private-key-outfile privkey.pem
```

This will show the keys and certificate and an "arn". Amazon Resource Name.

```
pi$ aws iot list-certificates
```

Now, create the policy that allows this "thing" to access all AWS IOT services.

```
pi$ aws iot create-policy --policy-name "PubSubToAnyTopic" --policy-document file://iotpolicy.json
```
Now, attach the policy and the thing to the arn.

```
pi$ aws iot attach-principal-policy --principal "certificate-arn" --policy-name "PubSubToAnyTopic"
pi$ aws iot attach-thing-principal --thing-name "thingName" --principal "certificate-arn"
```

Now you should be ready to.

## Step 5 - Modify the Pub/Sub applications for your "thing"

Update the awsiotput.py and the awsiotsub.py to have your `clientId` and `thingName`

```
pi$ nano awsiotpub.py
pi$ nano awsiotsub.py
pi$ python awsiotsub.py
```

In a separate SSH window, run the publisher

```
pi# python awsiotpub.py
```

## Step 6 - Experiment with Device Shadow on your "thing"

http://docs.aws.amazon.com/iot/latest/developerguide/thing-shadow-mqtt.html

topic: $aws/things/{myThing}/shadow/update
payload: { "state" : { "desired" : { "color" : "red", "power" : "on" }}}

[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartA.md) AWS Security and S3  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartB.md) AWS AWS IoT Button  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartC.md) AWS and Alexa  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/homework.md) Capstone Projects  



[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab 9 Part B - AWS and the AWS IoT Button

In this section of the lab you will learn:

* How to use the AWS IoT Button to control
* How to create an AWS Lambda Function

This lab assumes you have already purchased an AWS IoT Dash Button

## Step 1 - Purchase a AWS IoT Button

https://aws.amazon.com/iotbutton/getting-started/

## Step 2 - Connect AWS IoT Button To your Network

Download the AWS IoT Button App from your app store. I tried the iOS version at:

https://itunes.apple.com/us/app/aws-iot-button/id1178216626?mt=8

## Step 3 - Activiating the AWS IoT Button

Follow the instructions in the app to Add the button to your AWS account


[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartA.md) AWS Security and S3  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartB.md) AWS AWS IoT Button  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartC.md) AWS and Alexa  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/homework.md) Capstone Projects  



[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)

# Lab 9 Part C - AWS and Alexa Skill Kit (ASK)

In this section of the lab you will learn:

* How to add a spoken Skill to an Echo Dot (or Alexa equivalent)
* Learn a little about the Alexa Skills Kit

## Step 1 - Sign Up for Developer Account

Go to `developer.amazon.com` and sign up.

Answer no to monitizing, so you don't have to set up any payment information.

## Step 2 - Introduction to Amazon Skills Kit

Even if you don't have an Echo Dot, you can follow along with the example.

On your desktop browser, go to:

https://developer.amazon.com/alexa-skills-kit/tutorials/fact-skill-1

We'll go through this tutorial together in class.

For step 5, I created a skill called i.o.t.two.ten in english



[PART A](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartA.md) AWS Security and S3  
[PART B](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartB.md) AWS AWS IoT Button  
[PART C](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/LabPartC.md) AWS and Alexa  
[Homework](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab9/homework.md) Capstone Projects  

[IOT STUDENT HOME](https://gitlab.com/Gislason/iot-210B-student/blob/master/README.md)
# Changelog

This document will provide updates about the course at large if updates were made to the repo outside of what was presented within class, or new changes for future sessions.

## 2017-06-23

- Changed all files that should be labeled `README` to readme files so they can be displayed easily within the browsers.
- Initial changelog file added to course root folder
- Adding a section called **Lab Links** which provides links to all the items used within the lab in case anyone wants to delve further.
- **Lab Links** added to [week1/lab1/README.md](week1/lab1/README.md)
- **Lab Links** added to [week1/lab2/README.md](week1/lab2/README.md)
- Updated following sections to [week1/lab2/README.md](week1/lab2/README.md).
    - What is NPM?
    - MQTT over WebSockets
    - MQTT npm module
    - Setup the Electron Quick Start app


## 2017-06-29

- Changed out MQTT broker to [Mosquitto MQTT Broker](http://test.mosquitto.org/) -- updated in previous labs.
- Finished week2# Welcome to the IOT 310B: Internet of Things: Cloud Computing & Analytics

Data is the key to success in the internet of things. In this course youâ€™ll get an overview of the various techniques used to visualize, present and utilize data effectively, so agents of the internet of things system can drive results. Weâ€™ll explore data flow, cleansing, processing and analysis, all of which are critical to producing a result worth investing in by the customer. Youâ€™ll take a deep dive on concepts such as distributed computing, storage and end-user client applications, all in the context of the cloud. Weâ€™ll concentrate on extracting value from the data collected from devices, and from other relevant data, to generate an event or result.

Topics include:

How to store, process, present and visualize data from the internet of things.
- Setting up microservices in the cloud, including data schema, database, API development and server elements
- Simple and complex visualization tools
- Analysis of datasets 

This course expects that you have taken either Course 1 or Course 2 (preferrably both) of the UW IoT Certification Course (or are familiar with programming and the RPi sensors).

## Disclaimer

The materials of this course are the property of the University of Washington, and
are not to be posted on the internet or other forums.

They are for the personal use of the students attending the course.


## Instructor and Classroom Information

**Online Meeting Room:** [https://uwtest.zoom.us/j/546556168](https://uwtest.zoom.us/j/546556168)

**GitLab Repo Links**
- [Labs](https://gitlab.com/richardjortega/iot-310b-student.git)
- [Slides](https://gitlab.com/richardjortega/iot-310b-slides.git)

**MQTT Public Brokers**

If you run into a situation where a MQTT broker is not responding or refusing connection, feel free to change the broker.

- [IoT Eclipse MQTT Broker](https://iot.eclipse.org/getting-started#tutorials)
- [Mosquitto MQTT Broker](http://test.mosquitto.org/)

**Instructor: Richard Ortega**, Email: [riortega@uw.edu](mailto:riortega@uw.edu)

**TA: Bryan Palmer**, Email: [bpalmer@uw.edu](bpalmer@uw.edu)

**Class Sessions:** Thurdays 6:00 pm - 9:00 pm, PT. June 22nd - August 24th, 2017.

**Class Location:** 2445 140th Avenue N.E., Ste. B-100, Bellevue, WA 98005-1879 (Links to an external site.), Room 210

**In-Class Wi-Fi:**  
SSID: **UW-IoT110-R**  
Password: **piIoT110**  (Note: "I" in IoT is  "capital I" and not "lowercase L")

## Various Links

[UW-PCE IoT Website](https://www.pce.uw.edu/certificates/internet-of-things)  
[Canvas](https://canvas.uw.edu/)  

## Raspberry Pi 3 Information

*Note*: Link is from Course 2

[How to Setup your RPi3](https://gitlab.com/Gislason/iot-210B-student/tree/master/Lab1/PI_SETUP.md)

## Course 3 Required Lab Equipment List

**Note**: [Course 1](https://gitlab.com/iot110/iot110-student/) had more sensors/actuators to use, feel free to use those but primarily we will be using the SenseHAT for collecting data. 

| ITEM #  | DESCRIPTION |  QTY  | COST | COMPONENT | BUY URL| OTHER |
| :-----: | :---------- | :---: | ---: | :--------: | :-----------------| :-------- |
| 1  | Raspberry Pi 3 Kit | 1 | $89.95 | [RaspberryPi3](https://www.raspberrypi.org/) | [Adafruit](https://www.adafruit.com/products/3058) |  [Alternate](https://www.amazon.com/dp/B01C6Q4GLE?psc=1) |      
| 2  | Pi Sensor HAT    | 1 | $39.95 | Sensors | [Adafruit](https://www.adafruit.com/products/2738) | [Astro-Pi](https://astro-pi.org/) |
| 3  | Camera Module V2 | 1 | $29.60 | Sensors | [Amazon](https://www.amazon.com/Raspberry-Pi-Camera-Module-Megapixel/dp/B01ER2SKFS)
| 4  | TFT 5 inch Monitor |	1 | $59.95| | [Adafruit](https://www.adafruit.com/products/2232) | | |
| 5  | HDMI Flat Cable | 1 | $11.29 | | [Adafruit](https://www.adafruit.com/products/2197) | |
| 6  | Logitech Wireless Touch Keyboard K400 | 1 | $24.99 | | [Amazon](https://www.amazon.com/Logitech-920-007119-Wireless-Keyboard-Connected/dp/B014EUQOGK/) |
| 7 | Micro USB Charge Sync GOLD Data Cable | 2 |	$9.98 |	| [Amazon](http://amzn.to/2e49OHk) |
| 8 | Anker 24W Dual USB Wall Charger PowerPort 2 | 1 | $12.49 | | [Amazon](http://amzn.to/2ejevvC) |

## Session Breakdown

Section 1 | Time Allotted | Schedule
----- | ------ | ----
Lecture  | 30 Mins | 6:00-6:30pm
Lab  | 25 Mins | 6:30-6:55pm
Break  | 10 Mins | 6:55-7:05pm
Lab Continued  | 25 Mins | 7:05-7:30pm

Section 2 | Time Allotted | Schedule
----- | ------ | ----
Lecture  | 30 Mins | 7:30-8:00pm
Break  | 10 Mins | 8:00-8:10pm
Lab  | 50 Mins | 8:10-9:00pm

## Syllbus and Labs

Week | Date | Lab | Description
----- | ------ | ---- | -----
W1 | Jun 22 | [Lab 1]() | CENTRAL Edge v1 (NodeJS), CENTRAL FieldView (Electron)
W2 | Jun 29  | [Lab 2]() | CENTRAL Edge v2 (Docker), CENTRAL City API (App Service)
W3 | Jul 06 | [Lab 3]() | CENTRAL Link [Cloud Gateway (IoT Hub) <-> Device Gateway]
W4 | Jul 13 | [Lab 4]() | CENTRAL Citizen Finder (Face)/CENTRAL Citizen Happiness (Emotion)
W5 | Jul 20 | [Lab 5]() | Citizen Engagement Mobile App (Ionic), Mini-Capstone
W6 | Jul 27  | [Lab 6]() | CENTRAL Feedback (LUIS), CENTRAL Feedback Translator (Translator)
W7 | Aug 03 | [Lab 7]() | CENTRAL Ask Jarvis (Bot Framework, LUIS)
W8 | Aug 10 | [Lab 8]() | CENTRAL Precog 1 (Machine Learning)
W9 | Aug 17 | [Lab 9]() | CENTRAL Precog 2 (Machine Learning) 
W10 | Aug 24 | n/a   | Class IoT Hackathon: Smart Cities
# Week 1

Welcome to Week 1 everyone... it's going to be a fun ride, please provide feedback along the way.

- [Lab 1](lab1/README.md) - RPi, SenseHAT, and MQTT Revisited with a little Node.js
- [Lab 2](lab2/README.md) - Desktop Applications for Visualization with Electron

# Homework

- Setup a different MQTT topic to send/receive data from. Have the RPi send SenseHAT data to this new topic and have your Electron application use the new topic to recieve the data.
- Show Electron app working with a screenshot showing Node version, Chrome version, and Electron version.

![Example Homework](assets/homework1-example.png)
# RPi, SenseHAT, and MQTT Revisited with a little Node.js

## Overview

This lab is to get us collectively back to a stable point with our RPis and make sure everyone is on the same page. All version, libs, etc are running smoothly. We will run through some previous labs to get us up and running, these files have been modified to fit the Course 3 theme and focus only on their specific use case

Some files require system `python` dependencies to be installed. These were covered in Course 1, however, here are links to the packages.
- `mqtt` library can be found at the [Paho MQTT site](https://pypi.python.org/pypi/paho-mqtt/1.1#installation).
- `sense-hat` library can be found at the [SenseHAT site](https://github.com/RPi-Distro/python-sense-hat).

**Note**: Originally some files attempted to detect hostname and that worked well in class, but doesn't work well outside of class so this was removed in favor of a more manual approach. 

## Lab Links

- [MQTT python module](https://pypi.python.org/pypi/paho-mqtt/)
- [SenseHAT python module](https://github.com/RPi-Distro/python-sense-hat)
- [Node](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/)
- [MQTT npm module](https://github.com/mqttjs/MQTT.js)

## Use Case

Send and receive sensor data from device gateways across the city.

## Read SenseHAT data (from Course 1)

Let's find a file that grabs all the data we need from the SenseHAT and provides a JSON object we can use to send to a MQTT broker. Luckily, we built something similar in Course 1!

This file has been added for your convenience as `centralEdgeV1DeviceTest.py` within this directory. 

## Sending test data via MQTT client (from Course 2)

Let's try something a little different, we've converted a `python` file from Course 2 to be written in `javascript` that we will run on the RPi using `node` for the runtime.

This file has been added for your convenience as `centralEdgeV1-mqttTest.js` wthin this directory.

### Install Node.js and NPM

The following commands will install `node` and `npm` binaries to your RPi.

```bash
pi$ curl -sL http://deb.nodesource.com/setup_4.x | sudo -E bash
pi$ sudo apt-get -y install nodejs
```

### Verify successful installation

```bash
pi$ node --version
# v4.8.3
pi$ npm --version
# 2.15.11
```

### Install dependecies via `npm`

Run the following command from the **week1/lab1** folder.

```bash
~host/week1/lab1: $ npm install
```

### Run the code

Run the following command from the **week1/lab1** folder.

```bash
~host/week1/lab1: $ node centralEdgeV1-mqttTest.js
# Exit with CTRL+C
``` 

## Setup a MQTT Client and send SenseHAT data

Time to send some real data over the interwebs!

Using the `centralEdgeV1-Client.py` file provided, modify the `hostname` variable to include your own. We will use a topic channel of **iot-310b** with a subtopic of your hostname.


## Setup a MQTT Server for the RPi and Receive Other SenseHAT data

Have the RPi listen to other RPi messages (we've done this before, but good practice). 

Using the `centralEdgeV1-Server.py` file provided, modify the `hostname` variable to include your own. We will use a topic channel of **iot-310b** with a subtopic of your hostname.

## HACKER EDITION: Error Handling for MQTT Server

Currently, `centralEdgeV1-Server.py` will work fine for strings that contain JSON objects (as it will pase those JSON objects and turn it into a Python dictionary), however if a non-JSON compliant payload is sent it fails and exits. Update the code to support handling of general text (i.e. disregard non-JSON payloads).# Lab 2 - Desktop Applications for Visualization with Electron

## Use Case

City field reps require a desktop maintenance app to evaluate assets (sensor) functionality.

## Objectives 

- Learn the basics of Electron
  - Test out a demo app
  - Setup a starer project
- Have an editable dashboard Electron app that you can modify to your needs - codenamed **CENTRAL FieldView** for our class.

## Requirements

- Windows, Mac, or Linux machine

## Lab Links

- [Bootstrap 4 alpha](https://v4-alpha.getbootstrap.com/)
  - CSS framework used for styling
  - Installed via an [bootstrap npm module](https://github.com/twbs/bootstrap) within `package.json`
  - [Bootstrap Dashboard template](https://v4-alpha.getbootstrap.com/examples/dashboard/)
    - Click file **Save As > Web Page Complete** within your browser  to save HTML file with corresponding CSS links remove styling/presentation to liking.
  - [More boostrap starter examples](https://v4-alpha.getbootstrap.com/examples/)
- [Electron](https://electron.atom.io/)
  - Quick start guide can be found on home page
- [Node](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/)
- [MQTT npm module](https://github.com/mqttjs/MQTT.js)
- [WebSockets](https://en.wikipedia.org/wiki/WebSocket)

## What is NPM?

`npm` makes it easy for JavaScript developers to share and reuse code. We will be using `npm` (Node.js Package Manager) to assist us in downloading packages our applications we need. Additionally, NPM has a ton of reusable Node.js modules and libraries we can use. 

If youâ€™re familiar with any package manager â€œnpmâ€ works in a similar way (e.g. `apt` on Ubuntu Linux) . GUI versions of this are  Appleâ€™s App Store, Microsoftâ€™s Windows Store, and Googleâ€™s Play store -- they all download other packages not on your computer and install any dependencies that the package may require may have.

To get a high-level understanding of what NPM is doing for you with regards to package managing, watch the video on this link: 
- [https://docs.npmjs.com/getting-started/what-is-npm](https://docs.npmjs.com/getting-started/what-is-npm)

If you'd like to dive deeper (optional), here is a link that explains more on NPM:
- [https://www.sitepoint.com/beginners-guide-node-package-manager/](https://www.sitepoint.com/beginners-guide-node-package-manager/)


## Electron Overview

Electron enables you to create desktop applications with web technologies you know! HTML/CSS/JS! There is also a rich set of operating system APIs you can use (which we won't cover now). Electron uses Node.js runtime for the backend and Chromium for the frontend.

### Anatomy of an Electron app

An Electron app reflects a folder structure similar to a NodeJS application structure. If you don't have direct experience with that, no worries -- let's break it down.

**Example project structure**

```text
your-app/
â”œâ”€â”€ package.json
â”œâ”€â”€ main.js
â””â”€â”€ index.html
```

**Example `package.json`**

```json
{
  "name"    : "your-app",
  "version" : "0.1.0",
  "main"    : "main.js"
}
```

The file that describes all the required dependecies/packages needed to run/install the Electron app are within `package.json`. 

There is a default `main.js` that will load the `index.html` file as well. These two files will recieve the bulk of the updates/edits.


## Electron Demo App

### Download Electron Demos

Before you go down the process of working with Electron, it's best to see a final product. *Visual Studio Code*, *Atom* and *Slack* are popular desktop application  examples created using Electron (*Fun Fact: GitHub was originally called Atom Shell, used to build out Atom*).

Download the [Electron Demos App](https://github.com/electron/electron-api-demos/releases) to get a feel for what Electron can do (it shows off native OS API calls too!). Download the latest version (1.3.0 at time of writing) for your OS.

## Electron Quick Start app

Everything related to this guide is from the perspective of a field worker who has as laptop (we will use `$host` as an indicator) with internet connection. So run this on your laptop, not on the RPi.

### Install NodeJS

Follow the instructions at [https://nodejs.org/](https://nodejs.org/) to install Node.js (please install the **Current** release, v8.1.2 at time of writing). Downloads are available for Windows, Mac, and Linux.

Installing Node.js will also give you a package manager called `npm`.

Verify Successful Installation using the following commands:

```bash
host$ node --version
# v8.1.2
host$ npm --version
# v5.0.3
```

### Setup the Electron Quick Start app

This is verbatim from the [Electon Quick start](https://github.com/electron/electron-quick-start) website. It's a simple easy way to setup a minimal Electron app with file defaults, recommended folder structure, and preconfigured settings.

```bash
# Clone the Quick Start repository
host$ git clone https://github.com/electron/electron-quick-start

# Go into the repository
host$ cd electron-quick-start

# Install the dependencies and run
host$ npm install && npm start
```

A window should popup (your Electron app) and it should say "Hello, World!"

The command `npm start` is calling the following area of the file `package.json`. The value of `start` is `electron .`, so npm will fire that command on the terminal as if you wrote it.

```javascript
...

"scripts": {
    "start": "electron ."
  },

...
```

**Example Electron Starter App screenshot**

![ElectronStartApp](../assets/electron-quick-start.png)


## Setup CENTRAL FieldView app

For the purposes on this class, I've included all the necessary items from the git repo of [Electon Quick start](https://github.com/electron/electron-quick-start) so it's easier to work with to start *(e.g. Bootstrap 4 has already been added to the package list)*. Feel free to download the quick start in a separate folder so you can see what it contains and how it was mixed together for our purposes.

### MQTT npm module

To communicate over MQTT on the web we're going to use [WebSockets](https://en.wikipedia.org/wiki/WebSocket), specifically we going to send MQTT over WebSockets. Instead of creating and writing this from scratch, someone has already graciously created a library that just this.

The [MQTT npm module](https://github.com/mqttjs/MQTT.js) allows us to communicate on MQTT over WebSockets. This is our first `npm` module. The `mqtt` npm module (i.e package)  is a library that someone wrote and uploaded to the npm registry (place where you can download npm modules. When you call `npm install [package]` it finds that package and downloads it to a folder called `node_modules`. 

This package/dependency is defined within the `package.json` file. This was added to the `package.json`  file using the command `npm install mqtt`.

```javascript
...

"dependencies": {
    "bootstrap": "^4.0.0-alpha.6",
    "mqtt": "^2.9.0"
  },

...
```

#### MQTT over WebSockets

Open the file `centralView.html` within a text editor and notice that we are connecting to the MQTT server over WebSockets (another application layer protocol in the same vien as HTTP)! WebSockets will allow us to multiplex requests/responses to another server and keep a long lasting connection open. Most modern MQTT brokers provide WebSockets support.

**Example of MQTT broker url from `centralView.html`**

```javascript
var wsMQTTConnectionString = "ws://iot.eclipse.org:80/ws"
```

Also notice which MQTT topic we are subscribing to (**Note**: This will help in homework)

```javascript
var topic = 'iot-310b'
```

#### Install packages

Make sure you are within the **week1/lab2** folder as `npm` creates a folder called `node_modules` where it stores all the binaries for the packages installed. All packages to be installed are listed under `package.json`.

**Note**: Guide assumes you have already cloned this repo.

```bash
# Install dependencies
~host/week1/lab2:$ npm install
# Install electron globally
~host/week1/lab2:$ npm install electron -g
```

#### Run Electron app

Start the Electron app with:

```bash
~/host/week1/lab2:$ npm start
```

The previous command will start the Electron app. To see what's happening go to the file `package.json`.

Electron will first try to execute whatever value is set for `"main"` (typically `main.js`). If a value isn't provided, it will attempt to load `index.js`. 

If you review the `main.js` file, you can notice where the `centralView.html` webpage is being called and loaded.

```javascript
...

 // and load the index.html of the app.
  mainWindow.loadURL(url.format({
    pathname: path.join(__dirname, 'centralView.html'),
    protocol: 'file:',
    slashes: true
  }))
...

```

**Tips**:
- To exit the Electron app, go to the Electron File Menu and select "Electron" and "Quit/Exit".
- Edit HTML/CSS/JS files and hit the refresh shortcut on your computer to see it reflected within the app.

#### Verify CENTRAL FieldView app is receiving incoming MQTT message

The app is configures to listen on `iot-310b` topic. You should see messages coming through (provided messages are sending through).

![Example Working](../assets/exampleMQTTfieldview.png)

## HACKER EDITION: App Distribution

**Note**: Hacker Edition assignments are optional, don't count for anything but give you a starting point for where you should head next. If you'd like to use this in a professional setting.

Package your Electron app for distribution!!!
[https://github.com/electron/electron/blob/master/docs/tutorial/application-distribution.md](https://github.com/electron/electron/blob/master/docs/tutorial/application-distribution.md)# Week 2: Virtual Machines and Containers

Welcome to Week 2 everyone... it's going to be a fun ride, please provide feedback along the way.

- [Lab 1: Intro to Virtual Machines](lab1/README.md) 
- [Lab 2: Intro to Containers](lab2/README.md)

# Homework

*Note*: The homework can be turned in via screenshots, links to repos, and/or any other reference links. 

1. Modify the shell script in **lab1** inside `Vagrantfile` and install a non-installed Ubuntu package via `apt-get`. Take a screenshot of a successfully installed package. Along with a link to your `Vagrantfile`

2. Using your **centralView** dekstop app from Week1/Lab2, setup a custom MQTT topic that receives data from two new virtual devices:
    - One from a VM (instantiated with Vagrant/VirtualBox) - send a screenshot with VirtualBox GUI showing your VM and the message coming into centralView.
    - One from a container (instantiated from Docker) - send a screenshot of the output of `host$ docker ps -a` that should show a "Running" container. Have that adjacent to your centralView.# Intro to Virtual Machines

**Note**: To expedite speed of downloading the base Virtual Machine, run the following command now (after installing Vagrant from [https://www.vagrantup.com/downloads.html](https://www.vagrantup.com/downloads.html))

```bash
host$: vagrant box add ubuntu/xenial64
```

## Overview

This lab will help you get oriented with virtual machines using Vagrant to drive Virtualbox VMs that will ultimately run Ubuntu. We will be able to access the VM directly from terminal and control it. 

Virtual machines are a critical piece to modern cloud infrastructure, in these labs we'll be doing this all locally.

If you've ever setup a Virtual Machine before on your machine, you know that the process goes like this:

1. Download a hypervisor (e.g. VirtualBox, VMWare)
2. Download an ISO of your preferred OS (e.g. Ubuntu/CentOS) to virtualize.
3. Mount the ISO.
4. Walk through the OS installation process.
5. Have a new virtualized OS to do development on.
6. Install packages and system dependecies that your app needs.
7. Launch app and ensure everything is configured properly.
8. Completely forget everything you did on the VM and now never want to destroy it or mess too much with it because you're afraid it'll get into a bad state.
9. To prevent bad states, you snapshot the hell out of it.
10. You now move around a giant VM and all the baggage that it carries (e.g. large disk space, config files, etc)

This results in a "pet" and not "cattle" -- I'll explain this shortly. A  "pet" that you currently have today is your Raspberry Pi. If I told you to flash the SD card with another OS, some of you would be hesitant. Rightfully so, you've spent all this time configuring it, setting it up, and getting it "just right".

"In the old way of doing things, we treat our servers like pets, for example Bob the mail server. If Bob goes down, itâ€™s all hands on deck. The CEO canâ€™t get his email and itâ€™s the end of the world. In the new way, servers are numbered, like cattle in a herd. For example, www001 to www100. When one server goes down, itâ€™s taken out back, shot, and replaced on the line." -- Randy Bias, [The History of Pets vs Cattle](http://cloudscaling.com/blog/cloud-computing/the-history-of-pets-vs-cattle/)

Today, we're going to make some cattle.

## Lab Links

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com)
    - [Docs](https://www.vagrantup.com/docs/index.html)
    - [Boxes](https://app.vagrantup.com/boxes/search)
        - A registry where people upload VMs that have already have a "base" image. An example of a "base" image is downloading an Ubuntu box which already has Ubuntu installed and configured (as well as loading your Vagrant ssh keys).
    - [Provisioners](https://www.vagrantup.com/docs/provisioning/basic_usage.html)
        - Provisioners allow you use to a configuration management tool of your choice (e.g. Chef, Ansible, Puppet, etc) for provisioning a VM. We will not go too deep into this and will use only the shell scripting via Bash.
- [Ubuntu](https://www.ubuntu.com/)
    - We will use Ubuntu 16.04 for virtual machines and containers.
    - [apt - Ubuntu Package Manager](https://help.ubuntu.com/community/AptGet/Howto)

## Use Case

For development purposes, provide a consistent way of provisioning VMs.

## VirtualBox

We will use VirtualBox as our hypervisor to virtualize the Linux operating system Ubuntu. VirtualBox is available for Mac, Windows and Linux.

### Install VirtualBox

- Go to [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads) to download VirtualBox for your specific host.
    - Install VirtualBox via the downloaded binary.
- After installing VirtualBox download the [VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
    - Install extension pack onto VirtualBox using the downloaded binary.

## Up and Running with Vagrant

### Overview

**Note**: The following guide on Vagrant is not to be used for provisioning or scaling production VMs. 

"Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past." [Source](https://www.vagrantup.com/intro/index.html)

We will use Vagrant to automate virtual machine provisioning of VirtualBox VMs.

### Install Vagrant

Download Vagrant at [https://www.vagrantup.com/downloads.html](https://www.vagrantup.com/downloads.html) for your specific host. Install using the downloaded binary.

### Initialize a `Vagrantfile` and Create a Virtual Machine

The following commands will:
- Initialize this current folder with a `Vagrantfile`
- Download a [Vagrant Box](https://app.vagrantup.com/boxes/search)
    - **Note**: This process may take a while depending on connection speed.
- Startup the VM.

```bash
host ~week2/lab1$ vagrant init ubuntu/xenial64
host ~week2/lab1$ vagrant up
```

After running the above two commands, you will have a fully running virtual machine in VirtualBox running Ubuntu 16.04 LTS 64-bit. 

The `vagrant up` command references a file called `Vagrantfile` that was created in this folder when we initialized this folder for Vagrant using `vagrant init [BOX IMAGE]`. In this case, we told it to pull down the Vagrant Box image from [Vagrant Box](https://app.vagrantup.com/boxes/search). To learn more about Vagrant Boxes click [here](https://www.vagrantup.com/intro/getting-started/boxes.html).

You can verify this visually by opening the VirtualBox application on your host machine. You will see a VM state of "running" and the operating system will say "Ubuntu 64-bit".

![vagrant-vbox](../assets/virtualbox-vagrant.png)

### Accessing the VM

SSH into the VM!

```bash
# Assumes VM is running
host ~week2/lab1$ vagrant ssh
```

From here, you can do whatever you would normally want to do with an Ubuntu Linux machine. 

```bash
# Assumes ssh'ed into VM, play around!
ubuntu@ubuntu-xenial:~$ echo "Hello, world!"
ubuntu@ubuntu-xenial:~$ uname -a 
```

Exit the VM:

```bash
ubuntu@ubuntu-xenial:~$ exit 
```

### Halt the VM, Destroy the VM

We mentioned earlier about "pets" vs "cattle" and we're going to show it now. We'll stop the VM, destroy it, and in the next section setup new provisioning steps for the new VM instance to follow.

Halt the VM:

```bash
# Assumes VM is running
host ~week2/lab1$ vagrant halt
```

Verify the VM is powered off (or you can look at VirtualBox GUI):

```bash
host ~week2/lab1$ vagrant status

# Current machine states:
# default                   poweroff (virtualbox)
```

Now destroy the VM instance!

```bash
# Assumes VM is powered off
host ~week2/lab1$ vagrant destroy
# default: Are you sure you want to destroy the 'default' VM? [y/N] y
# ==> default: Destroying VM and associated drives...
```

So what did the command destroy? It destroyed the instance of our VM, however our "base" image (i.e. Vagrant box) that we initially used to build the VM is still available locally. Which means we can build another instance using this base image and provision another VM instance.

```bash
host ~week2/lab1$ vagrant box list
# ubuntu/xenial64 (virtualbox, 20170626.0.0)
```

## Provisioning the VM

Now let's use what we've learned to create a new VM, except now we'll add custom provisioning.

**Note**: The `Vagrantfile` is written in Ruby, so it's sometimes helpful to change your syntax highlighting to "Ruby" when working in the file.

Open `Vagrantfile` and change the following lines (which are commented out near the bottom of the file):

```ruby
# config.vm.provision "shell", inline: <<-SHELL
#   apt-get update
#   apt-get install -y apache2
# SHELL
```

To the following:

```ruby
config.vm.provision "file", source: "centralVirtualDevice.py", destination: "centralVirtualDevice.py"

config.vm.provision "shell", inline: <<-SHELL
    # Celebrate!
    echo "I provisioned a headless VM using Vagrant!"

    # Update list of packages
    apt-get update

    # Install python
    # Note: "-y" option is used since we are not in an interactive session.
    #   This will tell the apt-get installer to say "Y" when input is expected
    apt-get install -y python

    # Download pip for Python 2
    wget https://bootstrap.pypa.io/get-pip.py

    # Install pip for Python 2
    python get-pip.py

    # Install Python MQTT client
    pip install paho-mqtt

    # Check version
    python --version
SHELL
```

Create a new VM instance:

```bash
host ~week2/lab1$ vagrant up
# ...
# ==> default: Setting up libpython-stdlib:amd64 (2.7.11-1) ...
# ==> default: Setting up python (2.7.11-1) ...
# ==> default: Python 2.7.12
# ...
```

What did this do? It updated all the Ubuntu apt packages lists, installed the preferred Python version for this version of Ubuntu, verified installation of Python, added our file called `centralVirtualDevice.py` along with dependencies we need to run that file on a new machine (e.g. `pip` and `paho-mqtt`). 

You can access the VM via SSH and run the Python file:

```bash
host ~week2/lab1$ vagrant ssh

ubuntu@ubuntu-xenial:~$ ls
# centralVirtualDevice.py

ubuntu@ubuntu-xenial:~$ python centralVirtualDevice.py
```

You now know how to work on VMs in an effective manner for local development.

Feel free to shutdown your VM if you want:

```bash
# Assumes VM is running
host ~week2/lab1$ vagrant halt
```

## Troubleshooting

If you delete the `Vagrantfile` before destroying your VM you can put yourself in a bad situation (i.e. Vagrant doesn't know how to drive VirtualBox and all references are gone). If that happens, remove the VM from the VirtualBox GUI. Ideally, delete VM instance using `vagrant destroy` and then delete the `Vagrantfile` (if you wanted to). Also, don't make changes inside of VirtualBox GUI, all options and configs should be defined within the `Vagrantfile`.


## Hacker Edition (optional): VirtualBox Settings, Networking and Synced Folders

Set VirtualBox configs 
(e.g. memory/cpus) using: [https://www.vagrantup.com/docs/virtualbox/configuration.html](https://www.vagrantup.com/docs/virtualbox/configuration.html)

Other areas to learn that are extremely helpful are:
- [Networking](https://www.vagrantup.com/intro/getting-started/networking.html)
- [Synced Folders](https://www.vagrantup.com/intro/getting-started/synced_folders.html)
- [Shell External Scripts](https://www.vagrantup.com/docs/provisioning/shell.html#external-script)# Intro to Containers

## Overview

This lab will help you get oriented with Docker and why we are using it. 

## Lab Links

- [Docker](https://www.docker.com/)
- [Docker Hub Registry](https://hub.docker.com/)
    - Images uploaded to this registry are maintained by the community and have no support from Docker directly.
- [Docker Store](https://store.docker.com/)
    - This link is only provided as a reference. More details on Docker Store can be found [here](https://docs.docker.com/docker-store/).
    - The Docker Store provides Docker Verified images (as well as access to Docker Hub images). These Docker Verified images are verified by Docker, have a high level of security, and generally subscribe to Docker best practices.
    - In an enterprise setting, this likely would be the route to choose (as depending on publisher) may include a paid support level.

## Use Case

Investigate a way to optimize application density at the edge devices.

## Docker Overview

"Docker provides a method of developing, shipping, and running applications. Docker provides the ability to package and run an application in a loosely isolated environment called a container. The isolation and security allow you to run many containers simultaneously on a given host. Containers are lightweight because they donâ€™t need the extra load of a hypervisor, but run directly within the host machineâ€™s kernel. This means you can run more containers on a given hardware combination than if you were using virtual machines. You can even run Docker containers within host machines that are actually virtual machines!" [Source](https://docs.docker.com/engine/docker-overview/)

In the context of Docker, an **image** is the binary file that contains your code, your code packages, and any system level dependencies. A **container** is an instance of an image. 

This will make more sense during the lab. Right now, it's important to note that at a high-level the following points are key takeaways for containers [Source](https://docs.docker.com/engine/docker-overview/#what-can-i-use-docker-for):

- Fast, consistent delivery of your applications
    - Work in standardized environments using local containers which provide your applications and services.
- Responsive deployment and scaling
    - Because of the portability and how lightweight Docker is, you can dynamically manage workloads, scale up/tear down services with ease in near real-time.
- Running more workloads on the same hardware
    - You can increase app density on the same hardware over hypervisor-based virtual machines, so you can use more of your compute capacity to achieve your business goals. Docker is perfect for high density environments and for small and medium deployments where you need to do more with fewer resources (e.g. the Raspberry Pi).

Let's get into it!

## Docker Overview

Docker project (open-sourced by dotCloud in March '13) consists of several main parts (applications) and elements (used by these parts) which are all [mostly] built on top of already existing functionality, libraries and frameworks offered by the Linux kernel and third-parties (e.g. LXC, device-mapper, aufs etc.).

### Main Docker Parts

- docker daemon: used to manage docker containers on the host it runs
- docker CLI: used to command and communicate with the docker daemon
- docker hub registry: a repository (public or private) for docker images
- docker store: a trusted repository of images maintained by docker or first-party developers

### Main Docker Elements

- docker containers: directories containing everything-your-application
- docker images: snapshots of containers or base OS (e.g. Ubuntu) images
- Dockerfiles: scripts automating the building process of images

## Installing Docker

We will install the **Docker Community Edition** on your host machine. You can download it here: [Docker Community Edition](https://www.docker.com/community-edition).

Verify successful installation by opening your host machine's shell and enter:

```bash
host$ docker run hello-world
```

You will see some output similar to:

```text
Hello from Docker!
This message shows that your installation appears to be working correctly.
...
```

You can search for images available on Docker Hub by using the docker command with the `search` subcommand. For example, to search for the Ubuntu image, type:

```bash
host$ docker search ubuntu   
```

Alternatively, you can search on the [Docker Hub Registry](https://hub.docker.com/) website.

In the OFFICIAL column, OK indicates an image built and supported by the company behind the project. Once you've identified the image that you would like to use, you can download it to your computer using the `pull` subcommand, like so:

```bash
host$: docker pull ubuntu
```

After an image has been downloaded, you may then run a container using the downloaded image with the `run` subcommand. If an image has not been downloaded when docker is executed with the `run` subcommand, the Docker client will first download the image, then run a container using it:

```bash
host$: docker run ubuntu
```

To see the images that have been downloaded to your computer, type:

```bash
host$: docker images
```

The output should look similar to the following:

```text
Output
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
ubuntu              latest              d355ed3537e9        7 days ago          120.8 MB
hello-world         latest              1815c82652c0        2 weeks ago         967 B
```

The `hello-world` container you ran in the previous is an example of a container that runs and exits, after emitting a test message. Containers, however, can be much more useful than that, and they can be interactive. After all, they are similar to virtual machines, only more resource-friendly.

As an example, let's run a container using the latest image of Ubuntu. The combination of the -i and -t switches gives you interactive shell access into the container:

```bash
host$: docker run -it ubuntu
```

Your command prompt should change to reflect the fact that you're now working inside the container and should take this form:

```bash
root@33b7ca72ea69:/#
```

Important: Note the container id in the command prompt. In the above example, it is 33b7ca72ea69.

Now you may run any command inside the container. For example, let's update the package database inside the container. No need to prefix any command with sudo, because you're operating inside the container with root privileges:

```bash
container$: apt-get update
```

Then install any application in it. Let's install NodeJS, for example.

```bash
container$: apt-get install -y nodejs
```

This command pulled an [Ubuntu image from Docker Hub](https://hub.docker.com/_/ubuntu/). Docker uses a file called `Dockerfile` to describe how a Docker image should consist of, we'll see more of this later.

You can already see how powerful this can be... you've downloaded an Ubuntu environment that acts and works very similar to an Ubuntu VM except much more lightweight than the VMs.

In the next step we'll recreate what we did in Lab 1 but within containers.

## Containerize `centralVirtualDevice.py`

Let's go ahead and download a Docker container that already has Python 2.7 installed. 

Open the included file called `Dockerfile`, go line by line and read what is happening. We can add more comments if necessary, but at a high-level it's equivalent to the provisioning we did within the `Vagrantfile`.

Because we created our own `Dockerfile` we need to build a image and have Docker run all the commands we have told it. The following command will build the image (layer by layer), tag it with a name, and use the `Dockerfile` in the current directory.

```bash
host ~/week2/lab2$ docker build -t central_virtual_device .
```

Look at the new image you've made at:

```bash
host$ docker images
```

Now run your container:

```bash
host$ docker run -it central_virtual_device
```

This will instantiate a new container based off of the `central_virtual_device` image and will latch onto your terminal. 

If you want to run in a daemonized mode, run:

```bash
host$ docker run -d central_virtual_device
```

## Pushing up to Docker Hub

We can also push the image we created to Docker Hub.

- [Signup for Docker Hub](https://hub.docker.com/)

You can now log into Docker Hub from the terminal:

```bash
# Use the username and password you used in Docker Hub
host$ docker login
```

We are going to add another tag for our custom image that will work with Docker Hub Registry

```bash
# Usage: docker tag [image] [new image name]
#   Example: docker tag central_virtual_device [dockerHubUsername]/central_virtual_device
host$ docker tag central_virtual_device richardjortega/central_virtual_device
```

We can push your image up to Docker Hub so other people can download it:

```bash
host$ docker push richardjortega/central_virtual_device
```

I can now view my uploaded image at Docker Hub: [https://hub.docker.com/r/richardjortega/central_virtual_device/](https://hub.docker.com/r/richardjortega/central_virtual_device/)

Other people can directly pull the image and run on their machine:

```bash
host $: docker pull richardjortega/central_virtual_device
```

## Hacker Edition: Learn about adding app data within containers

- Add a `test.txt` file (with your own arbitrary text) to the image we created using `Dockerfile`. Upload the new image to DockerHub and provide a link to your DockerHub.
    - Tip: Use `COPY` command: [https://docs.docker.com/engine/reference/builder/#copy](https://docs.docker.com/engine/reference/builder/#copy)

- In a standard development workflow with Docker, developers will typically mount their host's application  folder to the container's application folder providing a way to edit code locally on the host and it reflecting immediately within the container.
    - You can read more about this on [Manage data in containers](https://docs.docker.com/engine/tutorials/dockervolumes/) under the section [Mount a Host Directory as a Data Volume](https://docs.docker.com/engine/tutorials/dockervolumes/#mount-a-host-directory-as-a-data-volumeMount)# IOT 110A/B - Internet of Things: Foundations Student Resource Repository #

## Link to Adobe Connect Online 
[Online Meeting Room](http://uweoconnect.extn.washington.edu/iot110/)

## Setting up RPi3
[RPi3 Setup](https://gitlab.com/iot110/iot110-student/blob/master/Resources/PI_SETUP.md)

## Outline
* [Lab 1](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab1/setup.md) - Flask WebApp - Hello IoT World!
* [Lab 2](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md) - LEDs and Switches (GPIO) via Python
* [Lab 3](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md) - Server Sent Events and Bootstrap UI
* [Lab 4](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md) - Sensors: I2C Pressure/Temperature via the BMP280
* [Lab 5](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md) - Sensors: Thing Data Protocols/Webapp for the BMP280
* [Lab 6](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md) - Sensors: Thing Data Protocols/Webapp for the SenseHat
* [Lab 7](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md) - Actuators: PWM LED Dimmer Controller & Stepper Motor / via the TB6612
* [Lab 8](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md) - Basic Networking (Simple Gateway Edge Devices)
* [Lab 9](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/setup.md) - Collect to Cloud using MQTT

## Webpage
[UW-PCE IoT Website](https://www.pce.uw.edu/certificates/internet-of-things)


## Lab Equipment List
| ITEM #  | DESCRIPTION |  QTY  | COST | COMPONENT | BUY URL| OTHER |
| :-----: | :---------- | :---: | ---: | :--------: | :-----------------| :-------- |
| 1  | Raspberry Pi 3 Kit | 1 | $89.95 | [RaspberryPi3](https://www.raspberrypi.org/) | [Adafruit](https://www.adafruit.com/products/3058) |  [Alternate](https://www.amazon.com/dp/B01C6Q4GLE?psc=1) |      
| 2  | Pi Sensor HAT    | 1 | $39.95 | Sensors | [Adafruit](https://www.adafruit.com/products/2738) | [Astro-Pi](https://astro-pi.org/) |
| 3  | Barometric Pressure & Temperature Sensor | 1 | $9.95 | [BMP280](https://www.bosch-sensortec.com/bst/products/all_products/bmp280) | [Adafruit](https://www.adafruit.com/products/2651) | [AppNote](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-bmp280-barometric-pressure-plus-temperature-sensor-breakout.pdf) | [Datasheet](https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf) |
| 4  | Stepper Motor Breakout Board | 1 | $4.95 | [TB6612](http://toshiba.semicon-storage.com/ap-en/product/linear/motordriver/detail.TB6612FNG.html) | [Adafruit](https://www.adafruit.com/products/2448) | [AppNote](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-tb6612-h-bridge-dc-stepper-motor-driver-breakout.pdf) | [Datasheet](http://toshiba.semicon-storage.com/ap-en/product/linear/motordriver/detail.TB6612FNG.html) |
| 5  | NEMA 17 Stepper Motor| 1 | $14.00 | | [Adafruit ](https://www.adafruit.com/products/324) | |
| 6  | Automotive Gauge Stepper Motor | 1| $9.95| | [AutoNeedle](https://www.adafruit.com/products/2424) | |
| 7  | TFT 5 inch Monitor |	1 | $13.32 | | [Adafruit](https://www.adafruit.com/products/2232) | | |
| 8  | HDMI Flat Cable | 1 | $11.29 | | [Adafruit](https://www.adafruit.com/products/2197) | |
| 9  | Microsoft Keyboard | 1 | $59.95 | | [Amazon](http://amzn.to/2djI91K) |
| 10 | Microsoft Wired Mouse | 1 | $3.95 | | [Amazon](http://amzn.to/2esKjlm) |
| 11 | Micro USB Charge Sync GOLD Data Cable | 2 |	$9.98 |	| [Amazon](http://amzn.to/2e49OHk) |
| 12 | Anker 24W Dual USB Wall Charger PowerPort 2 | 1 | $12.49 | | [Amazon](http://amzn.to/2ejevvC) |
| 13 | STRAP BATT ECON 9V I STYLE 4"LD |	1 | $0.60 | | [Digikey](http://bit.ly/2gFinYM) |
| 14 | Alkaline Battery Non-Rechargeable 9V | 2 | $4.76 | | [Digikey](http://bit.ly/2fLQYYl) |
| 15 | HEX STANDOFF 4-40 NYLON 1/2" | 8 | $5.60 | | [Digikey](http://bit.ly/2iWFqOT) |
| 16 | MACHINE SCREW PAN PHILLIPS 4-40 | 8 | $0.80 | | [Digikey](http://bit.ly/2iqhxlT) |
| 17 | 2 Position Wire to Board Terminal Block | 1	| $0.57 | | [Digikey](http://bit.ly/2gMUtgG) |
|    | | TOTAL | $292.06 | | |
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab1

### Objectives
For this lab we will be setting up a local web application running on the RPi
that will act as our primary user interface in a *headless* mode (i.e. not
requiring the HDMI graphic monitor connected to the RPi to interact with our
sensor and actuator devices.  The scope of this lab will ensure that we are
successful in connecting our networked RPi3 *Thing* controller, we are able to
log into the device, connect its file system to our development host (via sshfs)
and use the Atom editor to build our initial Python *Flask* Web Application.

The various steps of this lab are summarized as:
* Install Flask (lightweight Python Webserver)
* Ensure that we have ssh keys installed and sshfs operating smoothly.
* Build a Hello IoT WebApp using
* Run the Webserver from RPi3
* Test the Webserver from Browser and CLI

### Step 1: Getting Flask
```
pi$ pip install flask

```
### Step 2: Ensure ssh keys and sshfs operating smoothly
Secure shell (ssh) is the most universal and secure method to connect between
two computers, to transfer files (via the scp command) and to mount a
target's file system into the development host (via the sshfs command).

### Step 3: Build a Hello IoT App
Using the sshfs mounted folders and the Atom editor build the Flask demo
Web Application ```hello.py```.  This application will reply with a
simple HTML greeting page plus the hostname that was established during the
setup phase:

#### > Step 3a: Flask and socket
``` python
from flask import Flask
import socket
```

#### > Step 3b: Obtaining RPi Hostname from Socket Library
``` python
## Get my machine hostname
if socket.gethostname().find('.') >= 0:
    hostname=socket.gethostname()
else:
    hostname=socket.gethostbyaddr(socket.gethostname())[0]
```

#### > Step 3c: Create the Flash Webserver app
``` python
app = Flask(__name__)
```

#### > Step 3d: Establish the default "route"
``` python
@app.route("/")
def hello():
    return "Hello IoT World from RPi3: " + hostname
```

#### > Step 3e: Code to run server on port 5000
``` python
## Run the website and make sure to make
##  it externally visible with 0.0.0.0:5000 (default port)
if __name__ == "__main__":
    app.run(host='0.0.0.0')
```

### Start the webserver and run the hello.py app

```sh
pi$ python hello.py
 => runs the flask webserver from http://0.0.0.0, port 5000 for external access
```

### Test the hello.py WebApp from CLI and Remote Browser
```
pi$ curl http://0.0.0.0:5000
Hello IoT World from RPi3 (hostname) : iot8e3c.iot!

pi$ ifconfig | grep "inet addr"
 => inet addr:**192.168.10.19**  Bcast:192.168.10.255  Mask:255.255.255.0

host$ curl http://192.168.10.19:5000
=> Hello IoT World from RPi3 (hostname) : iot8e3c.iot!

host$ curl http://iot8e3c:5000
=> Hello IoT World from RPi3 (hostname) : iot8e3c.iot!
```

![HelloIoT](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/Hello-IoT_416x288.png)


[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part A - OO Python GPIO Driver ###
**Synopsis:** A good architectural design starts with partitioning the system
into components. One such component in our IoT system will be a GPIO interface
driver for the 3 LEDs and one pushbutton switch we have defined. We will design
methods for each of the actions and then a unit test to exercise each of these
methods with the target hardware on our RPi breadboard.

#### Step A1: Building a Simple GPIO Python Driver
**Objective:** We'll design a simple object oriented Python module to handle I/O
for our project.  Let's start by creating a file called ```gpio.py``` and
importing libraries we will need for handling Raspberry PI GPIO.
``` python
import RPi.GPIO as GPIO
```
Next we will define each of the pins we will use for the LEDs and SWITCH.
``` python
LED1_PIN    = 18    # cobbler pin 12 (GPIO18)
LED2_PIN    = 13    # cobbler pin 33 (GPIO13)
LED3_PIN    = 23    # cobbler pin 16 (GPIO23)
SWITCH_PIN  = 27    # cobbler pin 7  (GPIO27)
```
Next we'll declare the name of the class we will use to instantiate our GPIO
object from our web server code.
```python
class PiGpio(object):
    """Raspberry Pi Internet 'IoT GPIO'."""
```
We need to define what happens when we initialize the driver in an init method.
``` python
def __init__(self):
    GPIO.setwarnings(False)
    GPIO.setmode(GPIO.BCM)
    GPIO.setup(LED1_PIN, GPIO.OUT)      # RED LED as output
    GPIO.setup(LED2_PIN, GPIO.OUT)      # GRN LED as output
    GPIO.setup(LED3_PIN, GPIO.OUT)      # BLU LED as output
    GPIO.setup(SWITCH_PIN, GPIO.IN)     # Switch as input w/pu
    GPIO.setup(SWITCH_PIN, GPIO.IN, pull_up_down=GPIO.PUD_UP)
```

Next we need a GPIO method to handle reading of the input switch pin. Notice
that we will invert the logic of the pin due to the momentary switch circuit
that grounds out the input upon pressing the switch down.
``` python
def read_switch(self):
    """Read the switch state."""
    switch = GPIO.input(SWITCH_PIN)
    # invert because of active low momentary switch
    if (switch == 0):
        switch=1
    else:
        switch=0
    return switch
```

And finally, we need ```getter``` and ```setter``` methods for the LED control
for each of the 3 LEDs we have defined.
``` python
# set the particular LED to ON or OFF
def set_led(self, led, value):
    """Change the LED to the passed in value, '1 ON or '0' OFF."""
    if(led == 1):
        GPIO.output(LED1_PIN, value)
    if(led == 2):
        GPIO.output(LED2_PIN, value)
    if(led == 3):
        GPIO.output(LED3_PIN, value)

# get the state of an LED
def get_led(self, led):
    """Return the state value of the LED, '1' ON or '0' OFF."""
    if(led == 1):
        return GPIO.input(LED1_PIN)
    if(led == 2):
        return GPIO.input(LED2_PIN)
    if(led == 3):
        return GPIO.input(LED3_PIN)
```

#### Step A2: GPIO Driver Unit Test
**Objective:** In order to thoroughly test our ```gpio.py``` driver we need some
low level unit test code that can be run from the command line shell as follows
(along with its corresponding output):
``` sh
pi$ ./gpio_test.py

============ Switch: 0 ============
LED 1 ON (RED)
LED1: 1
LED2: 0
LED3: 0

LED 2 ON (GRN)
LED1: 1
LED2: 1
LED3: 0

LED 3 ON (BLU)
LED1: 1
LED2: 1
LED3: 1

LED 1 OFF (RED)
LED1: 0
LED2: 1
LED3: 1

LED 2 OFF (GRN)
LED1: 0
LED2: 0
LED3: 1

LED 3 OFF (BLU)
LED1: 0
LED2: 0
LED3: 0
```
We will start by importing our GPIO driver and the time function we will need
for some time delays.  Note also the inclusion of a "she-bang" which will be
used to turn this file into an executable by telling the Linux shell where to
find the Python program at ```/usr/bin/python```.

```python
#!/usr/bin/python
import time
from gpio import PiGpio
```

In order to test the driver, we will need to instantiate it.
```python
# create an instance of the pi gpio driver.
pi_gpio= PiGpio()
```

Next we will simply run a forever while loop to test each of the methods
```python
# Blink the LEDS forever.
print('Blinking all my LEDs in sequence (Ctrl-C to stop)...')
while True:
# Get the current switch state and print
    switch = pi_gpio.read_switch()
    print('\n============ Switch: {0} ============'.format(switch))

    print('\nLED 1 ON (RED)')
    pi_gpio.set_led(1,True)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)

    print('\nLED 2 ON (GRN)')
    pi_gpio.set_led(2,True)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)

    print('\nLED 3 ON (BLU)')
    pi_gpio.set_led(3,True)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)


    print('\nLED 1 OFF (RED)')
    pi_gpio.set_led(1,False)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)

    print('\nLED 2 OFF (GRN)')
    pi_gpio.set_led(2,False)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)

    print('\nLED 3 OFF (BLU)')
    pi_gpio.set_led(3,False)
    print('LED1: {0}'.format(pi_gpio.get_led(1)))
    print('LED2: {0}'.format(pi_gpio.get_led(2)))
    print('LED3: {0}'.format(pi_gpio.get_led(3)))
    time.sleep(1.0)
```
In order to run this unit test from the command line it will need to be made
executable.
```sh
pi$ chmod +x gpio_test.py
```
Then it can be run using the "./" method of execution from the command line.

[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part B -  Simple Flask API Webserver ###
**Objective:** We will be using HTTP GET and POST APIs as our basic method of
interfacing between our Webapp and the Python sensor and actuator driver code.  
The following is just an exercise to focus on how APIs work and how to test them
from the CLI (bash shell).

#### Step B1: import Flask and request support
Open a new file called ```api_server.py``` and enter the following sections:
Import the same structure as ```hello.py``` but provide support for parsing
requests.  Get the hostname as well and instantiate the Flash app object.
Place the app.run at the bottom of the file.  We will add each API and perform
a CURL test on each as we add them.
```python
from flask import Flask, request
import socket

## Get my machine hostname
if socket.gethostname().find('.')>=0:
    hostname=socket.gethostname()
else:
    hostname=socket.gethostbyaddr(socket.gethostname())[0]

app = Flask(__name__)


... API routes to be added below

## Run the website and make sure to make
##  it externally visible with 0.0.0.0:5000 (default)
if __name__ == "__main__":
    app.debug = True
    app.run(host='0.0.0.0')
```

#### Step B2: Add and Test Routes/API types
Add API routes for DEFAULT and a basic GET REQUEST.
```python
#DEFAULT Route
# curl http://0.0.0.0:5000/
@app.route("/")
def hello():
    return "Hello API Server : Default Request from (hostname) : " + hostname + "!\n"

#GET REQUEST
# curl http://0.0.0.0:5000/getHello
@app.route('/getHello')
def getRequestHello():
    return "Hello API Server : GET Request!\n"
```

Test these first two APIs by CURLing their hostname:5000
```sh
host$ curl iot8e3c.home:5000
=> Hello API Server : Default Request from (hostname) : iot8e3c.home!

host$ curl iot8e3c.home:5000/getHello
=> Hello API Server : GET Request!
```

Now, let's add a HTTP POST API request. **Note:** you can just add in the new
and save and the Flask framework will automatically restart for you after
detecting a file change.
```python
#POST REQUEST
# curl --data 'mykey=FOOBAR' http://0.0.0.0:5000/createHello
# echo 'mykey={"name":"Gene Cernan","age":"82"}' | curl -d @- http://0.0.0.0:5000/createHello
@app.route('/createHello', methods = ['POST'])
def postRequestHello():
    mydata = request.data
    print "Data:" + mydata
    assert request.path == '/createHello'
    assert request.method == 'POST'
    data = str(request.form['mykey'])
    # import pdb; pdb.set_trace()
    return "Hello API Server : You sent a "+ request.method + \
            " message on route path " + request.path + \
            " \n\tData:" +  data + "\n"
```

Test the POST API by CURLing with a slightly different way of passing data. We
will explore a couple of methods:
```sh
host$ curl --data 'mykey=FOOBAR' iot8e3c:5000/createHello
=> Hello API Server : You sent a POST message on route path /createHello
	 Data:FOOBAR

host$ echo 'mykey={"name":"Gene Cernan","age":"82"}' | curl -d @- iot8e3c:5000/createHello
=> Hello API Server : You sent a POST message on route path /createHello
	 Data:{"name":"Gene Cernan","age":"82"}
```
**GREAT!** Now you are empowered to create all manner of GET and POST API calls.

[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part C -  GPIO Webserver ###
**Objective:** Now its time to flesh out our main web server application ```main.py```
that will serve as the main interface between our GPIO python driver and the HTML
webpage ```index.html```.

#### Step C1: import Flask and request support and main execution (bottom)
Let's start by importing our Flask framework as well as our GPIO driver module
and instantiating objects for each:
```python
from gpio import PiGpio
from flask import *

app = Flask(__name__)
pi_gpio = PiGpio()

... add APIs <here>

if __name__ == "__main__":
    app.run(host='0.0.0.0', debug=True)
```

#### Step C2: Default Route
Next we need to add the default route.  In other words, this is the route that
will be executed whenever the main webpage is rendered on port 5000.  Note that
this default webpage load also contains code to read the current state of the
hardware and place in some python local variables.  These variables are then
passed by some new variable namespace that will be passed to
a *template* ```index.html``` file (located in a templates directory off the
root directory).  As we will see shortly these variables are accessible to the
HTML document in a special embedded scripting syntax  {{ python code }} supported
by the Flask framework.
```python
@app.route("/")
def index():
    # create an instance of my pi gpio object class.
    pi_gpio = PiGpio()
    switch_state = pi_gpio.read_switch()
    led1_state = pi_gpio.get_led(1)
    led2_state = pi_gpio.get_led(2)
    led3_state = pi_gpio.get_led(3)
    return render_template('index.html', switch=switch_state,
                                led1=led1_state,
                                led2=led2_state,
                                led3=led3_state)
```

#### Step C3: Add all of our GPIO API Routes
```python
# ============================== API Routes ===================================
# ============================ GET: /leds/<state> =============================
# read the LED status by GET method from curl for example
# curl http://iot8e3c:5000/led/1
# curl http://iot8e3c:5000/led/2
# -----------------------------------------------------------------------------
@app.route("/leds/<int:led_state>", methods=['GET'])
def leds(led_state):
  return "LED State:" + str(pi_gpio.get_led(led_state)) + "\n"


# =============================== GET: /sw ====================================
# read the switch input by GET method from curl for example
# curl http://iot8e3c:5000/sw
# -----------------------------------------------------------------------------
@app.route("/sw", methods=['GET'])
def sw():
  return "Switch State:" + str(pi_gpio.read_switch()) + "!\n"

# ======================= POST: /ledcmd/<data> =========================
# set the LED state by POST method from curl. For example:
# curl --data 'led=1&state=ON' http://iot8e3c:5000/ledcmd
# -----------------------------------------------------------------------------
@app.route("/ledcmd", methods=['POST'])
def ledcommand():
    cmd_data = request.data
    print "LED Command:" + cmd_data
    led = int(str(request.form['led']))
    state = str(request.form['state'])
    if(state == 'OFF'):
        pi_gpio.set_led(led,False)
    elif (state == 'ON'):
        pi_gpio.set_led(led,True)
    else:
        return "Argument Error"

    return "Led State Command:" + state + " for LED number:"+ str(led) + "\n"
    # -----------------------------------------------------------------------------
# ============================== API Routes ===================================
```

#### Step C4: Test all of our API routes using CURL as indicated in comments.
```sh
# SW not pressed
host$ curl http://iot8e3c:5000/sw
=> Switch State:0!

# SW pressed
host$ curl http://iot8e3c:5000/sw
=> Switch State:1!

# LED GET requests
host$ curl http://iot8e3c:5000/leds/1
=> LED State:1

host$ curl http://iot8e3c:5000/leds/2
=> LED State:1

host$ curl http://iot8e3c:5000/leds/3
=> LED State:1

# Change the LED states to ON
host$ curl --data 'led=1&state=ON' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:1

host$ curl --data 'led=2&state=ON' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:2

host$ curl --data 'led=3&state=ON' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:3

# Change the LED states to OFF
host$ curl --data 'led=1&state=OFF' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:1

host$ curl --data 'led=2&state=OFF' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:2

host$ curl --data 'led=3&state=OFF' http://iot8e3c:5000/ledcmd
=> Led State Command:ON for LED number:3
```

[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part D - Lab2 HTML Webpage ###
**Objective:** Now that we have our webserver api and driver architectural
components built and tested it's time to create our IoT website for driving
and providing status for our sensor / actuator system. Remember that this
webpage ```index.html``` has some slight non-HTML properties provided by the
Flask framework for embedded python execution using index.html as a template
(in the templates folder) and embedded code going into ```{{  code }}```
sections of the HTML.

#### Step D1: Create a Flask Templates Folder
Flask has this nice capability to intereact with HTML by placing your HTML code
into a directory right off the *root* webpage app.
```
pi$ cd Labs/Lab2/webapp
pi$ mkdir templates
pi$ cd templates
pi$ touch index.html   # creates a blank index.html to be edited in Atom
```

#### Step D2: Start by creating the basic HTML *standard* structure
A good way to enter HTML code is to use CodePen (codepen.io).  After you have
opened a free account you should prototype your code in CodePen using their
WYSIWYG web page rendering and HTML tidy and syntax checking utilities.  Start
by entering the basic html document structure PLUS a scripting area including
the jQuery *minified* javascript library as shown in the URL.
```html
<!doctype html>
<html>

  <head>
    <title>UW IoT Lab2</title>
  </head>

  <body>

    <!-- ... our HTML goes here!! -->

    <script src="https://code.jquery.com/jquery-1.12.0.min.js"></script>

    <script>
      <!-- ... our custom JS jQuery scripting goes here!! -->
    </script>

  </body>
</html>
```
Select ```Tidy HTML``` and ```Analyze HTML``` to clean up indents and spaces as
well as checking the syntax of your HTML code.  Then select-all and copy the
entire page and paste into your Atom editor (mapped into the RPi).You can go 
back and forth from your CodePen and Atom to copy-paste updates into the 
index.html located in the ```templates``` directory.

#### Step D3: Add python embedded script status structure
The state of the switch and LEDs will be read each time the web page loads if
we can embed a bit of Python into the HTML <body> code using {{ code }} methods.
Prototype this all in CodePen initially (and don't forget to rename and save
your *pen*).

```html
<h2>UW IoT | Lab 2: GPIO API and WebApp</h2>
<h3>Switch: {{'On' if switch else 'Off'}}</h3>
<h4>RED LED (on GPIO18): {{'ON' if led1 else 'OFF'}}</h4>
<h4>GREEN LED (on GPIO13): {{'ON' if led2 else 'OFF'}}</h4>
<h4>BLUE LED (on GPIO23): {{'ON' if led3 else 'OFF'}}</h4>
```
Refresh the webpage when pressing and releasing the SWITCH to see if the webpage
variables update as we expect.  You might try a few CURLs to manually change the
LED state and perform a similar reload to see if the LED states are picked up.

#### Step D4: Add html buttons (one for each LED)
Each HTML button will toggle the state of the LED if we just add an *id* to the
button so that the jQuery script code (below) will "find" that button by name.
```html
<p>
  <button type='button' id='red_led_btn'>RED LED</button><br><br>
  <button type='button' id='grn_led_btn'>GREEN LED</button><br><br>
  <button type='button' id='blu_led_btn'>BLUE LED</button><br><br>
</p>
```
Let's also add a little style to the buttons to give them some color corresponding
to the LED they control. Add the following ```style``` attribute to each of the
buttons and then change the background color to the corresponding LED color.
```html
  <button style="width:100px; height:50px; color:white; background:red" ... >
  <button style= ... >
  <button style= ... >
```
OK!  Done with the main HTML body code.  That's it for now in this section.

[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part E - Javascript Click Events ###
**Objective:** Now that we have almost everyone working, we need to add some
relatively simple jQuery to intercept button click events and then call the
GPIO methods by way of HTTP API methods.  In the ```<script>``` section, add the
following design pattern for each of the LEDs.  Even if you don't know much or
any jQuery you can sort of logically determine that an HTML element given by
the particular ID corresponding to the LED color will fire a button event which
will get processed by the jQuery JS click event.

```html
  <script>
  // start executing only after document has loaded
  $(document).ready(function() {
    // establish global variables for LED status
    var led1;
    var led2;
    var led3;

    // The button click functions run asynchronously in the browser
    $('#red_led_btn').click(function() {
      if (led1 === "OFF") {led1 = "ON";} else {led1 = "OFF";}
      var params = 'led=1&state='+led1;
      console.log('Led Command with params:' + params);
      $.post('/ledcmd', params, function(data, status){
              console.log("Data: " + data + "\nStatus: " + status);
      });
    });

    // code the green and blue buttons the same
  });
  </script>
```
Complete the same design pattern for each of the buttons but changing the POST
API data parameter to correspond to the correct LED.  Note that we have code for
toggling the led1 variable each time the click occurs.

[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)

### Part F - Fine-tune Startup Conditions
**Problem:** It turns out that there is a slight disconnect in state when the
web page has been reloaded after manipulating the LEDs from the buttons.

**Objective:** Because Javascript functions are by nature asynchronous, we can't
necessarily control the order of those functions firing.  However we need some
predictable start up sequencing when the HTML page loads and starts running the
script section of the code.  

#### Step F1: Build a Javascript function sequence in CodePen
We will use the jQuery Deferred execution model with 'resolve' and 'promise'
methods to synchronize the execution.
```javascript
function firstFunction() {
  var d = $.Deferred();
  // some very time consuming asynchronous code...
  setTimeout(function() {
    console.log('1');
    d.resolve();
  }, 1000);
  return d.promise();
}

function thirdFunction() {
  var d = $.Deferred();
  setTimeout(function() {
    console.log('3');
    d.resolve();
  }, 1000);
  return d.promise();
}

function secondFunction() {
  var d = $.Deferred();
  setTimeout(function() {
    console.log('2');
    d.resolve();
  }, 1000);
  return d.promise();
}

function fourthFunction() {
  var d = $.Deferred();
  // last function, not executed until the other 3 are done.
  setTimeout(function() {
    console.log('4');
    d.resolve();
  }, 1000);
  return d.promise();
}

// sequence through the synchronous functions using '.then'
firstFunction().then(thirdFunction).then(secondFunction).then(fourthFunction);
```

#### Step F2: Code a similar startup sequence for LED state variables
```javascript
// Let's read the current LED state
function initial_conditions() {
  var d = $.Deferred();

  setTimeout(function() {
    $.get('/leds/1',function(data){
      led1 = $.trim(data.split(':')[1]);
    });

    $.get('/leds/2',function(data){
      led2 = $.trim(data.split(':')[1]);
    });

    $.get('/leds/3',function(data){
      led3 = $.trim(data.split(':')[1]);
    });

    // console.log("Got my data now!");
    d.resolve();
  }, 1);
  return d.done();
}

// Let's initialize our LED vars to the current LED state "ON"/"OFF"
function led_status() {
  var d = $.Deferred();

  setTimeout(function() {
    if (led1 === '0') {led1 =  "OFF"} else {led1 =  "ON"}
    if (led2 === '0') {led2 =  "OFF"} else {led2 =  "ON"}
    if (led3 === '0') {led3 =  "OFF"} else {led3 =  "ON"}
    d.resolve();

    console.log("RED:",led1);
    console.log("GRN:",led2);
    console.log("BLU:",led3);
  }, 200);
  return d.promise();
}

// make sure to intialize synchronously (10ms back to back)
initial_conditions().then(led_status);
```
**Great!** We now have a fully functional sensor/actuator monitoring and control
dashboard webapp.  In our upcoming lab we will make this a more dynamic dashboard
that will automatically update indications using "Server Sent Events".


[LAB2 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab2

### Objectives
For this lab we will continue building on our IoT webapp by adding basic GPIO
capability in a layered architectural manner.  We will build an object oriented
Python ```gpio.py``` driver as well as a unit test ```gpio_test.py``` for the
driver code.

We will also build a simple introduction to API design that provides a hands-on
approach to designing *HTTP get/post* methods within the Flask webserver
framework.

Next we'll build a simple ```index.html``` page that has three
buttons for toggling the LED states as well as an indicator for the state of
the switch.  This webpage will also have a small amount of Javascript (jQuery) to
handle pushbutton events.


The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartA.md) Design an object oriented Python GPIO driver and unit test.
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartB.md) Build a Flask webserver application that shows how to build HTTP GET/POST API.
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartC.md) Expand the API webserver design to interface to the GPIO module methods.
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartD.md) Build our GPIO IoT Webapp and show how to interface it as a template to Flask.
* [PART E](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartE.md) Code each of the Javascript events that need handling from button clicks
* [PART F](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab2/PartF.md) Fine tune the Javascript logic to handle startup conditions
[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)

### Part A - Add Twitter Bootstrap Framework ###
**Synopsis:** A good website design provides for *separation of concerns*.  This
means that the HTML is generally separated from the CSS which is separated from
the JavaScript in so much as the code it placed in separate files and folders.

#### Step A1: Create Expanded Web File Structure
**Objective:** Flask provides for a traditional web site layout, where content (HTML)
is separated from presentation (CSS) and action (JavaScript) by placing each of
these files in their own separate folders. In addition to the ```templates```
folder we need to add a ```static``` folder and then add a ```css``` and ```js```
folder under the static *assets* folder.

```sh
pi$ cd ; cd Documents/GIT_REPOS/iot110/Labs
pi$ mkdir Lab3 ; cd Lab3
pi$ mkdir -p webapp/templates ; mkdir -p webapp/static/css ; mkdir -p webapp/static/js
pi$ cd webapp/static/css ; touch lab3.css
pi$ cd ../js ; touch lab3.js
```

#### Step A2: Download bootstrap and jQuery
**Objective:** We want to install the Bootstrap UI and components and put them
in our static assets folder. Use the links below to download the latest version
of Bootstrap and jQuery and then we will copy a few select files into the file
structure we created above.

[Download Bootstrap](http://getbootstrap.com/getting-started/#download)

The following is the jQuery site, but we will directly download using wget below:
[Download jQuery](http://jquery.com/download)

```sh
pi$ wget https://code.jquery.com/jquery-3.1.1.min.js
```
Now, let's grab two files from the Bootstrap download folder.  At the time of
this lesson it was /Downloads/bootstrap-3.3.7-dist/ (or wherever your Downloads
  folder happens to reside).

**Note:** The code below is copying from the HOST downloads folder thru the mount
point to the RPi's GIT repo mounted folder.  (Adjust this for  your unique
mount point situation)
```sh
host$ cd Downloads/bootstrap-3.3.7-dist
host$ cp css/bootstrap.min.css ~/PI_MOUNT_8e3c/iot110/Labs/Lab3/webapp/static/css/
host$ cp js/bootstrap.min.js ~/PI_MOUNT_8e3c/iot110/Labs/Lab3/webapp/static/js/

# Note: just as a reminder (MacOSX) the command for mounting your PI is
host$ sshfs pi@iot1234:Documents/GIT_REPOS PI_MOUNT_1234/ -C
```
#### Step A3:  
We will need to adjust the ```index.html``` meta and script sections to account
for our organization of the *web assets*.  Modify the HEAD section of the HTML
to make this change according to the Flask provisions for static assets.
```html
<head>
  <meta charset="utf-8">
    <title>UW IoT Lab3</title>
    <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/bootstrap.min.css') }}">
    <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/lab3.css') }}">
    <script src="{{ url_for('static',filename='js/jquery-3.1.1.min.js') }}"></script>
    <script src="{{ url_for('static',filename='js/bootstrap.min.js') }}"></script>
  </head>
```

OK, were done with the organization of our assets and prepared for styling with
Bootstrap components and actions.  Next we will move on to adding dynamic Server
Sent Events capability to our code.

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartB.md) Add additional
capbility to main.py for *Server Sent Events*.

[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)
[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)

### Part B - Adding SSE to the Webserver Code (main.py) ###
**Synopsis:** Flask has provisions built in to allow for streaming of data
from the server to clients.  We want to use that streaming capability to request
data from our GPIO driver and then send it through what Flask calls a ```Response```
mechanism.

#### Step B1: Timer
**Objective:** We will need to have a continuously running thread that updates
every half a second and sends updated state information on this endpoint.  
Therefore we will need to add the time library.  In addition we will use the
same library imports from the original web server implementation for GPIO.
```python
import time
from gpio import PiGpio
from debouncer import Debouncer
from flask import *

app = Flask(__name__)
pi_gpio = PiGpio()
db = Debouncer()
```

#### Step B2: SSE Endpoint
Next we need to add the routing endpoint code to read the switch status as well
as LEDs.  This endpoint will read the status of the switch, the 3 LEDs and then
build a data payload ```data: 0 1 0 1``` that will *yield* to the Flask Response
to communicate these data back to the web client. We will call this the myData
endpoint.  

```python
# =========================== Endpoint: /myData ===============================
# read the gpio states by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_state_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            raw_switch = pi_gpio.read_switch()
            debounced_switch = str(db.debounce(raw_switch))
            led_red = str(pi_gpio.get_led(1))
            led_grn = str(pi_gpio.get_led(2))
            led_blu = str(pi_gpio.get_led(3))
            yield('data: {0} {1} {2} {3}\n\n'.format(debounced_switch,led_red,led_grn,led_blu))
            time.sleep(0.1)
    return Response(get_state_values(), mimetype='text/event-stream')
```

#### Step B3: SSE Client-side Subscriber
Now that we have a routing endpoint that creates an EventSource feed, we need a
client-side receiver of that data by matching up the method name with the
subscriber to that EventSource.  Below is a snippet of JavaScript that needs to
be at the bottom of index.html in order for it to receive data payloads.  We run
a simple test of this by logging output to the console.

```html
<script type="text/javascript">
  var switchSource = new EventSource("{{ url_for('myData') }}");
  switchSource.onmessage = function(e) {
    console.log(e.data);
  }
</script>
```

#### Step B4: Added Threaded Execution
Finally, because we want this thread to run independently from the other API
calls to this code, we need to simply tell the app.run method to ensure threaded
execution is enabled.  **Make sure this code is at the bottom of main.py**.

```python
if __name__ == "__main__":
    app.run(host='0.0.0.0', debug=True, threaded=True)
```

#### Step B5: Possible Errors with Threading
Whenever multiple threads are set up to run there's always the possibility that
the operating system will still be running that thread after killing the main
program.  For now, we will just manually kill these extra orphan threads by using
the Linux shell commands to list processes, obtain a process number and then to
kill off that extra process thread.  The symptom of this will be when you try to
run the main program again and then receive a *Traceback exception*.

Example:
```sh
pi$ python main.py
Traceback (most recent call last):
  File "main.py", line 82, in <module>
   ...
   socket.error: [Errno 98] Address already in use
```

To fix this we need to kill (using minus 9 for strong kill!) the orphan process.
```sh
pi$ ps aux | grep python
=> pi        3785  1.0  1.7  74788 16244 pts/0    Sl   18:15   0:04 /usr/bin/python main.py
=> pi        3900  0.0  0.2   4280  1908 pts/0    S+   18:22   0:00 grep --color=auto pytho
pi$ kill -9 3785

pi$ ps aux | grep python
=> pi        3902  0.0  0.1   4276  1876 pts/0    S+   18:22   0:00 grep --color=auto pytho
```

#### Step B6: Test from Chrome
Run through all of the states of the GPIO functionality by pulling up the
web developer console and observing the ```data: 0 1 0 1``` output that was
created from the console output above.

Now we are ready to start splitting off style and operations into their own
files also utilizing Bootstrap assets.

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartC.md) Organize and Code Web Assets.

[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)
[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)

### Part C - Organize and Code Web Assets. ###
**Synopsis:** Before we finish up on the web JavaScript client side code and
styling via CSS, we want to better organize our assets by moving the scripts
into a separate file called ```js/lab3.js```.  We also want to create a style sheet
for this lab called ```css/lab3.css```.  The files go into their respective
folders under the ```static``` folder.

#### Step C1: Flask Parameter Passing w/o SSE
**Objective:** Flask uses a template engine called
[Jinja2](http://jinja.pocoo.org).  This framework is used to pass variables and
execute script code within HTML as it renders within a web browser.  
In our lab ```main.py``` web server the index.html is rendered on the default
path in the following code snippet.  The index() method is called when the web
page reloads on the default path ("/"). The default path is executed whenever a
CURL is executed (e.g. iot1234:5000) or when you type your host address into a
web browser URL address line (e.g. URL=>iot1234:5000). In our original main.py, in
the execution of index(), the GPIO driver is instantiated and the initial state 
of the led and switch variables are read and passed as arguments to 
the ```render_template()``` function.

```python
@app.route("/")
def index():
    # create an instance of my pi gpio object class.
    pi_gpio = PiGpio()
    switch_state = pi_gpio.read_switch()
    led1_state = pi_gpio.get_led(1)
    led2_state = pi_gpio.get_led(2)
    led3_state = pi_gpio.get_led(3)
    return render_template('index.html', switch=switch_state,
                                led1=led1_state,
                                led2=led2_state,
                                led3=led3_state)
```

#### Step C2: Flask Parameter Passing with SSE
In our new *Server Sent Event* implementation for this lab, we will push all of
this state information from the server by continuously reading the state. We will 
have a different mechanism for communicating and rendering the state to our web 
page using JavaScript.  This will simplify the index.html rendering code as 
follows:
```html
@app.route("/")
def index():
    return render_template('index.html')
```

#### Step C3: Adding the Client JavaScript Code to connect to SSE
In Part B we added an SSE data publishing endpoint to ```main.py``` and a simple
console.log() debug output of the client side subscription to this endpoint.  
Now we need that JavaScript, at the bottom of the index.html code, to change the
HTML code dynamically to reflect the state of the GPIO pins.  We start by
ensuring we have state variables for the leds that will be retained.  We read
and parse the incoming data and then call respective functions to update the
switch and leds on the HTML webpage.  These updates are accomplished using 
jQuery methods.  (e.g. the $().method capability we added in Part A).

```python
      /* start executing only after document has loaded */
      $(document).ready(function() {
        /* establish global variables for LED status */
        var led1;
        var led2;
        var led3;

 		/* var iotSource = new EventSource("{{ url_for('myData') }}"); */
        /* intercept the incoming states from SSE */
        iotSource.onmessage = function(e) {
          var params = e.data.split(' ');
          updateSwitch(params[0]);
          updateLeds(1,params[1]);
          updateLeds(2,params[2]);
          updateLeds(3,params[3]);
        }

        /* update the Switch based on its SSE state monitor */
        function updateSwitch(switchValue) {
          if (switchValue === '1') {
            $('#switch').text('ON');
          } else if (switchValue === '0') {
            $('#switch').text('OFF');
          }
        }

        /* update the LEDs based on their SSE state monitor */
        function updateLeds(ledNum,ledValue) {
          if (ledNum === 1) {
            if (ledValue === '1') {
              $('#red_led_label').text('ON');
              led1 = "ON"
            } else if (ledValue === '0') {
              $('#red_led_label').text('OFF');
              led1 = "OFF"
            }
          }
          else if (ledNum === 2) {
            if (ledValue === '1') {
              $('#grn_led_label').text('ON');
              led2 = "ON"
            } else if (ledValue === '0') {
              $('#grn_led_label').text('OFF');
              led2 = "OFF"
            }
          }
          else if (ledNum === 3) {
            if (ledValue === '1') {
              $('#blu_led_label').text('ON');
              led3 = "ON"
            } else if (ledValue === '0') {
              $('#blu_led_label').text('OFF');
              led3 = "OFF"
            }
          }
        }
```

At this point we have a fully functional page, but perhaps not a very 
esthetically pleasing dashboard.  In the next part we will fix that with the
Twitter Bootstrap framework we prepared in Part A.

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartD.md) Add Bootstrap UI Elements and CSS Styles.

[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)
[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)


### Part D - Add Bootstrap UI Elements and CSS Styles. ###
**Synopsis:** Adding Bootstrap.  We will add the following modifications to our
main index.html file to be compatible with Bootstrap UI.  

```html
<body>
  <div class="container panel">
    <div class="container well well-sm">
      <h3 id='title'>Lab 3 GPIO Server Sent Events</h3>
    </div>

    <div class="container well">
      <div class="row">
        <div class="col-sm-2"></div>
        <div class="col-sm-3">
          <h4 class="gpio">Switch</h4>
        </div>
        <div class="col-sm-3 switch">
          <h4><span id="switch" class="label label-default">&#9759</span></h4>
        </div>
        <div class="col-sm-2">
          <h4 class="gpio">[GPIO27]</h4></div>
        <div class="col-sm-2"></div>
      </div>

      <!-- LED: RED -->
      <div class="row">
        <div class="col-sm-2"></div>

        <div class="col-sm-3 led_button">
          <button type='button' id="red_led_btn" class="btn btn-md btn-default">Toggle LED</button>
        </div>
        <div class="col-sm-3 led_label">
          <h4><span id="red_led_label" class="label label-default">&#9728</span></span></h4>
        </div>
        <div class="col-sm-2">
          <h4 class="gpio">[GPIO18]</h4></div>
        <div class="col-sm-2"></div>
      </div>
      <!-- LED: GREEN -->
      <div class="row">
        <div class="col-sm-2"></div>

        <div class="col-sm-3 led_button">
          <button type='button' id="grn_led_btn" class="btn btn-md btn-default">Toggle LED</button>
        </div>
        <div class="col-sm-3 led_label">
          <h4><span id="grn_led_label" class="label label-default">&#9728</span></h4>
        </div>
        <div class="col-sm-2">
          <h4 class="gpio">[GPIO13]</h4></div>
        <div class="col-sm-2"></div>
      </div>
      <!-- LED: BLUE -->
      <div class="row">
        <div class="col-sm-2"></div>
        <div class="col-sm-3 led_button">
          <button type='button' id="blu_led_btn" class="btn btn-md btn-default">Toggle LED</button>
        </div>
        <div class="col-sm-3 led_label">
          <h4><span id="blu_led_label" class="label label-default">&#9728</span></h4>
        </div>
        <div class="col-sm-2">
          <h4 class="gpio">[GPIO23]</h4></div>
        <div class="col-sm-2"></div>
      </div>
    </div>
  </div>

  <script type="text/javascript">
    var iotSource = new EventSource("{{ url_for('myData') }}");
    // intercept the incoming states from SSE
  </script>
</body>
```

Now, we will add our Cascading Style Sheet styling to our site.  

```css
body {
  background-color: rgb(51, 0, 111);
  width: 800px;
  margin:5px auto;
}

span.label  {
    font-size: 1.3em;
}

.btn {
  font-size: 1.2em;
}

button {
  margin: 5 auto;
}

h4.gpio {
  margin:13 auto;
}
.well {
  width: 100%;
}

.well-sm {
  margin: 10px auto;
}

.panel {
  background-color: darkgray;
  width: 75%;
  text-align: center;
}
```

[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)
[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)


### Part E - Digital Debouncer. ###
**Synopsis:** In this section we will be adding a digital switch debouncer.

### Part E1 - Digital Debounce Module ###
**Objective:** We would like to have a digital debounce stand along class that
we can call from our server SSE section that is constantly sampling the switch
input.  Create a new file called ```debouncer.py```.  In this file we will
implement a digital shift register to debounce a stream of incoming raw switch
states.  We'll only make this a 4 bit shift register since the switch sampling
rate will be 100ms.

```python
SHIFT_MASK = 15
class Debouncer(object):
    """Shift Register Debouncer"""

    def __init__(self):
        self.switch_shift_register = 0

    # perform AND logic debouncer
    def debounce(self, switch_in):
        self.switch_shift_register = (self.switch_shift_register << 1) | switch_in
        return int((self.switch_shift_register & SHIFT_MASK) == SHIFT_MASK)
```

### Part E2 - Digital Debounce Unit Test ###
**Objective:** Let's create a unit test before we just embedded our new Module
into our web server.  It will be called ```debouncer_test.py```.  In this file
we will sample the raw switch state and pass it to the debouncer.  We'll use the
LEDs to show both the state of the raw and debounced output.
```python
#!/usr/bin/python
import time
from debouncer import Debouncer
from gpio import PiGpio

# create an instance of the pi gpio driver.
pi_gpio= PiGpio()
# create an instance of the switch debouncer
db = Debouncer()
#
print('Debounce my Input Switch (Ctrl-C to stop)...')
while True:
    switch_raw = pi_gpio.read_switch()
    switch_debounced = db.debounce(switch_raw)
    pi_gpio.set_led(1,(switch_raw == 1))
    pi_gpio.set_led(2,(switch_debounced == 1))

    print('SW RAW: {0} SW DEBOUNCED: {1}'.format(switch_raw , switch_debounced))
    time.sleep(0.2)
```

OK, now that our debouncer is working, we can implement it in the web server.

[LAB3 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab3

### Objectives
For this lab we will continue building on our IoT webapp by adding *Advanced*
GPIO capability to get us started using *Server Sent Events* in Python/Flask.  We
will also spruce up our web page a bit using the Twitter *bootstrap* web
framework and the adjust the size and spacing to fit on the RPI just in case
you want to see it stand alone on the RPi's smaller own web browser screen.

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartA.md) Add Twitter Bootstrap Framework.
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartB.md) Add additional
capbility to main.py for *Server Sent Events*.
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartC.md) Organize and Code Web Assets.
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartD.md) Add Bootstrap UI Elements and CSS Styles.
* [PART E](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab3/PartE.md) Digital Debounce.

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)

## Part A
**Synopsis:** We need to ensure that the I2C serial bus capability is enabled and
functional with its connection to the BMP280 pressure/temperature sensor.  We
will enable the I2C from RPi settings and then install some ```i2c-tools``` to scan
all of the I2C addresses for the presence of the BMP280.   From the BMP280
datasheet we know that the I2C bus address is either 0x76 (SDO grounded) or 0x77
(SDO connected high or left floating).  This will show up and be apparent using
the ```i2cdetect``` utility.

## Objectives
* Enabling I2C Bus Capability on RPI
* Wire the BMP280 into the breadboard
* Test to ensure proper connectivity

*Note:* We'd like to thank **Matt Hawkins** for his excellent tutorial on using Python
for many sensor devices on RPI and his example code for the BME280 (similar device to the BMP280).

[Python Driver BME280](http://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/)<br />
[Enable I2C Interface](http://www.raspberrypi-spy.co.uk/2014/11/enabling-the-i2c-interface-on-the-raspberry-pi/)<br />
[BMP280 Datasheet](https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf)<br />

## Enabling I2C Bus Capability on RPI

### Step A1: Enable i2c using raspi-config utility
```
pi$ sudo raspi-config
```
Now complete the following steps :

* Select â€œAdvanced Optionsâ€
* Select â€œI2Câ€

The screen will ask if you want the ARM I2C interface to be enabled :

* Select â€œYesâ€
* Select â€œOkâ€ (Enable I2C)
* Select â€œOkâ€ (Install Kernel Modules)
* Select â€œFinishâ€ to return to the command line.
* Select Reboot

### Step A2: Enable i2c using RPi Preferences Panel
Go to Menu > Preferences > Raspberry Pi Configuration and select the Intefaces Tab
<img src="https://gitlab.com/iot110/iot110-student/raw/master/Labs/Lab4/images/I2C_800x480.png" alt="I2C Enable">

### Step A3: â€“ Install I2C Utilities

```
pi$ sudo apt-get update
pi$ sudo apt-get install -y python-smbus i2c-tools
```

### Step A4: Reboot and Test I2C
```
pi$ sudo reboot   
  => wait until rebooted
pi$ lsmod | grep i2c_
i2c_bcm2708             4834  0
i2c_dev                 5859  0
```
That will list all the modules starting with â€œi2c_â€. If it lists â€œi2c_bcm2708â€ then the module is running correctly.

### Step A5: Wire the BMP280 on the Breadboard
The following breadboard configuration will be used to test the BMP280.  Please
add the BMP280 module and connect as showing below.
![Lab4 Breadboard](https://gitlab.com/iot110/iot110-student/raw/master/Labs/Lab4/images/Lab4-Breadboard.png)

### Step A6: Test the I2C Address
Open the [BMP280 Datasheet](https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf) and browse to section **5.2 IÂ²C Interface**<br />

The **IÂ²C interface** uses the following pins:
* SCK: serial clock (SCL)
* SDI: data (SDA)
* SDO: Slave address LSB (GND = â€˜0â€™, VDDIO = â€˜1â€™)

"...The 7-bit device address is 111011x. The 6 MSB bits are fixed. The last bit is changeable by
SDO value and can be changed during operation. Connecting SDO to GND results in slave
address 1110110 (**0x76**); connection it to VDDIO results in slave address 1110111 (**0x77**), which is the same as BMP180â€™s IÂ²C address. The SDO pin cannot be left floating; if left floating, the
IÂ²C address will be undefined."

**Connect SDO to 10K PU**
```
pi$ sudo i2cdetect -y 1
     0  1  2  3  4  5  6  7  8  9  a  b  c  d  e  f
00:          -- -- -- -- -- -- -- -- -- -- -- -- --
10: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
20: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
30: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
40: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
50: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
60: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
70: -- -- -- -- -- -- 77 --
```

**Connect SDO to GND**

```
pi$ sudo i2cdetect -y 1
     0  1  2  3  4  5  6  7  8  9  a  b  c  d  e  f
00:          -- -- -- -- -- -- -- -- -- -- -- -- --
10: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
20: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
30: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
40: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
50: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
60: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
70: -- -- -- -- -- -- 76 --
```

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartB.md) Create BMP280 Driver

[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)
[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)

## BMP280 Driver Development

## Objectives
* Adapt low level driver for bmp280 (from Matt Hawkins' site)

*Note:* We'd like to thank **Matt Hawkins** for his excellent tutorial on using Python
for many sensor devices on RPI and his example code for the BME280 (similar device to the BMP280).

### Step B1 â€“ Imports and the Python SHEBANG
```python
#!/usr/bin/python
# =============================================================================
#        File : bmp280.py
# Description : Read data from the Bosch digital pressure sensor.
#      Author : S. Dame (Adapted from Matt Hawkins' code)
#        Date : 12/21/2016
# =============================================================================
#
#  Official datasheet available from :
#  https://www.bosch-sensortec.com/bst/products/all_products/bme280
#
# Matt Hawkin's site --> http://www.raspberrypi-spy.co.uk/
# =============================================================================
import smbus    # System Management Bus
import time     # time utilities

```

### Step B2 â€“ FFI Interface to some C types needed for byte manipulation
```python
# =============================================================================
# ctypes is an advanced ffi (Foreign Function Interface) package for Python
# that provides  call functions in dlls/shared libraries and has extensive
# facilities to create, access and manipulate simple and complicated
# C data types in Python
# =============================================================================
from ctypes import c_short
from ctypes import c_byte
from ctypes import c_ubyte
# =============================================================================
```

### Step B3 â€“ Collection of Utility Functions
```python
def getShort(data, index):
  # return two bytes from data as a signed 16-bit value
  return c_short((data[index+1] << 8) + data[index]).value

def getUShort(data, index):
  # return two bytes from data as an unsigned 16-bit value
  return (data[index+1] << 8) + data[index]

def getChar(data,index):
  # return one byte from data as a signed char
  result = data[index]
  if result > 127:
    result -= 256
  return result

def getUChar(data,index):
  # return one byte from data as an unsigned char
  result =  data[index] & 0xFF
  return result
```

### Step B4 â€“ Sensor Object Constructor and read ID Method
```python
# =============================================================================
# create a sensor object
# -----------------------------------------------------------------------------
class PiBMP280(object):
    """Raspberry Pi 'IoT BMP280 Sensor'."""

    # addr = I2C Chip Address
    def __init__(self,addr=DEVICE):
        self.bus = smbus.SMBus(1)   # Rev 2 Pi, Pi 2 & Pi 3 uses bus 1
                                    # Rev 1 Pi uses bus 0
        self.addr = addr            # register the address with the object

    def readBMP280ID(self):
      REG_ID     = 0xD0
      (chip_id, chip_version) = self.bus.read_i2c_block_data(self.addr, REG_ID, 2)
      return (chip_id, chip_version)
```

### Step B5.1 â€“ Read Pressure/Temperature Method (setup)
```python
    def readBMP280All(self, addr=DEVICE):
      # Register Addresses
      REG_DATA = 0xF7
      REG_CONTROL = 0xF4
      REG_CONFIG  = 0xF5

      # Oversample setting - page 27
      OVERSAMPLE_TEMP = 2
      OVERSAMPLE_PRES = 2
      MODE = 1
      
      # write oversample configuration and mode
      control = OVERSAMPLE_TEMP<<5 | OVERSAMPLE_PRES<<2 | MODE
      self.bus.write_byte_data(self.addr, REG_CONTROL, control)

      # Read blocks of calibration data from EEPROM
      # See Page 22 data sheet
      cal1 = self.bus.read_i2c_block_data(self.addr, 0x88, 24)
      cal2 = self.bus.read_i2c_block_data(self.addr, 0xA1, 1)
      cal3 = self.bus.read_i2c_block_data(self.addr, 0xE1, 7)
      
      # ... continued ...
```

### Step B5.2 â€“ Set up T and P Compensation values
```python
      # Convert byte data to word values
      dig_T1 = getUShort(cal1, 0)
      dig_T2 = getShort(cal1, 2)
      dig_T3 = getShort(cal1, 4)

      dig_P1 = getUShort(cal1, 6)
      dig_P2 = getShort(cal1, 8)
      dig_P3 = getShort(cal1, 10)
      dig_P4 = getShort(cal1, 12)
      dig_P5 = getShort(cal1, 14)
      dig_P6 = getShort(cal1, 16)
      dig_P7 = getShort(cal1, 18)
      dig_P8 = getShort(cal1, 20)
      dig_P9 = getShort(cal1, 22)

      dig_H1 = getUChar(cal2, 0)
      dig_H2 = getShort(cal3, 0)
      dig_H3 = getUChar(cal3, 2)

      dig_H4 = getChar(cal3, 3)
      dig_H4 = (dig_H4 << 24) >> 20
      dig_H4 = dig_H4 | (getChar(cal3, 4) & 0x0F)

      dig_H5 = getChar(cal3, 5)
      dig_H5 = (dig_H5 << 24) >> 20
      dig_H5 = dig_H5 | (getUChar(cal3, 4) >> 4 & 0x0F)

      dig_H6 = getChar(cal3, 6)

      # ... continued ...      
```

### Step B5.3 â€“ Read Temperature and Pressure Raw Values
```python
      # Read temperature & pressure
      data = self.bus.read_i2c_block_data(self.addr, REG_DATA, 6)
      pres_raw = (data[0] << 12) | (data[1] << 4) | (data[2] >> 4)
      temp_raw = (data[3] << 12) | (data[4] << 4) | (data[5] >> 4)
      # ... continued ...      
```

### Step B5.4 â€“ Perform Compensation and calc values in degrees C and hPa Units
```python
      # Refine temperature based on calibration per spec
      var1 = ((((temp_raw>>3)-(dig_T1<<1)))*(dig_T2)) >> 11
      var2 = (((((temp_raw>>4) - (dig_T1)) * ((temp_raw>>4) - (dig_T1))) >> 12) * (dig_T3)) >> 14
      t_fine = var1+var2
      temperature = float(((t_fine * 5) + 128) >> 8);

      # Refine pressure and adjust for temperature
      var1 = t_fine / 2.0 - 64000.0
      var2 = var1 * var1 * dig_P6 / 32768.0
      var2 = var2 + var1 * dig_P5 * 2.0
      var2 = var2 / 4.0 + dig_P4 * 65536.0
      var1 = (dig_P3 * var1 * var1 / 524288.0 + dig_P2 * var1) / 524288.0
      var1 = (1.0 + var1 / 32768.0) * dig_P1
      if var1 == 0:
        pressure=0
      else:
        pressure = 1048576.0 - pres_raw
        pressure = ((pressure - var2 / 4096.0) * 6250.0) / var1
        var1 = dig_P9 * pressure * pressure / 2147483648.0
        var2 = pressure * dig_P8 / 32768.0
        pressure = pressure + (var1 + var2 + dig_P7) / 16.0

      return temperature/100.0,pressure/100.0
# -----------------------------------------------------------------------------      
# =============================================================================
```

### Step B5.4 â€“ Add a default CLI main function to bmp280.py
```python
# =============================================================================
# main to test from CLI
def main():

    # create an instance of my pi bmp280 sensor object
    pi_bmp280 = PiBMP280()

    # Read the Sensor ID.
    (chip_id, chip_version) = pi_bmp280.readBMP280ID()
    print "    Chip ID :", chip_id
    print "    Version :", chip_version

    # Read the Sensor Temp/Pressure values.
    (temperature, pressure) = pi_bmp280.readBMP280All()
    print "Temperature :", temperature, "C"
    print "   Pressure :", pressure, "hPa"

if __name__=="__main__":
   main()
```
[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartC.md) Create BMP280 Unit Test

[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)
[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)

## Setting up BMP280 Unit Test

## Objectives
* Create unit test for checking out Methods of BMP280
* Create unit test for abstract methods of multiple BMP280 sensors.

### Step C1 â€“ imports
```python
import pprint
from bmp280 import PiBMP280

```


### Step C2 â€“ Array of BMP280 Sensor Parameters
```python
# create an array of my pi bmp280 sensor dictionaries
sensor = []
sensor.append({'name' : 'bmp280', 'addr' : 0x76, 'chip' : PiBMP280(0x76) , 'data' : {}})

```


### Step C3 â€“ Get Sensor ID Populated
```python
# Read the Sensor ID for 0x76 -> values into the ['data'] dictionary
(chip_id, chip_version) = sensor[0]['chip'].readBMP280ID()
sensor[0]['data']['chip_id'] = chip_id
sensor[0]['data']['chip_version'] = chip_version
```

### Step C1 â€“ Get the Sensor Data and print the Object
```python
print "  ============================== SENSOR   =============================="
print "  Chip ADDR :", hex(sensor[0]['addr'])
print "    Chip ID :", sensor[0]['data']['chip_id']
print "    Version :", sensor[0]['data']['chip_version']

# Read the Sensor Temp/Pressure values into the ['data'] dictionary
(temperature, pressure) = sensor[0]['chip'].readBMP280All()
sensor[0]['data']['temperature'] = { 'reading': temperature, 'units' : 'C' }
sensor[0]['data']['pressure'] = { 'reading': pressure, 'units' : 'hPa' }

print "Temperature :", sensor[0]['data']['temperature']['reading'], "C"
print "   Pressure :", sensor[0]['data']['pressure']['reading'] , "hPa"

pprint.pprint(sensor[0])
print "  ======================================================================"

```

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartD.md) Test Everything

[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)
[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)

## Perform BMP280 Unit Tests

## Objectives
* Run unit test for ```bmp280.py``` stand alone
* Run unit test for abstract test methods of multiple BMP280 sensors.

### Step D1 â€“ set up Unit Tests for them to become executables
```sh
pi$ chmod +x bmp280.py
pi$ chmod +x bmp280_test.py
pi$ chmod +x bmp280_test2.py
```
### Step D2 â€“ Test the methods in bmp280.py
```sh
pi$ ./bmp280.py
    Chip ID : 88
    Version : 1
Temperature : 23.61 C
   Pressure : 1009.74418394 hPa
```

### Step D3 â€“ One sensor test in bmp280_test.py
```sh
pi$ ./bmp280_test.py
============================== SENSOR 1 ==============================
Chip ADDR : 0x76
  Chip ID : 88
  Version : 1
Temperature : 23.61 C
 Pressure : 1009.71752441 hPa
{'addr': 118,
'chip': <bmp280.PiBMP280 object at 0x76a887b0>,
'data': {'chip_id': 88,
        'chip_version': 1,
        'pressure': {'reading': 1009.7175244112908, 'units': 'hPa'},
        'temperature': {'reading': 23.61, 'units': 'C'}},
'name': 'bmp280'}
======================================================================
```

### Step D4 â€“ Two sensor test in bmp280_test2.py
```sh
============================== SENSOR 1 ==============================
Chip ADDR : 0x76
  Chip ID : 88
  Version : 1
Temperature : 23.61 C
 Pressure : 1009.71752441 hPa
{'addr': 118,
'chip': <bmp280.PiBMP280 object at 0x76a887b0>,
'data': {'chip_id': 88,
        'chip_version': 1,
        'pressure': {'reading': 1009.7175244112908, 'units': 'hPa'},
        'temperature': {'reading': 23.61, 'units': 'C'}},
'name': 'bmp280'}
============================== SENSOR 2 ==============================
Chip ADDR : 0x77
  Chip ID : 88
  Version : 1
Temperature : 23.59 C
 Pressure : 1009.7345 hPa
{'addr': 118,
'chip': <bmp280.PiBMP280 object at 0x76a887b0>,
'data': {'chip_id': 88,
        'chip_version': 1,
        'pressure': {'reading': 1009.7345, 'units': 'hPa'},
        'temperature': {'reading': 23.59, 'units': 'C'}},
'name': 'bmp280'}
======================================================================
```

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartC.md) Back to Part C

[LAB4 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab4

### Objectives
For this lab we will continue building on our IoT suite by adding our first
active sensor device.  We will be adding the *Bosch BMP280* Pressure/Temperature
sensor and interfacing to it using the I2C serial protocol standardized by
Philips (NXP) Semiconductor.  

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartA.md) Enable I2C Bus and Test Connection to BMP280
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartB.md) Create BMP280 Python Driver
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartC.md) Create BMP280 Python Driver Unit Test
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab4/PartD.md) Test Everything

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)

## Part A - Create a Sensor Data Object
**Synopsis:** We need to enhance our ```main.py``` to blend in the capability
we developed in Lab4 unit tests to gather data from our sensor device 

## Objectives
* Merge code from Lab3 and Lab4
* Rename lab3.css and lab3.js
* Add Python Data Object to main.py for our BMP280 Sensor
* Add a console test in lab5.js

### Step A1: Copy Select Files from Lab3 and Lab4
```sh
pi$ cd ~/Documents/GIT_REPOS/iot110/Labs
pi$ cp -r Lab3/ Lab5/
pi$ cp Lab4/bmp280.py Lab5/webapp/
pi$ cd Lab5/webapp/
```

### Step A2: Test to ensure BMP280 and bmp280.py are working
```sh
$ ./bmp280.py 
    Chip ID : 88
    Version : 1
Temperature : 25.21 C
   Pressure : 1018.92606166 hPa
```

### Step A3: Modify main.py to add Python Sensor Object for BMP280.py
Import the bmp280 module
```python
#!/usr/bin/python
import time
from gpio import PiGpio
from bmp280 import PiBMP280
from debouncer import Debouncer
from flask import *
```

Create GPIO, Debounce and Sensor Objects
```python
# create GPIO Object and Switch Debouncer
pi_gpio = PiGpio()
db = Debouncer()
# create an array of my pi bmp280 sensor dictionaries
sensor = {"name" : "bmp280", "addr" : 0x76, "chip" : PiBMP280(0x76) , "data" : {}}
(chip_id, chip_version) = sensor["chip"].readBMP280ID()
sensor["data"]["chip_id"] = chip_id
sensor["data"]["chip_version"] = chip_version
```

Create a function to get only the temperature and pressure sensor values.
```python
# ============================== Functions ====================================
def get_sensor_values():
    (temperature, pressure) = sensor["chip"].readBMP280All()
    sensor["data"]["temperature"] = { "reading": temperature, "units" : "C" }
    sensor["data"]["pressure"] = { "reading": pressure, "units" : "hPa" }
    return sensor["data"]
```

All API methods for GPIO and LEDs remain unchanged
```python
# ============================== API Routes ===================================
app = Flask(__name__)

@app.route("/")
def index():
    return render_template('index_bs.html')
    # create an instance of my pi gpio object class.
    # pi_gpio = PiGpio()
    # switch_state = pi_gpio.read_switch()
    # led1_state = pi_gpio.get_led(1)
    # led2_state = pi_gpio.get_led(2)
    # led3_state = pi_gpio.get_led(3)
    # return render_template('index.html', switch=switch_state,
    #                             led1=led1_state,
    #                             led2=led2_state,
    #                             led3=led3_state)
# ============================ GET: /leds/<state> =============================
# read the LED status by GET method from curl for example
# curl http://iot8e3c:5000/leds/1
# curl http://iot8e3c:5000/leds/2
# curl http://iot8e3c:5000/leds/3
# -----------------------------------------------------------------------------
@app.route("/leds/<int:led_state>", methods=['GET'])
def leds(led_state):
  return "LED State:" + str(pi_gpio.get_led(led_state)) + "\n"


# =============================== GET: /sw ====================================
# read the switch input by GET method from curl for example
# curl http://iot8e3c:5000/switch
# -----------------------------------------------------------------------------
@app.route("/sw", methods=['GET'])
def sw():
  return "Switch State:" + str(pi_gpio.read_switch()) + "!\n"

# ======================= POST: /ledcmd/<data> =========================
# set the LED state by POST method from curl. For example:
# curl --data 'led=1&state=ON' http://iot8e3c:5000/ledcmd
# -----------------------------------------------------------------------------
@app.route("/ledcmd", methods=['POST'])
def ledcommand():
    cmd_data = request.data
    print "LED Command:" + cmd_data
    led = int(str(request.form['led']))
    state = str(request.form['state'])
    if(state == 'OFF'):
        pi_gpio.set_led(led,False)
    elif (state == 'ON'):
        pi_gpio.set_led(led,True)
    else:
        return "Argument Error"

    return "Led State Command:" + state + " for LED number:"+ str(led) + "\n"
# -----------------------------------------------------------------------------
```

### Step A4: Refactor the data yield route for the SSE to send the Sensor Object
```python
# =========================== Endpoint: /myData ===============================
# read the gpio states by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_state_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            raw_switch = pi_gpio.read_switch()
            debounced_switch = str(db.debounce(raw_switch))
            data_obj = get_sensor_values()
            data_obj["led_red"] = str(pi_gpio.get_led(1))
            data_obj["led_grn"] = str(pi_gpio.get_led(2))
            data_obj["led_blu"] = str(pi_gpio.get_led(3))
            data_obj["switch"] = debounced_switch
            yield('data: {0}\n\n'.format(data_obj))
            time.sleep(1.0)
    return Response(get_state_values(), mimetype='text/event-stream')
# ============================== API Routes ===================================
```
   

Ensure app.run is the last thing in the code.
```python
if __name__ == "__main__":
    app.run(host='0.0.0.0', debug=True, threaded=True)
```

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartB.md) Send the Sensor Data Object to the Webapp

[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)
[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)

## Part B - Send the Sensor Data Object to the Webapp
**Synopsis:** In order to communicate sensor data from our Python driver program
and main web server, we need to package it in a Python dictionary structure and 
sent it via Server Sent Events as a single data item and then decode it into a
JavaScript Object.

## Objectives
* Point to new lab5.css and lab5.js file after renaming them for Lab5
* Test that the single quoted text sensor structure arrives at the web
* Convert single quoted strings to double quoted (required by JSON.parse)
* Convert the sensor JSON data into a JavaScript object

### Step B1: Adjust index.html <head> section for lab5.css and lab5.js name change
```
<head>
  <meta charset="utf-8">
  <title>UW IoT Lab5</title>
  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/bootstrap.min.css') }}">
  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/lab5.css') }}">
  <script src="{{ url_for('static',filename='js/jquery-3.1.1.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/bootstrap.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/lab5.js') }}"></script>
</head>
```

### Step B2: Adjust lab5.js iotSource.onmessage function for initial test
```python
iotSource.onmessage = function(e) {
  console.log(e.data);
}
```

### Step B3: Start Webserver and Verify that IoT sensor text data is sent
Start Webserver
```sh
pi$ ./main.py
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger pin code: 269-766-075
   192.168.1.17 - - [11/Feb/2017 17:14:34] "GET /myData HTTP/1.1" 200 -
```

Using Google Chrome Developer Tools (right click 'inspect') observe console
The following should be what the text version of the sensor object looks like.
```
{'led_red': '1', 'chip_id': 88, 'led_grn': '1', 'temperature': {'units': 'C', 'reading': 25.41}, 'chip_version': 1, 'pressure': {'units': 'hPa', 'reading': 1018.8871169722084}, 'switch': '0', 'led_blu': '1'}

```
### Step B4: convert the sensor JSON data into a JavaScript object
```JavaScript
iotSource.onmessage = function(e) {
  // must convert all single quoted data with double quote format
  var dqf = e.data.replace(/'/g, '"');
  // now we can parse into JSON
  d = JSON.parse(dqf);
  console.log(d);
}
```

Verify that we now have a JavaScript representation of the sensor object in the
Chrome Console.
![JavaScript Object](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/JS_SensorObject.png)


[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartC.md) Display Time, Temp and Pressure in a Bootstrap Table Structure

[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)
[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)

## Part C - Display Time, Temp and Pressure in a Bootstrap Table Structure
**Synopsis:** We now need to add a few new JavaScript libraries and stylesheets
in order to spruce up our user interface for displaying data. 

## Objectives
* Download jQuery-UI, RaphaelJS and MorrisJS and install in static assets
* Configure a "Tabbed" Panel for our Data Dashboard
* Shrink and Optimize the LED and Switch Dashboard
* JavaScript array object to handle data feed

### Step C1: Download Tools (JS and CSS) jQuery-UI, RaphaelJS and MorrisJS
Download the above libraries and copy the ```min.css``` and ```min.js``` files 
(if ```minified``` is availabl) into the static assets folder. The folder should 
look like this after downloading and copying assets from the above libaries:

```
pi$ ls -l static/css/
total 176
-rw-r--r-- 1 pi pi 121200 Feb 11 16:38 bootstrap.min.css
-rw-r--r-- 1 pi pi  32076 Sep 14 18:34 jquery-ui.min.css
-rw-r--r-- 1 pi pi  13849 Sep 14 18:34 jquery-ui.theme.min.css
-rw-r--r-- 1 pi pi    986 Feb 12 10:22 lab5.css
-rwxr-xr-x 1 pi pi    433 Jun 15  2014 morris.css

pi$ ls -l static/js/
total 512
-rw-r--r-- 1 pi pi  37045 Feb 11 16:38 bootstrap.min.js
-rw-r--r-- 1 pi pi  86709 Feb 11 16:38 jquery-3.1.1.min.js
-rw-r--r-- 1 pi pi 253669 Sep 14 18:34 jquery-ui.min.js
-rw-r--r-- 1 pi pi   5552 Feb 12 15:34 lab5.js
-rwxr-xr-x 1 pi pi  35652 Jun 15  2014 morris.min.js
-rw-r--r-- 1 pi pi  93251 Feb  9 20:36 raphael.min.js
```

### Step C2: New Dashboard!
As we try to pack more sensor data types and displays into our small display, we
need to find a better UI element to display. Enter the "Tabbed" display! 
Fortunately we don't have to work hard at all to have a tab based panel display.
The above libraries provide us with a simple way to have this multi-tab interface.

![Dashboard with jQuery-UI](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/Dashboard-jQuery-UI.png)

Rather than detail out the Web design and coding steps (since this isn't a Web
design class) let's focus on just using this capability and doing just the small
amount of coding required to integrate what we coded in class already for tablular
data display.

### Step C3: GIT PULL and Let's GO!
We want to keep pace with next labs and there's quite a bit of UI tweaking required
to get the display just the way we want it for this stage.  Therefore just do a
git pull and you'll be 100% ready to move on to the homework of integrating the
pressure data chart.

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartD.md) Add MorrisJS Charting Capability for the Pressure

[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)
[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)

## Part D - Add MorrisJS Charting Capability for the Pressure
**Synopsis:** In parts A-C we built up quite a capability from capturing our sensor
data in Python, converting the sensor data object to JavaScript and then a fairly
major overhaul of our webapp UI to get into position for adding multiple sensor
data types.  This is just the beginning of the typical process of creating a 
sensor dashboard.  For this last part we'll just detail what we had to do to 
successfully integrate the MorrisJS temperature chart and we'll leave it as the
Lab5 homework exercise to do the same for the pressure chart.

## Objectives
* Describe how to Integrate MorrisJS Charting Capability
* JavaScript code modifications and new functions to handle temperature charting
* Description of how to integrate pressure

### Step D1: MorrisJS Charting Capability
Morris.js provides a very simple way to get started with clean and useful chart
integration into our web displays including hover data point viewing.  Visit the 
following website for Morris to study the APIs.
[MorrisJS](http://morrisjs.github.io/morris.js/)

We will integrate the simple line chart based on their starter example.  First we 
will need to put an HTML element that will place the chart.  We will locate this 
in one of the jQuery Tabbed panel elements as follows in the ```<div id="tabs-temp">```
element:
```html
    <div id="tabs">
      <ul>
        <li><a href="#tabs-table-data">Table Data</a></li>
        <li><a href="#tabs-temp">Temperature Chart</a></li>
        <li><a href="#tabs-press">Pressure Chart</a></li>
      </ul>
      
      <div id="tabs-table-data">
        <table class="table table-hover table-striped">
            ... (table data)
        </table>
      </div>
      
      <div id="tabs-temp">
        <div id="mytempchart" style="height: 70%; width: 95%;"></div>
      </div>
      
      <div id="tabs-press">
        ...
      </div>
    </div>

```
The inclusion of MorrisJS charting will reference the css id ```mytempchart``` as
a means to render the chart.

### Step D2: JavaScript functions for Temperature Charting
We added Morris charting capability to ```lab5.js``` as follows.  First we need
to create an object to refer to the temperature chart. This contains a data
array that will hold a series of (time, y-value) to be plotted.  Once we've
instantiated the ```graph``` object, we can add data to it as shown in the next
code snippet.
```javascript
var graph = new Morris.Line({
  element: 'mytempchart',
  data: [],
  xkey: 'time',
  ykeys: ['value'],
  labels: ['Value']
});
```

In this simple dashboard, we have hardcoded 5 data points that stream update.  
That is, when we pass data to this chart it is the last 5 data points captured
on a moving time window of 5 data points.
```javascript
function update_temp_chart(data) {
  var chart_data = [
    { time: data[0]['time'], value: data[0]['temp'] },
    { time: data[1]['time'], value: data[1]['temp'] },
    { time: data[2]['time'], value: data[2]['temp'] },
    { time: data[3]['time'], value: data[3]['temp'] },
    { time: data[4]['time'], value: data[4]['temp'] }
  ];
  graph.setData(chart_data);
}
```

Finally, we'll show the ```updateSensors``` function which calls this function to
update the display.  Note that only whene the tab is selected will the chart be
in view on the web page.

```javascript
updateSensors = (function (d) {
  var t_c = d['temperature'].reading
  var p_mbar = d['pressure'].reading
  var t_f = (t_c * 9) / 5.0 + 32.0;
  var p_inHg = p_mbar * MBAR_TO_inHG;

  var timedata = getDateNow();
  var t =  t_c.toFixed(1) + ' | ' + t_f.toFixed(1);
  var p =  p_mbar.toFixed(1) + ' | ' + p_inHg.toFixed(2);

  var obj = {};
  obj['date'] = timedata.date;
  obj['time'] = timedata.date;
  obj['temp'] = t;
  obj['press'] = p;
  data.push(obj);

  console.log(timedata);
  if (data.length > 5) {
    data.shift();
    clearTable();
    updateTable(data);
    update_temp_chart(data);
  }
});
```
The result of all these modifications is that we now have a temperature chart in
our dashbard on the temperature tab panel.
![TemperatureDashboardChart](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/DashboardTemperature.png)

### Step D3: Homework => Create MorrisJS Pressure Chart
For this week's homework you will want to make changes to the index.html (tab 
panel structure) and the JavaScript to incorporate a 5 datapoint pressure chart
much the same way the temperature chart was created.  

Good luck!  (The solution will be posted below after the assignment is completed)

```
Solution coming soon!
```

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartC.md) Display Time, Temp and Pressure in a Bootstrap Table Structure

[LAB5 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab5

### Objectives
For this lab we will continue building on our IoT suite by creating a web app
for our BMP280 sensor device.  We will maintain our LED/Switch configuration for
now and optimize the user interface dashboard for panels of each sensing element. 
We will particularly focus on how to create data objects in one language (Python) 
and transport them (via SSE) to another language (JavaScript).  This is how our
Thing will continue to get smarter in talking to the Internet.

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartA.md) Create a Sensor Data Object
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartB.md) Send the Sensor Data Object to the Webapp
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartC.md) Display Time, Temp and Pressure in a Bootstrap Table Structure
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab5/PartD.md) Add MorrisJS Charting Capability for the Pressure

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)

## Part A - Test SenseHat Hardware
**Synopsis:** We need to initially test and ensure that the SenseHat hardware is
functional and driver is loaded.

## Objectives
* Fasten [SenseHat](https://www.raspberrypi.org/products/sense-hat/) to RPi3 Platform
* Browse to the [SenseHat API](http://pythonhosted.org/sense-hat/api/)
* Startup and manually send a message and read some temperature data

### Step A1: Install SenseHat Library
```sh
pi$ sudo apt-get update
pi$ sudo apt-get install sense-hat
pi$ sudo reboot
```

### Step A2: Hello SenseHat
```sh
pi$ python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hello SenseHat World!")
```
This should scroll a message across the SenseHat LED Matrix Display.


### Step A3: Verify some Sensor Data
```sh
pi$ python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> temp = sense.get_temperature()
>>> print("Temperature: %s C" % temp)
Temperature: 31.2470054626 C
>>> <ctrl-D>
```

### Step A4: Check the I2C Bus Address Map
```sh
pi$ sudo i2cdetect -y 1
0  1  2  3  4  5  6  7  8  9  a  b  c  d  e  f
00:          -- -- -- -- -- -- -- -- -- -- -- -- --
10: -- -- -- -- -- -- -- -- -- -- -- -- 1c -- -- --
20: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
30: -- -- -- -- -- -- -- -- -- -- -- -- -- -- -- --
40: -- -- -- -- -- -- UU -- -- -- -- -- -- -- -- --
50: -- -- -- -- -- -- -- -- -- -- -- -- 5c -- -- 5f
60: -- -- -- -- -- -- -- -- -- -- 6a -- -- -- -- --
70: -- -- -- -- -- -- -- --
```
You are now ready to use SenseHat!

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartB.md) Import jQuery UI Framework for Lab6

[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)
[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)

## Part C - Import jQuery UI Framework for Lab6
**Synopsis:** We will simply perform a git pull on iot110-student to pull all of
the relevant JS libraries and the HTML/CSS code needed for this webapp.

## Objectives
* Check to ensure static folder is available
* static/js
* static/css


### Step C1: check the JS folder
```sh
pi$ cd ~/Documents/GIT_REPOS/iot110

pi$ ls -l static/js
total 508
-rw-r--r-- 1 pi pi  37045 Feb 14 06:36 bootstrap.min.js
-rw-r--r-- 1 pi pi  86709 Feb 14 06:36 jquery-3.1.1.min.js
-rw-r--r-- 1 pi pi 253669 Feb 14 06:36 jquery-ui.min.js
-rw-r--r-- 1 pi pi   3250 Feb 16 08:23 lab6.js
-rw-r--r-- 1 pi pi  35652 Feb 14 06:36 morris.min.js
-rw-r--r-- 1 pi pi  93251 Feb 14 06:36 raphael.min.js
```

### Step C2: check the CSS folder
```sh
pi$ ls -l static/css
total 176
-rw-r--r-- 1 pi pi 121200 Feb 14 06:37 bootstrap.min.css
-rw-r--r-- 1 pi pi  32076 Feb 14 06:37 jquery-ui.min.css
-rw-r--r-- 1 pi pi  13849 Feb 14 06:37 jquery-ui.theme.min.css
-rw-r--r-- 1 pi pi    986 Feb 14 06:37 lab6.css
-rw-r--r-- 1 pi pi    433 Feb 14 06:37 morris.css

```

You are now ready to use develop the SenseHat API and Main WebApp Code

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartC.md) SenseHat Driver and Main WebApp Python Code

[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)
[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)

## Part C - SenseHat Driver and Main WebApp Python code
**Synopsis:** Now we are developing an interface similar to our other sensor
labs.

## Objectives
* Create ```sense.py``` and add various sensor APIs
* UnitTest ```sense.py``` (via its main function)
* Modify ```main.py```

### Step C1: SenseHat Driver ```sense.py```
```python
#!/usr/bin/python
from sense_hat import SenseHat

class PiSenseHat(object):
    """Raspberry Pi 'IoT Sense Hat API Driver Class'."""

    # Constructor
    def __init__(self):
        self.sense = SenseHat()
        # enable all IMU functions
        self.sense.set_imu_config(True, True, True)

    ... (more to come...)    
```

### Step C2: Add an API for each Sensor
```python
# Pressure
def getPressure(self):
    return self.sense.get_pressure()

# Temperature
def getTemperature(self):
    return self.sense.get_temperature()

# Humidity
def getHumidity(self):
    return self.sense.get_humidity()

def getHumidityTemperature(self):
    return self.sense.get_temperature_from_humidity()

def getPressureTemperature(self):
    return self.sense.get_temperature_from_pressure()

def getOrientationRadians(self):
    return self.sense.get_orientation_radians()

def getOrientationDegrees(self):
    return self.sense.get_orientation_degrees()

# degrees from North
def getCompass(self):
    return self.sense.get_compass()

def getAccelerometer(self):
    return self.sense.get_accelerometer_raw()

def getEnvironmental(self):
    sensors = {'name' : 'sense-hat', 'environmental':{}}
    return sensors

def getJoystick(self):
    sensors = {'name' : 'sense-hat', 'joystick':{}}
    return sensors

def getInertial(self):
    sensors = {'name' : 'sense-hat', 'inertial':{}}
```


### Step C3: Add an API for each Sensor
```python
def getAllSensors(self):
    sensors = {'name' : 'sense-hat', 'environmental':{}, 'inertial':{}, 'joystick':{}}
    sensors['environmental']['pressure'] = { 'value':self.sense.get_pressure(), 'unit':'mbar'}
    sensors['environmental']['temperature'] = { 'value':self.sense.get_temperature(), 'unit':'C'}
    sensors['environmental']['humidity'] = { 'value':self.sense.get_humidity(), 'unit': '%RH'}
    accel = self.sense.get_accelerometer_raw()
    sensors['inertial']['accelerometer'] = { 'x':accel['x'], 'y':accel['y'], 'z': accel['z'], 'unit':'g'}
    orientation = self.sense.get_orientation_degrees()
    sensors['inertial']['orientation'] = { 'compass':self.sense.get_compass(), 'pitch':orientation['pitch'], 'roll':orientation['roll'], 'yaw': orientation['yaw'], 'unit':'degrees'}
    return sensors
```

### Step C3: main to test from CLI
```python
def main():

    # create an instance of my pi sense-hat sensor object
    pi_sense_hat = PiSenseHat()

    # Read Parameters.
    p = pi_sense_hat.getPressure()
    t_c = pi_sense_hat.getTemperature()
    h = pi_sense_hat.getHumidity()
    ht = pi_sense_hat.getHumidityTemperature()
    hp = pi_sense_hat.getPressureTemperature()
    orientation = pi_sense_hat.getOrientationDegrees()
    accel = pi_sense_hat.getAccelerometer()
    d = pi_sense_hat.getCompass()

    print("================ Discrete Sensor Values ==================")
    print "      Pressure :", p
    print "   Temperature :", t_c
    print "      Humidity :", h
    print "  HumidityTemp :", ht
    print "  PressureTemp :", hp
    print "       Compass :", d
    print("  p: {pitch}, r: {roll}, y: {yaw}".format(**orientation))
    print("  x: {x}, y: {y}, z: {z}".format(**accel))
    print("==========================================================\n")

    print("================== Dictionary Object =====================")
    print(pi_sense_hat.getAllSensors())
    print("==========================================================\n")

if __name__=="__main__":
   main()
```

### Step C4: the ```Flask main.py```
```python
#!/usr/bin/python
import time
from sense import PiSenseHat
from flask import *

# create Pi SenseHat Object
pi_sense_hat = PiSenseHat()

# ============================== Functions ====================================
def get_sensor_values():
    return pi_sense_hat.getAllSensors()

# ============================== API Routes ===================================
app = Flask(__name__)

@app.route("/")
def index():
    return render_template('index.html')

# =========================== Endpoint: /myData ===============================
# read the sensor values by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            data_obj = get_sensor_values()
            yield('data: {0}\n\n'.format(data_obj))
            time.sleep(1.0)
    return Response(get_values(), mimetype='text/event-stream')
# ============================== API Routes ===================================

if __name__ == "__main__":
    app.run(host='0.0.0.0', debug=True, threaded=True)
```

OK, onward to our webapp!

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartD.md) Build Sensor UI Components

[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)
[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)

## Part D - Finally!  The Web appeared
**Synopsis:** Finally we will tie all of this together and have all of our sensor
values both plotable and graphed on our Morris JS Chart.

## Objectives
* Test that we can receive data from the Driver and Main
* Add code to display Environmental Data in a Table in real-time
* Add code to display Inertial Data in a Table in real-time
* Add code to display Environmental Data in a in a Chart Form
* Add code to display Inertial Data in a Chart Form

### Step D1: Let's test the incoming data
```Javascript
$(document).ready(function() {

  // the key event receiver function
  iotSource.onmessage = function(e) {
    // must convert all single quoted data with double quote format
    var double_quote_formatted_data = e.data.replace(/'/g, '"');
    // now we can parse into JSON
    parsed_json_data = JSON.parse(double_quote_formatted_data);
    console.log(parsed_json_data);
  }
    ...more to come
```    

### Step D2:

![Inertial  Table Data](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/InertialTable.png)

![Inertial Chart Data](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/InertialChart.png)

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartC.md) SenseHat Driver and Main WebApp Python Code

[LAB6 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab6

**Synopsis:** For this lab we will continue building on our IoT suite by creating a web app
for the SenseHat device.  We will build on the jQuery  dashboard user interface
we started in Lab5, but focus on the major functional sensor and actuator classes
of the SenseHat platform.  Using the same Server Sent Events and JavaScript
charting capability we established in Lab5, we will extend to the *Environmental*,
*Inertial* sensors and provision for a future UI around the *JoyStick* and *LED
Matrix* Display capability.

### Objectives
* Test to ensure SenseHat hardware is functional and Python Library is Loaded
* Import jQuery UI HTML/CSS *Tabbed Panel* Framework
* Build a ```sense.py``` Python Driver to Provide an API for the SenseHat
* Interface the main Flask webapp ```main.py``` to the SenseHat Driver
* Add JavaScript code to parse the SenseHat sensor data and render on Tab panels

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartA.md) Test SenseHat Hardware
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartB.md) Import jQuery UI Framework for Lab6
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartC.md) SenseHat Driver and Main WebApp Python code
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab6/PartD.md) Build Sensor UI Components

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Additional Supplemental Information for Debug ##
If your SenseHat is experiencing specific errors, your RPi may be in need of an
update ... see below:
[Errors running SenseHat](https://www.reddit.com/r/raspberry_pi/comments/3yg0rz/sense_hat_and_jessie/)

May need to run
```
pi$ sudo rpi-update
 *** Downloading specific firmware revision (this will take a few minutes)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
                                 ...
 *** Updating firmware
 *** Updating kernel modules
 *** depmod 4.4.48+
 *** depmod 4.4.48-v7+
 *** Updating VideoCore libraries
 *** Using HardFP libraries
 *** Updating SDK
 *** Running ldconfig
 *** Storing current firmware revision
 *** Deleting downloaded files
 *** Syncing changes to disk
 *** If no errors appeared, your firmware was successfully updated to 71c475563fd5aa4ade62c9a31dd25865ab7d4a7b
 *** A reboot is needed to activate the new firmware
```
[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)

## Part A - Check Starter Files, Sensors and PWM
**Synopsis:** In this part, we will re-test that the BMP280 sensor is still 
operating correctly and also run the pre-coded unit test for LED PWM control. 
Due to the amount of code needed to operate the stepper motor, the LED PWM 
driver and unit test are provided for this lab.

## Objectives
* Check to ensure all starter files are present in the lab
* Run the BMP280 temperature and pressure sensor unit test
* Run the LED PWM unit test

### Step A1: Check starter files
```sh

pi$ git pull (from iot110-student REPO, then copy to your working folder)

pi$ cd webapp
pi$ tree  .
.
â”œâ”€â”€ bmp280.py
â”œâ”€â”€ main.py
â”œâ”€â”€ pwm.py
â”œâ”€â”€ pwm_test.py
â”œâ”€â”€ static
â”‚Â Â  â”œâ”€â”€ css
â”‚Â Â  â”‚Â Â  â”œâ”€â”€ bootstrap.min.css
â”‚Â Â  â”‚Â Â  â”œâ”€â”€ jquery-ui.min.css
â”‚Â Â  â”‚Â Â  â”œâ”€â”€ jquery-ui.theme.min.css
â”‚Â Â  â”‚Â Â  â”œâ”€â”€ lab7.css
â”‚Â Â  â”‚Â Â  â””â”€â”€ morris.css
â”‚Â Â  â”œâ”€â”€ icon
â”‚Â Â  â”‚Â Â  â””â”€â”€ favicon.ico
â”‚Â Â  â””â”€â”€ js
â”‚Â Â      â”œâ”€â”€ bootstrap.min.js
â”‚Â Â      â”œâ”€â”€ jquery-3.1.1.min.js
â”‚Â Â      â”œâ”€â”€ jquery-ui.min.js
â”‚Â Â      â”œâ”€â”€ lab7.js
â”‚Â Â      â”œâ”€â”€ morris.min.js
â”‚Â Â      â””â”€â”€ raphael.min.js
â”œâ”€â”€ stepper.py
â”œâ”€â”€ stepper_test.py
â””â”€â”€ templates
    â””â”€â”€ index.html

```    

### Step A2: Run BMP280 Unit Test
```python
# =============================================================================
# main to test from CLI
def main():

    # create an instance of my pi bmp280 sensor object
    pi_bmp280 = PiBMP280()

    # Read the Sensor ID.
    (chip_id, chip_version) = pi_bmp280.readBMP280ID()
    print "    Chip ID :", chip_id
    print "    Version :", chip_version

    # Read the Sensor Temp/Pressure values.
    (temperature, pressure) = pi_bmp280.readBMP280All()
    print "Temperature :", temperature, "C"
    print "   Pressure :", pressure, "hPa"

if __name__=="__main__":
   main()
# =============================================================================

# -----------------------------------------------------------------------------
pi$ ./bmp280
    Chip ID : 88
    Version : 1
Temperature : 24.78 C
   Pressure : 1006.53054419 hPa
# -----------------------------------------------------------------------------
```    

### Step A3: Run LED PWM Unit Test
```python
# =============================================================================
#!/usr/bin/python

import time
from pwm import PiPwm

PWM0 = 0    # logical handle for RPi3 PWM0
PWM1 = 1    # logical handle for RPi3 PWM1
# create an instance of my pi thing.
pi_pwm = PiPwm()

# Create two counter breathing PWM LEDs
print('Connect RED LED to GPIO18, GREEN LED to GPIO13, DIR SW to GPIO25')

time.sleep(1.0)
print('Starting PWM0 at 5Hz with 75% duty cycle')
ch0 = pi_pwm.start_pwm(0, 5, 75)
# time.sleep(0.01)
print('Starting PWM1 at 3Hz with 10% duty cycle')
ch1 = pi_pwm.start_pwm(1, 5, 10)

time.sleep(10.0)
print('Stopping PWM0')
pi_pwm.stop_pwm(ch0)
time.sleep(3.0)
print('Stopping PWM1')
pi_pwm.stop_pwm(ch1)
# =============================================================================

(review the pwm.py driver in Atom)

$pi ./pwm_test.py
Connect RED LED to GPIO18, GREEN LED to GPIO13, DIR SW to GPIO25
Starting PWM0 at 5Hz with 75% duty cycle
Starting PWM1 at 3Hz with 10% duty cycle
Stopping PWM0
Stopping PWM1
```    

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartB.md) Develop stepper.py and unit test

[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)
[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)

## Part B - Develop Stepper Motor Driver and Unit Test
**Synopsis:** We will be controlling the stepper motor using the TB6612 driver 
chip.  This chip buffers the GPIO signals driving the AIN1/2, BIN1/2 and STBY
signals and turns them into 4 high current driver outputs.  All of the signals
are manually managed by bit banging the GPIOs (no automatic PWM timing).  The "PWM"
signals listed in the TB6612 datasheet are simply tied to +5V.

## Objectives
* Code the ```stepper.py``` Driver
* Code the ```stepper_test.py``` Unit Test
* Run the Stepper Unit Test and Check all wiring

### Step B1: The ```stepper.py``` Driver [import | constants | constructor]
```python
import RPi.GPIO as GPIO
import time

LED     = 23    # GPIO23 RUNNING STATUS LED
SW      = 25    # cobbler pin 22 (GPIO25)

AIN1    = 19    # GPIO19 TB6612 AIN1 Logic Input
AIN2    = 26    # GPIO26 TB6612 AIN2 Logic Input
BIN1    = 20    # GPIO20 TB6612 BIN1 Logic Input
BIN2    = 21    # GPIO21 TB6612 BIN2 Logic Input
STBY    = 16    # GPIO16 TB6612 Standby Input

# =============================================================================
# create a Stepper Motor Object
# -----------------------------------------------------------------------------
class PiStepper(object):
    """Raspberry Pi 'IoT GPIO Stepper Motor'."""

    def __init__(self, freq=10, steps=600):
        self.steps_per_rev = steps
        self.sec_per_step = 0.1
        self.steppingcounter = 0
        self.currentstep = 0
        self.speed = 0
        self.state = 0
        self.steps = 0
        self.direction = 0
        self.position = 0

        GPIO.setwarnings(False)
        GPIO.setmode(GPIO.BCM)          # BMC Pin numbering convention
        GPIO.setup(LED, GPIO.OUT)       # LED as output
        GPIO.setup(AIN1, GPIO.OUT)      # AIN1 as output
        GPIO.setup(AIN2, GPIO.OUT)      # AIN2 as output
        GPIO.setup(BIN1, GPIO.OUT)      # BIN1 as output
        GPIO.setup(BIN2, GPIO.OUT)      # BIN2 as output
        GPIO.setup(STBY, GPIO.OUT)      # Standby as output
        GPIO.output(AIN1,0)             # initialize AIN1 state to off
        GPIO.output(AIN2,0)             # initialize AIN2 state to off
        GPIO.output(BIN1,0)             # initialize BIN1 state to off
        GPIO.output(BIN2,0)             # initialize BIN2 state to off
        GPIO.output(STBY,0)             # initialize Standby state to off
        GPIO.setup(SW,  GPIO.IN, pull_up_down=GPIO.PUD_UP)
# -----------------------------------------------------------------------------

```    

### Step B2: Add Basic Interface Methods, Getters/Setters
```python
# -----------------------------------------------------------------------------
    def hello(self):
        print "Hello Stepper"

    def start(self):
        print "Starting Stepper Motor"
        GPIO.output(LED,1)      # turn on LED status
        GPIO.output(STBY,1)     # TB6612 Standby State TRUE
        self.state = 1

    def stop(self):
        print "Stopping Stepper Motor"
        GPIO.output(LED,0)      # turn off LED status
        GPIO.output(STBY,0)     # TB6612 Standby State FALSE
        self.state = 0

    def getState(self):
        return self.state

    # get motor position
    def getPosition(self):
        return self.position

    # set motor position
    def setPosition(self,position):
        self.position = position

    # set the speed parameters for stepper motor based on RPM
    def setSpeed(self, rpm):
        self.sec_per_step = 60.0 / (self.steps_per_rev * rpm)
        self.steppingcounter = 0
        self.speed = rpm

    def getSpeed(self):
        return self.speed
# -----------------------------------------------------------------------------
```

### Step B3: Add Stepper Coil Sequencing
```python

    # perform one step in sequence at a direction CW or CCW
    def oneStep(self, direction):
        # go to next 'step' and wrap around
        self.direction = direction
        coils = [0, 0, 0, 0]
        step2coils = [
        #    A2 B1 A1 B2
            [1, 0, 0, 0],
            [1, 1, 0, 0],
            [0, 1, 0, 0],
            [0, 1, 1, 0],
            [0, 0, 1, 0],
            [0, 0, 1, 1],
            [0, 0, 0, 1],
            [1, 0, 0, 1] ]
        coils = step2coils[self.currentstep]
        # print '%d', self.currentstep, " : coils = AIN1:%d AIN2:%d BIN1:%d BIN2:%d" % (coils[2],coils[0],coils[1],coils[3])

        # post increment/decrement the modulo step counter depeneding on direction
        #   also update the stepper position (one tic per step)
        if(direction == 1):
            self.currentstep += 1
            self.position += 1
        else:
            self.currentstep -= 1
            self.position -= 1
        self.currentstep %= 8

        #print "coils state = " + str(coils)
        self.setPin(AIN2, coils[0])
        self.setPin(BIN1, coils[1])
        self.setPin(AIN1, coils[2])
        self.setPin(BIN2, coils[3])

    # set current pin in sequence
    def setPin(self, pin, value):
        GPIO.output(pin,value)

    # set motor direction
    def setDirection(self,direction):
        self.direction = direction

    # get motor direction
    def getDirection(self):
        return self.direction

    # set motor steps
    def setSteps(self,steps):
        self.steps = steps

    # get motor direction
    def getSteps(self):
        return self.steps

    # execute all steps
    def step(self, steps):
        s_per_s = self.sec_per_step

        for s in range(steps):
            self.oneStep(self.direction)
            time.sleep(s_per_s)

    # de-energize all coils
    def nullCoils(self):
        coils = [0, 0, 0, 0]
        self.setPin(AIN2, coils[0])
        self.setPin(BIN1, coils[1])
        self.setPin(AIN1, coils[2])
        self.setPin(BIN2, coils[3])

```

### Step B4: Add Stepper Unit Test
```python
#!/usr/bin/python
import time
from stepper import PiStepper

CW = 1
CCW  = 0

# Create a stepper motor controller object
pi_smc = PiStepper()
print('Motor Controller Initialized')

# set the initial RPM speed

pi_smc.start()
pi_smc.setSpeed(100)
print 'Finding Home Position...'
pi_smc.setDirection(CCW)
pi_smc.step(1200)
pi_smc.setPosition(0)

# loop through several CW and CCW steps
for rpm in range(100,200):
    pi_smc.setSpeed(rpm)
    print '\n-------> Speed: %d rpm <-------' % (rpm)

    print('Stepping CW')
    pi_smc.setDirection(CW)
    pi_smc.step(600)
    time.sleep(0.2)
    pi_smc.step(600)
    print 'Position: %d (steps)' % (pi_smc.getPosition())

    print('Change Dir')
    pi_smc.nullCoils()
    time.sleep(0.1)

    print('Stepping CCW')
    pi_smc.setDirection(CCW)
    pi_smc.step(600)
    time.sleep(0.2)
    pi_smc.step(600)
    print 'Position: %d (steps)' % (pi_smc.getPosition())
    print('Change Dir')
    pi_smc.nullCoils()
    time.sleep(0.1)

print('Stopping Motor')
pi_smc.stop()
```

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartC.md) Modify main.py for stepper and PWM control code

[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)
[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)

## Part C - Modify our ```main.py``` to include stepper
**Synopsis:** We've added our driver code now we need to hook up our API so that 
the webapp can connect to it.

## Objectives
* Top of Main
* Environmental Sensor Gather Function
* API Routes for the Stepper
* API Routes for the PWM LED (to be done in class)

### Step C1: top of main.py
```python
#!/usr/bin/python
import time
import pprint
from stepper import PiStepper
from bmp280 import PiBMP280
from flask import *
app = Flask(__name__)

# Create a stepper motor controller object
pi_smc = PiStepper()

# create a pi bmp280 sensor object and data structure
env_sensor = {'name' : 'bmp280', 'addr' : 0x76, 'chip' : PiBMP280(0x76) , 'data' : {}}
```    

### Step C2: Environmental Sensors
```python
## function to read environmental parameters
def get_env_sensors():
    # Read the Sensor ID for 0x76 -> values into the ['data'] dictionary
    (chip_id, chip_version) = env_sensor['chip'].readBMP280ID()
    env_sensor['data']['chip_id'] = chip_id
    env_sensor['data']['chip_version'] = chip_version

    # Read the Sensor Temp/Pressure values into the ['data'] dictionary
    (temperature, pressure) = env_sensor['chip'].readBMP280All()
    env_sensor['data']['temperature'] = { 'reading': temperature, 'units' : 'C' }
    env_sensor['data']['pressure'] = { 'reading': pressure, 'units' : 'hPa' }
    return env_sensor['data']
```

### Step C3: API Route to kick off Webpage
```python
# ============================== API Routes ===================================
@app.route("/")
def index():
    return render_template('index.html')
    
```

### Step C4: API Routes for Stepper Motor
```python
# ============================= POST: /motor/<state> ============================
# control motor by POST methods from curl for example
# curl http://iot8e3c:5000/motor/0
# curl http://iot8e3c:5000/motor/1
# -----------------------------------------------------------------------------
@app.route("/motor/<int:motor_state>", methods=['GET'])
def motor(motor_state):
    if motor_state == 0:    # stop
        pi_smc.stop()
    elif motor_state == 1:      # start
        pi_smc.start()
    else:
        return ('Unknown Stepper Motor state!', 400)
    return ('', 204)


# ====================== GET: /motor_speed/<speed_rpm> ========================
# set the motor speed in RPM by GET method from curl. For example:
# curl http://iot8e3c:5000/motor_speed/60
# -----------------------------------------------------------------------------
@app.route("/motor_speed/<int:motor_speed>", methods=['GET'])
def set_motor_speed(motor_speed):
    pi_smc.setSpeed(motor_speed)
    return "Set Motor Speed : " + str(pi_smc.getSpeed()) + "\n"

# ===================== GET: /motor_direction/<direction> =====================
# set the motor direction (CW/CCW) by GET method from curl. For example:
# curl http://iot8e3c:5000/motor_direction/1
# -----------------------------------------------------------------------------
@app.route("/motor_zero", methods=['GET'])
def set_motor_zero():
    pi_smc.setPosition(0)
    return "Set Motor Position : " + str(pi_smc.getPosition()) + "\n"

# ===================== GET: /motor_direction/<direction> =====================
# set the motor direction (CW/CCW) by GET method from curl. For example:
# curl http://iot8e3c:5000/motor_direction/1
# -----------------------------------------------------------------------------
@app.route("/motor_direction/<string:direction>", methods=['GET'])
def set_motor_dir(direction):
    pi_smc.setDirection(direction)
    return "Set Motor Direction : " + str(pi_smc.getDirection()) + "\n"

# ===================== GET: /motor_steps/<steps> =====================
# set the motor steps (int) by HTTP GET method  CURL example:
# curl http://iot8e3c:5000/motor_steps/100
# -----------------------------------------------------------------------------
@app.route("/motor_steps/<int:steps>", methods=['GET'])
def set_motor_steps(steps):
    pi_smc.setSteps(steps)
    return "Set Motor Steps : " + str(pi_smc.getSteps()) + "\n"

# ====================== GET: /motor_position/<position> ======================
# set the motor position by HTTP GET method. CURL example:
# curl http://iot8e3c:5000/motor_position/1
# -----------------------------------------------------------------------------
@app.route("/motor_position/<int:position>", methods=['GET'])
def set_motor_pos(position):
    pi_smc.setDirection(direction)
    return "Set Motor Direction : " + str(pi_smc.getDirection()) + "\n"


# ======================= POST: /motor_multistep/<dir> =========================
# set the motor multistep by POST method from curl. For example:
# curl --data 'steps=10&direction=CW' http://iot8e3c:5000/motor_multistep
# -----------------------------------------------------------------------------
@app.route("/motor_multistep", methods=['POST'])
def postMotorMultistep():
    ctrl_data = request.data
    print "Motor Control Data:" + ctrl_data
    direction = str(request.form['direction'])
    if (direction == 'CW'):
        pi_smc.setDirection(1)
    elif (direction == 'CCW'):      # start
        pi_smc.setDirection(0)
    else:
        return ('Unknown Stepper Motor Direction!', 400)

    steps = str(request.form['steps'])
    pi_smc.step(int(steps))

    return "Motor Multisteps Steps:" + steps + " Direction:"+ direction + "\n"
```

### Step C5: API Route for Server Sent Events + app_main
```python
# =========================== Endpoint: /myData ===============================
# read the sensor values by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            data_obj = {'environmental' : get_env_sensors(),
                        'motor' : { 'position':str(pi_smc.getPosition()),
                                    'state':str(pi_smc.getState()) }
            }

            yield('data: {0}\n\n'.format(data_obj))
            time.sleep(2.0)
    return Response(get_values(), mimetype='text/event-stream')
# ============================== API Routes ===================================

if __name__ == "__main__":
    app.run(host='0.0.0.0', debug=True, threaded=True)
# =============================================================================
```

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartD.md) Refactor index.html and add Javascript Tabs

[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)
[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)

## Part D - Add JavaScript for Stepper/PWM Control and Temp/Pressure Sensor
**Synopsis:** We have all of our low level tools integrated and tested.  Now it's
time to modify our webpage (```index.html```) and the associated (```lab7.js```) 
JavaScript that provides all the interface and dynamic behavior.

## Objectives
* Add additional Tabs and Concent to ```index.html```
* Add Stepper Motor functionality to lab7.js
* Add PWM LED dimmer control to lab7.js

### Step D1: Webapp head section
Ensure all libraries are correctly ordered in ```<head>``` section.
```html
<head>
  <meta charset="utf-8">
  <title>UW IoT Lab7</title>

  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/morris.css') }}">
  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/jquery-ui.min.css') }}">
  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/bootstrap.min.css') }}">
  <link rel="stylesheet" type="text/css" href="{{ url_for('static',filename='css/lab7.css') }}">
  <link rel="shortcut icon" type="image/x-icon" href="{{ url_for('static',filename='icon/favicon.ico') }}">

  <script src="{{ url_for('static',filename='js/jquery-3.1.1.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/bootstrap.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/raphael.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/morris.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/jquery-ui.min.js') }}"></script>
  <script src="{{ url_for('static',filename='js/lab7.js') }}"></script>

</head>
```    

### Step D2: Tabs List Items
```html
                <li><a href="#tabs-environmental-data">EnvironTable</a></li>
                <li><a href="#tabs-stepper">STEPPER</a></li>
                <li><a href="#tabs-ledpwm">PWM LEDS</a></li>
```

### Step D3: Table for Temperature and Pressure
```html
                <table class="table table-hover table-striped">
                  <tr class=param-header>
                    <th>Time (PST)</th>
                    <th>Temperature (&degC)</th>
                    <th>Pressure (mbar)</th>
                  </tr>
                  <tr class=env-param-row>
                  </tr>
                  <tr class=env-param-row>
                  </tr>
                  <tr class=env-param-row>
                  </tr>
                  <tr class=env-param-row>
                  </tr>
                </table>
```

### Step D4: Table for Stepper Controls
```html
                <table>
                  <tr>
                    <td>
                      <!-- <div class="container well"> -->
                        <table class="table">
                          <tr>
                            <td><h6>Motor Status  <span id='motor_state' class="label label-default">&#8635</span></h6></td>
                          </tr>
                          <tr>
                            <td><h6>Motor Position(steps)  <span id="motor_position" class="label label-default">100</span></h6></td>
                          </tr>
                        </table>
                      <!-- </div> -->
                    </td>
                    <td>
                      <table class="table">
                        <tr>
                          <td>New Motor Speed(rpm):</td>
                          <td><input id='motor_speed' type="number" min="0" max="250" name="rpm" value=100></td>
                        </tr>
                        <tr>
                          <td>Number of Steps:</td>
                          <td><input id='motor_steps' type="number" min="0" max="600" name="steps" value=100></td>
                        </tr>
                        <tr>
                          <td>Motor Direction:</td>
                          <td><select id='motor_direction' type="text" name="direction" value="CW">
                                <option value="CW">Clockwise</option>
                                <option value="CCW">Counter Clockwise</option>
                              </select>
                          </td>
                        </tr>
                      </table>
                    </td>
                  </tr>
                </table>
```

### Step D5: Buttons for Stepper Commands
```html
                <div id="stepper_buttons" class="container well">
                  <button type='button' class="btn btn-default" id='motor_start'>START</button>
                  <button type='button' class="btn btn-default" id='motor_stop'>STOP</button>
                  <button type='button' class="btn btn-default" id='motor_zero'>POS ZERO</button>
                  <button type='button' class="btn btn-success" id='motor_multistep'>MULTI-STEP</button>
                </div>
```

### Step D6: Table for PWM LED Sliders
```html
                <table>
                  <tr>
                    <td class="slider-col">
                      <p>
                        <h4>RED LED</h4>
                        DUTY CYCLE (%) <input type="text" id="pwm1" readonly>
                      </p>
                      <div id="slider1"></div>
                    </td>
                    <td class="slider-col">
                      <p>
                        <h4>GREEN LED</h4>
                        DUTY CYCLE (%) <input type="text" id="pwm2" readonly>
                      </p>
                      <div id="slider2"></div>
                    </td>
                  </tr>
                </table>
```

### Step D7: Code for RED LED Slider
```javascript
  $( "#slider1" ).slider({
    orientation: "vertical",
    range: "min",
    min: 0,
    max: 100,
    value: 50,
    animate: true,
    slide: function( event, ui ) {
      $( "#pwm1" ).val( ui.value );
      console.log("red led duty cycle(%):",ui.value);
    }
  });
  
```

### Step D8: Code for GREEN LED Slider
```javascript
  $( "#slider2" ).slider({
    orientation: "vertical",
    range: "min",
    min: 0,
    max: 100,
    value: 50,
    animate: true,
    slide: function( event, ui ) {
      $( "#pwm2" ).val( ui.value );
      console.log("grn led duty cycle(%):",ui.value);
    }
  });
```

### Step D9: Code for Environmental Sensor Tables
```javascript
  // ============================== ENV TABLE =================================
  updateEnvironmentalTableData = (function (d) {
    var env = d;
    var timedata = getDateNow();
    env['date'] = timedata.date;
    env['time'] = timedata.time;

    env_table_data.push(env);
    if (env_table_data.length > 4) {
      env_table_data.shift();
      clearEnvTables();
      updateEnvironmentalTable(env_table_data);
    }
  });

  function updateEnvironmentalTable(data) {
    $('tr.env-param-row').each(function(i) {
      var tm = '<td>' + data[i].date + '</td>';
      var t = '<td>' + data[i]['environmental']['temperature'].reading.toFixed(2) + '</td>';
      var p = '<td>' + data[i]['environmental']['pressure'].reading.toFixed(2) + '</td>';
      $(this).append(tm);
      $(this).append(t);
      $(this).append(p);
    });
  }
  function clearEnvTables() {
    $('tr.env-param-row').each(function(i) {
      $(this).empty();
    });
  }
  // ============================== ENV TABLE =================================
```

### Step D10: Code for Stepper Motor Control
```python
  // ============================ STEPPER MOTOR ===============================
  // Buttons
  $('#motor_start').click(function() {
    console.log('Start Motor Up!');
    $.get('/motor/1');
  });
  $('#motor_stop').click(function() {
    console.log('Stop Motor');
    $.get('/motor/0');
  });
  $('#motor_zero').click(function() {
    console.log('Zero Motor Position');
    $.get('/motor_zero');
  });
  $('#motor_multistep').click(function() {
    var params = 'steps='+$('#motor_steps').val()+"&direction="+$('#motor_direction').val();
    console.log('Multistep with params:' + params);
    $.post('/motor_multistep', params, function(data, status){
                console.log("Data: " + data + "\nStatus: " + status);
            });
  });

  // Text Fields
  $('#motor_speed').change(function() {
    console.log('Changed motor speed to ' + $('#motor_speed').val());
    $.get('/motor_speed/'+$('#motor_speed').val());
  });
  $('#motor_position').change(function() {
    console.log('Changed motor position to ' + $('#motor_position').val());
    $.get('/motor_position/'+$('#motor_position').val());
  });

  $('#motor_steps').change(function() {
    console.log('Changed motor steps to ' + $('#motor_steps').val());
    $.get('/motor_steps/'+$('#motor_steps').val());
  });

  $('#motor_direction').change(function() {
    console.log('Changed motor steps to ' + $('#motor_direction').val());
    $.get('/motor_direction/'+$('#motor_direction').val());
  });

  // ============================ STEPPER MOTOR ===============================
  function updateStepperMotor(data) {
    $('#motor_position').text(data['motor']['position']);
    if (data['motor']['state'] === '1') {
      $('#motor_state').toggleClass('label-default', false);
      $('#motor_state').toggleClass('label-success', true);
    } else if (data['motor']['state'] === '0') {
      $('#motor_state').toggleClass('label-default', true);
      $('#motor_state').toggleClass('label-success', false);
    }
  }
  // ============================ STEPPER MOTOR ===============================
```

[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartC.md) Modify main.py for stepper and PWM control code

[LAB7 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab7

**Synopsis:** For this lab we will continue building on our IoT suite by creating
a web app for ACTUATORS.  For our Lab ACTUATORS we will be using 2 LEDs with a
dimming function created by pulse width modulation (PWM) and an automotive
instrument analog indicator using a precision stepper motor and the TB6612 Driver module.

### Objectives
* Test to ensure BMP280 sensor and driver are still working correctly (no code change)
* Test to ensure PWM LEDs and driver are working correctly (driver and unit test provided)
* Build a driver ```stepper.py``` for the motor and test (unit test provided)
* Interface the main Flask webapp ```main.py``` to the stepper and PWM drivers
* Add new HTML code for the PWM slider controls and stepper motor control.
* Add JavaScript code to add actuator control and status as well as sensing.

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartA.md) Test BMP280 and PWM LEDs
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartB.md) Develop stepper.py and unit test
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartC.md) Modify main.py for stepper and PWM control code
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab7/PartD.md) Refactor ```index.html``` and add Javascript Tabs

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)

## Part A - Install MQTT
**Synopsis:** In this part, we will install and test MQTT.

## Objectives
* apt-get MQTT libraries
* Install MQTT.fx on development host
* Configure and establish user and password

### Step A1: Install Libraries
```sh
sudo apt-get install mosquitto mosquitto-clients python-mosquitto
sudo pip install paho-mqtt

```    

### Step A2: Configure Mosquitto  (/etc/mosquitto/conf.d/mosquitto.conf)
```
pi$ sudo vim /etc/mosquitto/conf.d/mosquitto.conf

# Config file for mosquitto
#
# See mosquitto.conf(5) for more information.

# user mosquitto
# max_queued_messages 200
# message_size_limit 0
# allow_zero_length_clientid true
# allow_duplicate_messages false

listener 1883
# autosave_interval 900
# autosave_on_changes false
# persistence true
# persistence_file mosquitto.db
allow_anonymous false
password_file /etc/mosquitto/passwd
```    
### Step A3: Setup Username ("pi") and Password ("raspberry")
```sh
pi$ sudo mosquitto_passwd -c /etc/mosquitto/passwd pi
Password: ********* (<= "raspberry")
Reenter password: ********* (<= "raspberry")
```  

### Step A4: Start (Restart) the Mosquitto Daemon
```sh
pi$ sudo systemctl restart mosquitto
pi$ sudo reboot
pi$ mosquitto &
```

### Step A5: Subscribe to Topic "iot/test"
```sh
pi$ mosquitto_sub -d -u pi -P raspberry -t iot/test

```

### Step A6: Publish Hello String to Topic "iot/test"
```sh
pi$ mosquitto_pub -d -u pi -P raspberry -t iot/test -m "Hello MQTT!"

```

[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartB.md)  Install MQTT Client Tool MQTT.fx

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)

## Part B - Install MQTT Client Tool MQTT.fx
**Synopsis:** In this part, we will install and test the MQTT.fx client test tool.
This tool is quite useful in troubleshooting connections to the MQTT broker and
is able to explore the operation of publishing and subscribing to "topics".

## Objectives
* Download an [MQTT Test Client](http://www.jensd.de/apps/mqttfx/)
* Install and Configure MQTT.fx on development host
* Connect to our Mosquitto Broker (Server)

### Step B1: Install and Configure MQTT.fx
The following show installation on MacOSX, but a similar install and configuration
should apply to whatever is the target host development platform being used
for development in this class.
![MQTT Connection](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/MQTTfx_Connect.png)

### Step B2: Subscribe to some topics
![Subscribe-Redirect](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/SubscribeRedirect.png)

### Step B3: Publish to some topics
![First Publish](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/MQTT_FirstPub.png)

### Step B4: Observe Subscribed Topics
![Subscribed Topics](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/SubscribeHello.png)


[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartC.md) Create MQTT Python Test Code

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)

## Part C - Create MQTT Python Test Code
**Synopsis:** In this part, we will code a number client entities to simulate
sensors, test real sensors from the SenseHat, create a MQTT listener that also
redirects payloads and sets up the framework that will be used for eventually
connecting to the Azure IoT Suite cloud platfrom.

## Objectives
* apt-get MQTT libraries
* Install MQTT.fx on development host
* Configure and establish user and password

### Step C1: Create an MQTT Listener
As usual, we will need to import a few tools.  We will need som
```python
#!/usr/bin/python
import time
import paho.mqtt.client as paho
import json
import ast

localBroker = "iot8e3c"     # Local MQTT broker
localPort   = 1883          # Local MQTT port
localUser   = "pi"          # Local MQTT user
localPass = "raspberry"     # Local MQTT password
localTopic = "iot/sensor"   # Local MQTT topic to monitor
cloudTopic = "iot/azure"    # publish to simulated Azure topic 
localTimeOut = 120          # Local MQTT session timeout

```    

### Step C2: Event Callback for On Connect
```python
# The callback for when a CONNACK message is received from the broker.
def on_connect(client, userdata, flags, rc):
    print("CONNACK received with code %d." % (rc))
    mqttc.subscribe(localTopic, 0)
```

### Step C3: Event Callback for On Message
```python
def on_message(mosq, obj, msg):
    global message
    print("Topic Rx:" + msg.topic + " QoS:" + str(msg.qos) + "\n")
    clean_json = ast.literal_eval(msg.payload)
    print ("Payload: ")
    # import pdb; pdb.set_trace()
    print json.dumps(clean_json , indent=4, sort_keys=True)
    # message = msg.payload
    # This is where we will develop client connect to  Azure IoT Suite
    mqttc.publish(cloudTopic,msg.payload, 1);
```
### Step C4: MQTT Listener startup Main
```python
print('Establish MQTT Broker Connection')
# Setup to listen on topic`
mqttc = paho.Client()
mqttc.on_connect = on_connect
mqttc.on_message = on_message
mqttc.connect(localBroker, localPort, localTimeOut)
print('MQTT Listener Loop <ctl-C> to break...')
mqttc.loop_forever()
```

### Step C5: Create an MQTT Test Client (part 1)
```python
#!/usr/bin/python
import time
import socket
import paho.mqtt.client as paho
from sense import PiSenseHat

myHostname = 'iot8e3c'

localBroker = "iot8e3c"		# Local MQTT broker
localPort   = 1883			# Local MQTT port
localUser   = "pi"			# Local MQTT user
localPass = "raspberry"		# Local MQTT password
localTopic = "iot/sensor"	# Local MQTT topic to monitor
localTimeOut = 120			# Local MQTT session timeout

# The callback for when a CONNACK message is received from the broker.
def on_connect(client, userdata, flags, rc):
    print("CONNACK received with code %d." % (rc))

# The callback for when a PUBLISH message is received from the broker.
def on_message(client, userdata, msg):
    print (string.split(msg.payload))

# display one row of blue LEDs (just for fun)
def displayLine(row):
    blue = (0, 0, 255)
    for i in range(0,8):
        x = i % 8
        y = (i / 8) + row
        # print("set pixel x:%d y:%d" % (x,y))
        pi_sense.set_pixel(x,y,blue)
        time.sleep(0.02)

```
### Step C6: Create an MQTT Test Client (part 2)
```python
# Create a sense-hat object
pi_sense = PiSenseHat()
print('PI SenseHat Object Created')

# Get hostname
## Get my machine hostname
# import pdb; pdb.set_trace()
if socket.gethostname().find('.') >= 0:
    hostname=socket.gethostname()
else:
    hostname=socket.gethostbyaddr(socket.gethostname())[0]

# Setup to Publish Sensor Data
mqttc = paho.Client()
mqttc.on_connect = on_connect
mqttc.on_message = on_message
mqttc.connect(localBroker, localPort, localTimeOut)

# initialize message dictionary
msg = {'topic':localTopic, 'payload':"", 'qos':0, 'retain':False }

pi_sense.clear_display()
# loop
print('Getting Sensor Data')
for i in range(1,9):
    print("SensorSet[%d]" % (i))
    displayLine(i-1)
    sensors = pi_sense.getAllSensors()

    sensors['host'] = hostname
    msg['payload'] = str(sensors)
    print("msg["+str(i)+"]:"+msg['payload'])

#   publish(topic, payload=None, qos=0, retain=False)
    mqttc.publish('iot/test', msg['payload'], 1)
    time.sleep(2.0)

print('End of MQTT Messages')
quit()
```

### Step C6: Create an MQTT Test Client (part 2)
```python

```

### Step C8: Modify our WebApp main.py setup
First, copy all of the code from Lab6 into Lab8.  Then make the following minor
changes to your ```main.py```.  Later, we will change the ```localBroker``` variable
to point to whatever platform is hosting Mosquitto the MQTT broker.
```python
# MQTT Configuration for local network
localBroker = "iot8e3c"		# Local MQTT broker
localPort   = 1883			# Local MQTT port
localUser   = "pi"			# Local MQTT user
localPass = "raspberry"		# Local MQTT password
localTopic = "iot/sensor"	# Local MQTT topic to monitor
localTimeOut = 120			# Local MQTT session timeout

# Setup to Publish Sensor Data
mqttc = paho.Client()
mqttc.on_connect = on_connect
mqttc.on_message = on_message
mqttc.connect(localBroker, localPort, localTimeOut)
```

### Step C9: Modify our WebApp main.py SSE route and method
```python
# =========================== Endpoint: /myData ===============================
# read the sensor values by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            data_payload = get_sensor_values()
            yield('data: {0}\n\n'.format(data_payload))
            print("MQTT Topic:"+localTopic, data_payload)
            mqttc.publish(localTopic,data_payload)
            time.sleep(2.0)
    return Response(get_values(), mimetype='text/event-stream')
# ============================== API Routes ===================================
```


### Step C10: Modify Sense.py to include LED display

Add the following two functions from line 24 on the sense.py from Lab6
```python
    # pixel display
    def set_pixel(self,x,y,color):
    # red = (255, 0, 0)
    # green = (0, 255, 0)
    # blue = (0, 0, 255)
        self.sense.set_pixel(x, y, color)

    # clear pixel display
    def clear_display(self):
        self.sense.clear()
```


# STEPS TO MODIFY in ```main.py```
### STEP C11: Initial Import structure
```python 
#!/usr/bin/python
import time
import datetime
from sense import PiSenseHat
import paho.mqtt.client as paho
from flask import *
```

### STEP C12: MQTT Callbacks
```python
# ============================= MQTT Callbacks ================================
# The callback for when a CONNACK message is received from the broker.
def on_connect(client, userdata, flags, rc):
    print("CONNACK received with code %d." % (rc))

# The callback for when a PUBLISH message is received from the broker.
def on_message(client, userdata, msg):
    print (string.split(msg.payload))
# ============================= MQTT Callbacks ================================
```
### STEP C13: LOGIN CONSTANTS and SETUP TO PUBLISH
```python
# MQTT Configuration for local network
localBroker = "iot8e3c"		# Local MQTT broker
localPort   = 1883			# Local MQTT port
localUser   = "pi"			# Local MQTT user
localPass = "raspberry"		# Local MQTT password
localTopic = "iot/sensor"	# Local MQTT topic to monitor
localTimeOut = 120			# Local MQTT session timeout

# Setup to Publish Sensor Data
mqttc = paho.Client()
mqttc.on_connect = on_connect
mqttc.on_message = on_message
mqttc.connect(localBroker, localPort, localTimeOut)
```
### STEP C14: Addition of Publish in our SSE Loop
```python
# =========================== Endpoint: /myData ===============================
# read the sensor values by GET method from curl for example
# curl http://iot8e3c:5000/myData
# -----------------------------------------------------------------------------
@app.route('/myData')
def myData():
    def get_values():
        while True:
            # return the yield results on each loop, but never exits while loop
            data_payload = get_sensor_values()
            yield('data: {0}\n\n'.format(data_payload))
            print("MQTT Topic:"+localTopic, str(data_payload))
            mqttc.publish(localTopic,str(data_payload))
            time.sleep(2.0)
    return Response(get_values(), mimetype='text/event-stream')
```

[PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartD.md) Test Multiple Pub/Sub Connections

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)

## Part D - Test Multiple Pub/Sub Connections
**Synopsis:** In this part, we will test multiple in class nodes against the
MQTT gateway device.  We will also set up several gate way device and cross test.

## Objectives
* Assign hostnames for each gateway device
* Ensure Mosquitto is started and running
* Ensure MQTT.fx is started and attached/connected to the Mosquitto server.
* Ensure Publish and observe both MQTT.fx subscriptions, listener and mosquitto_pub

### Step D1: Assign Hostnames
```sh

```    
### Step D2: Ensure Mosquitto is started and running
```sh
pi$ ps aux | grep mosq |
```    
### Step D3: Ensure MQTT.fx is connected to Mosquitto


### Step D4: Publish and Subscribe!


[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartC.md) Create MQTT Python Test Code

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab8

**Synopsis:** For this lab we will study gateways and examine the Message Queue
Telemetry Transport (MQTT) protocol in preparation for our last class where we 
create a connection to an instructor led Microsoft Azure IoT Suite connection.

### Objectives
* Install MQTT Message Broker
* Install the MQTT Client Tool (MQTT.fx)
* Create MQTT Test code, Sensor Sim and Update SenseHat Web main.py
* Testing Multiple Pub/Sub Connections

The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartA.md) Install MQTT Message Broker
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartB.md) Install MQTT Client Tool MQTT.fx
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartC.md) Create MQTT Python Test Code
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab8/PartD.md) Test Multiple Pub/Sub Connections

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/setup.md)

## Part A - Install MQTT on Azure Ubuntu VM
**Synopsis:** In this part, we will install and test MQTT on an Azure Ubuntu Virtual Machine (VM).

## Objectives
* Provision an Azure Ubuntu VM as aan MQTT Broker
* Test the MQTT Pub/Sub Capability
* Setup basic Password Authentication to the MQTT Broker and Test
* Set up SSL Certificates and Test

### Step A1: Provision an Azure VM to act as an MQTT Broker
From Azure Portal Choose an Ubuntu 16 Compute VM.
![Ubuntu 16.04 LTS VM](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/AzureCreateVM.png)

Get SSH public key from development host machine (from the ~/.ssh/id_rsa.pub file created with the ssh-keygen comamnd).

Note: if you have not created a public key please log into a linux shell or Git Bash CLI and perform the following:
```sh
host$ cd ~/.ssh
host$ ssh-keygen        # <= just hit enter for all questions
host$ cat id_rsa.pub    # <= copy the SSH public key to your clipboard
```  

![Ubuntu SSH Keys](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/AzureVM-SSHKeys.png)

### Step A2: Log In & Install Libraries and Mosquitto MQTT Broker
There is a great tutorial found at Digital Ocean concerning installing and testing both
password only and encrypted (SSL) communications between a MQTT client and
MQTT broker (server).  [Digital Ocean MQTT Tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-the-mosquitto-mqtt-messaging-broker-on-ubuntu-16-04)

We will adapt that tutorial for our Azure VM example.
```sh
AzureVM$ sudo apt-get update
AzureVM$ sudo apt-get install -y mosquitto mosquitto-clients
AzureVM$ $ ps aux | grep mos
mosquit+  3103  0.0  0.1  35828  4540 ?        S    21:42   0:00 /usr/sbin/mosquitto -c /etc/mosquitto/mosquitto.conf
sdame     3165  0.0  0.0  12944  1084 pts/0    S+   21:43   0:00 grep --color=auto mos
```
Open a subscriber terminal for testing
```sh
AzureVM$ $ mosquitto_sub -h localhost -t test
=> hello MQTT world!
```

Open a publisher terminal for publishing a test message
```sh
AzureVM$ $ mosquitto_pub -h localhost -t test -m "hello MQTT world!"
```

### Step A3: Establish MQTT Password Access on Port 1883
In this step we need to both edit the MQTT configuration file to require a
username and password as well as open a port in the network security resource.

Add a new configuration file in /etc/mosquitto/conf.d (then edit)
```shsudo touch /etc/mosquitto/conf.d/mosquitto.conf
AzureVM$ sudo vim /etc/mosquitto/conf.d/mosquitto.conf
=>...
user mo
listener 1883
allow_anonymous false
password_file /etc/mosquitto/passwd
```

Setup a username ("mo" and password "squitto")

```sh
AzureVM$ sudo mosquitto_passwd -c /etc/mosquitto/passwd mo
Password: ******* (<= "squitto")
Reenter password: ******** (<= "squitto")

```


[PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartB.md)  Install MQTT Client Tool MQTT.fx

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/setup.md)
[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/setup.md)

## Part B - Create and Configure Devices for Azure IoT Hub
**Synopsis:** In this part, we will configure Azure IoT Hub.

## Objectives
* Provision an Azure IoT Hub

### Step B1: Create Azure IoT Hub
From Azure Portal Choose an Ubuntu 16 Compute VM.
![Azure IoT Hub]()

[npm package iothub explorer](https://www.npmjs.com/package/iothub-explorer)

[iothub-explorer https://github.com/Azure/iothub-explorer/blob/master/readme.md

### Step B2: Setup iothub-explorer
```sh
pi$ sudo apt-get update
pi$ sudo apt-get install -y nodejs
pi$ sudo apt install -y npm
pi$ sudo npm install -g iothub-explorer
pi$ iothub-explorer login "HostName=<<host>>;SharedAccessKeyName=service;SharedAccessKey=<<key>>"
Session started, expires on Sun Mar 05 2017 18:20:05 GMT-0800 (PST)
Session file: /home/pi/.iothub-explorer

https://github.com/Azure/azure-iot-sdk-python
git clone --recursive https://github.com/Azure/azure-iot-sdk-python.git

 => looking down in the service samples directory there is a iothub_messaging_sample.py
 => the standard ConnectionString is not parseable by this current code because it contains

AzureVM$ iothub-explorer list | grep foo
 deviceId:                   foo
 connectionString:           HostName=Iot110-hub.azure-devices.net;DeviceId=foo;SharedAccessKey=PyOxlqIITtqi3K7Jypw9Kg3vWgvMveJCbqSh0O+Q6c0=

 => DeviceId=foo  vs. SharedAccessKeyName=foo ???
AzureVM$ python iothub_messaging_sample.py -c "HostName=Iot110-hub.azure-devices.net;SharedAccessKeyName=foo;SharedAccessKey=PyOxlqIITtqi3K7Jypw9Kg3vWgvMveJCbqSh0O+Q6c0=" -d foo

iothub-explorer send foo 'hello9994' --ack=full

iothub-explorer monitor-feedback foo

iothub-explorer simulate-device --protocol=mqtt foo --receive




python iothub_message_demo.py -c "HostName=Iot110-hub.azure-devices.net;SharedAccessKeyName=device;SharedAccessKey=c6Glzei6IkM42CF9/ZuVknH/7OqbC+LaQVe4k7JaxO0=" -d foo


```

```sh
AzureVM$ sudo ln -s /usr/bin/nodejs /usr/bin/node
```

### Step B3: Login to IoT Hub via iothub-explorer
```sh
iothub-explorer login "HostName=<<host>>;SharedAccessKeyName=service;SharedAccessKey=<<key>>"
```

### Step B4: Create device <foo> via iothub-explorer
```sh
iothub-explorer create foo
```

### Step B5: Create device <foo> via iothub-explorer
```sh
iothub-explorer create foo
```

### Step B6: List all devices on IoT Hub via iothub-explorer
```sh
iothub-explorer list

iothub-explorer list |  grep foo
iothub-explorer list |  grep bar

```

### Step B7: Monitor Events for Device to Cloud (D2C)
```sh
iothub-explorer monitor-events foo --login "HostName=Iot110-hub.azure-devices.net;SharedAccessKeyName=iothubowner;SharedAccessKey=c6Glzei6IkM42CF9/ZuVknH/7OqbC+LaQVe4k7JaxO0="
```

### Step B8: Send Simulated Message from Device to Cloud (D2C)
```sh
iothub-explorer simulate-device foo --send "{deviceId: 'foo', windSpeed: 10.671534826979041 }"
```

### Step B9:


[PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartB.md)  TBD

[LAB8 INDEX](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/setup.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up Lab9

**Synopsis:** For this lab we will extend the introduction to MQTT and IoT edge
devices by connecting to the UW/instructor provisioned Microsoft Azure cloud
system and the Azure IoT Suite.  We will perform manual connections to an MQTT
Broker on the Azure cloud, provision security certificates, connect to the Azure
IoT Hub, perform a basic Stream Analytics function and Utilize the Power BI
visualization toolkit to graph data from multiple IoT devices.

### Objectives
* Install MQTT Message Broker on an Azure Ubuntu VM
* Generate Certificates for IoT End Devices or Gateways
* Connect our IoT Gateway code to Azure IoT Hub
* Stream data through Stream Analytics
* Perform Visualization using Power BI


The various steps of this lab are summarized as:
* [PART A](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartA.md) Install MQTT Message Broker on an Azure Ubuntu VM
* [PART B](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartB.md) Generate Certificates for IoT End Devices or Gateways
* [PART C](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartC.md) Create MQTT Python Test Code
* [PART D](https://gitlab.com/iot110/iot110-student/blob/master/Labs/Lab9/PartD.md) Test Multiple Pub/Sub Connections

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)

## Setting up RPi3 for the IoT110 Class

### Summary of Setup Steps
* [OPT] Download OS from RaspberryPi Foundation
* ( 1) Set Hardcoded Screen Resolution for mini HDMI monitor
* ( 2) Expand the filesystem
* ( 3) Setup WiFi connection
* ( 4) Establish a Command Line Interface (CLI)
* ( 5) Ensure a US Keyboard mapping
* ( 6) Set up a hostname unique for your PI (using its last 4 digits MAC address for wlan)
* ( 7) Enable Serial Ports and GPIO for Labs
* ( 8) Set up local hostname resolution for the IOT class (or home) network
* ( 9) SSH -> iot1234
* (10) Mapping PI filesystem into host's
* (11) Update OS and install a few utilities and check versions
* (12) Set up a Project for this Class in GITLAB and push ssh key(s)

<hr>
### [OPTIONAL] Downloading and burning a new image (if you wish to have the latest OS or burn your own image)
[RASPBIAN JESSIE WITH PIXEL](https://www.raspberrypi.org/downloads/raspbian/)
Image with PIXEL desktop based on Debian Jessie

[RASPBIAN JESSIE LITE](https://www.raspberrypi.org/downloads/raspbian/)
Minimal image based on Debian Jessie

[Optional Configuration Link](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-2-first-time-configuration/using-the-whole-sd-card?view=all)
<hr>
### STEP 1: Mini Display 480x800 pixels
This display will not boot a screen on default.  The config.txt file must be
modified according to the instructions on Adafruit.  (config.txt is located on the SD card and you must insert the card into your host computer to edit)
[Display Config Changes](https://learn.adafruit.com/adafruit-5-800x480-tft-hdmi-monitor-touchscreen-backpack/raspberry-pi-config)
In case that site goes down, here's a summary of the changes in config.txt:
```
# uncomment if hdmi display is not detected and composite is being output
hdmi_force_hotplug=1

# uncomment to force a specific HDMI mode (here we are forcing 800x480!)
hdmi_group=2
hdmi_mode=87
hdmi_cvt=800 480 60 6 0 0 0
```
<hr>
#### [GENERAL INFO] Check the Raspberry PI Settings/Preferences
Start > Preferences > Raspberry Pi Configuration
![Raspberry Pi Settings](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/Preferences.png)

<hr>

### STEP 2: Expanding Filesystem
**Objective:** The default SD card operating systems shipped out of the box
often are not expanded to the full extent of the size of the SD card.  This is
also true if you have downloaded an operating system image (see above) and
burned it onto the card.  The image size may only be 1-2GB but the card might be
8GB to 64GB for example.  We therefore will want to have ALL of the SD card
file system available to the RPi. It is very important to do this at the **VERY
BEGINNING OF SETUP** otherwise you may find yourself out of disk space and in a
"bricked" state.  In this case, you will need to perform the OPTIONAL step above
and start over with a fresh image install.<br><br>
![Expand File System](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/expand.png)

After expanding and rebooting as required, open a terminal and check to ensure
that the filesystem was indeed expanded.<br><br>
![File System Size Check](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/df_dash_h.png)
<br>
<hr>
### STEP 3: Setup WiFi Connection
Apple Airport access points have been configured for our IoT classroom.  There
are 2 access points because they each have a limit of 50 client connections.  
To attempt to keep things simple we will join to only one of the access points
(UW-IoT110-R) until we either have:<br>
a) run out of 50 client connections<br>
  or<br>
b) we have a failure on one access point.<br>
*(Being airplane engineers we tend to think in terms of redundancy!) (grin)*<br>

Using the mouse and hovering over the WiFi connection ICON, select SSID and
enter the password given below:<br>
Airports have SSIDs of UW-IoT110-R (primary) and UW-IoT110-L (secondary).  
Password: **piIoT110**  (Note: "I" in IoT is  "capital I" and not "capital L")
<br><br>
![WiFi Settings Panel](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/SSID.png)
<br>
<hr>
### STEP 4: Command line shell ###
For MacOSX or Linux users, just use the normal "terminal" for your Command Line
Interface (CLI).<br>

For Windows users, it maybe best to download the GIT Bash tool (git is built
into Linux and MacOSX terminal shells).
[Download GIT](https://git-scm.com/downloads)

NOTE: For the following command line entries we use the following to
indicate which machine you are on.
```
pi$  => this is a command on the RPi3

host$ => this is a command on your development host
```

#### Check to see if connected to the public Internet
```
pi$ ping google.com
```

#### Determine IP address of RPi
```
pi$ ifconfig | grep "inet addr"
=> inet addr:192.168.10.19  Bcast:192.168.1.255  Mask:255.255.255.0
```

### Step 5: Ensure a US Keyboard Mapping
![Keyboard Setting](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/Keyboard.png)


### Step 6: Setup a unique hostname based on wlan MAC
```
pi$ ifconfig | grep wlan0  
=> wlan0     Link encap:Ethernet  HWaddr b8:27:eb:e9:12:34  
=> choose the last 4 digits of the MAC => [1234]

pi$ sudo vi /etc/hostname

=> remove current hostname and replace with "iot1234"
=> using the [HWaddr] from above network queries
```
Alternatively the hostname can be set from the Preferences panel.
![Hostname Preferences UI](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/hostname.png)

### Step 7: Enable I2C Serial Port (and GPIO if Pixel OS) for Labs
![Raspberry Pi I/O Port Settings](https://gitlab.com/iot110/iot110-student/raw/master/Resources/Images/interfaces.png)

#### Reboot
```
pi$ reboot
```

<hr>
### STEP 8: Using Hostname Resolution on Network
```
// start the avahi-daemon network service
pi$ systemctl status avahi-daemon
  => Verify that the hostname matches the name changed to above
Loaded: loaded (/lib/systemd/system/avahi-daemon.service; enabled)
Active: active (running) since Sun 2016-11-13 23:15:20 UTC; 15min ago
Main PID: 438 (avahi-daemon)
  Status: "avahi-daemon 0.6.31 starting up."
  CGroup: /system.slice/avahi-daemon.service
          â”œâ”€438 avahi-daemon: running [iot1234.local]
          â””â”€465 avahi-daemon: chroot helper

host$ ping iot1234
PING iot1234.home (192.168.10.19): 56 data bytes
64 bytes from 192.168.10.19: icmp_seq=0 ttl=64 time=10.863 ms
64 bytes from 192.168.10.19: icmp_seq=1 ttl=64 time=7.657 ms
64 bytes from 192.168.10.19: icmp_seq=2 ttl=64 time=7.024 ms      

```
<hr>
### STEP 9: Setting up SSH
**Objective:** Establishing ssh connection is the most universal way to connect
two computers together over a network (local or global).  This also automatically
provides public key infrastructure (PKI) security which is the standard for
Internet Security.  Establishing SSH keys allows for password free log in
between systems which is not only convenient (when a trust is established) but
essential when automating connectivity --as we will be doing for our class.  We
will be using SSH to routinely log into our machines as well as utilizing a
capbility known as SSHFS (i.e. File System mapping over SSH).

```
// ------- RPi KEY SETUP ----------
// log into RPi iot1234 (with password => "raspberry")
host$ ssh pi@iot1234  // answer yes to the one time prompt for host signature
                            // passwd default: "raspberry"
pi$ cd .ssh                 // change dir to .ssh if it exists, mkdir if it doesn't
pi$ ssh-keygen              // generate an ssh key (RSA)
=> Enter file in which to save the key (/home/pi/.ssh/id_rsa):
                            // hit <enter> 3 times

pi$ cp id_rsa.pub  id_rsa_iot1234.pub
pi$ exit                    // success! now exit and set up an SSH key for host
```

**(IF YOU ALREADY HAVE AN SSH HOST KEY PLEASE SKIP THE HOST PORTION)**

```
// ------- HOST KEY SETUP ----------
// generatate (or use) a ssh key on the host (IF YOU ALREADY HAVE A KEY
host$ cd ~/.ssh
host$ ssh-keygen            
=> Enter file in which to save the key (/home/pi/.ssh/id_rsa):
                            // hit <enter> 3 times

host$ cp id_rsa.pub id_rsa_XYZ.pub  // Use a unique XYZ id from your host machine
host$ scp id_rsa_XYZ.pub pi@iot1234:.ssh
host$ ssh pi@iot1234                // enter passwd (for the last time!)

// install the ssh host key on iot708c
pi$ cd .ssh
pi$ cat id_rsa_XYZ.pub >> authorized_keys
pi$ exit  

// test the ssh key
host$ ssh pi@iot1234  // should be passwd free now!
pi$ exit  
```
<hr>
### STEP 10: Mapping PI filesystem into host's
**Objective:** It is *very convenient* to map the RPi's filesystem into your
development host as if it is just another folder on your host.  This allows the
use of native and powerful code friendly editors (e.g. Atom or Sublime) in which
to edit source code.  Because the RPi's file system is mapped there is no need
to transfer code back and forth to the RPi.  In Linux-speak mapping a target
filesystem like this is known as *mounting the file system*.

Create a folder on the RPi under ```Documents/``` called ```GIT_REPOS``` 
(e.g. Documents/GIT_REPOS)

Must install sshfs capability in order to mount file system then...
#### sshfs for MacOSX
[FUSE for macOS](https://osxfuse.github.io/)   // install **BOTH** fuse and sshfs pkgs

Create directories on development host to mount each PI (e.g. PI_MOUNT_1234)
then mount them using sshfs.

``` sh
host$ sshfs pi@iot1234:Documents/GIT_REPOS PI_MOUNT_1234/ -C

```

disconnect from the PI file systems
```
host$ umount PI_MOUNT_1234/
```

#### sshfs for Windows 7/8/10
[SSHFS Win10](https://igikorn.com/sshfs-windows-10/)   // install Win sshfs pkg

Follow the instructions to set up a GUI based SSHFS capability for Windows
development hosts.

<hr>
### STEP 11: Update OS and install a few utilities and check versions
**Objective:** It is always a good idea to keep Linux systems such as the
Debian OS (Raspbian) updated with the latest improvements coming from the large
open source community such as enjoyed by the Raspberry Pi platform.  As a final
stage of our PI setup we will make sure we have an updated OS.

``` bash
host$ ssh pi@iot1234

pi$ sudo apt install rpi-update
pi$ sudo rpi-update
pi$ uname -a

```
<hr>
### STEP 12: Setting up GIT Repositories
**Objective:** We will be making use of GIT (Distributed Software Version Control)
to ensure that each student's projects are safely backed up and under version
control.
* create an account on GITLAB (or other GIT services if you have a preference)
* log in and create a project called iot-110
* clone this project into a folder on your HOST (e.g. Documents/GIT_REPOS)
* clone this project into a folder on your PI (e.g. Documents/GIT_REPOS)

[IOT STUDENT HOME](https://gitlab.com/iot110/iot110-student/blob/master/README.md)
