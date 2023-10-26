Last login: Thu Oct 26 07:31:13 on console
pl259351@7118L06 ~ % ssh pi@192.168.1.26
pi@192.168.1.26's password: 
Linux raspberrypi 5.10.103-v7+ #1529 SMP Tue Mar 8 12:21:37 GMT 2022 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Wed Oct 25 13:43:23 2023 from 192.168.1.16
pi@raspberrypi:~ $ cd
pi@raspberrypi:~ $ ls -a
.              bcm2835-1.70         Motor_Driver_HAT_Code
..             bcm2835-1.70.tar.gz  Motor_Driver_HAT_Code.7z
.bash_history  code                 .profile
.bash_logout   .gnupg               wiringpi-latest.deb
.bashrc        .local
pi@raspberrypi:~ $ cd code
pi@raspberrypi:~/code $ ls -a
.  ..  main.py  .main.py.swp
pi@raspberrypi:~/code $ nano main.py
pi@raspberrypi:~/code $ sudo python3 main.py
pi@raspberrypi:~/code $ delete main.py
-bash: delete: command not found
pi@raspberrypi:~/code $ rm main.py
pi@raspberrypi:~/code $ ls -a
.  ..
pi@raspberrypi:~/code $ cd
pi@raspberrypi:~ $ rm code
rm: cannot remove 'code': Is a directory
pi@raspberrypi:~ $ sudo rm code
rm: cannot remove 'code': Is a directory
pi@raspberrypi:~ $ sudo rmdir code
pi@raspberrypi:~ $ git clone https://github.com/DylanDeSchryver/moverpi.git
-bash: git: command not found
pi@raspberrypi:~ $ sudo apt-get update
Get:1 http://archive.raspberrypi.org/debian buster InRelease [32.6 kB]
Get:2 http://raspbian.raspberrypi.org/raspbian buster InRelease [15.0 kB]
Get:3 http://raspbian.raspberrypi.org/raspbian buster/main armhf Packages [13.0 MB]
Get:4 http://archive.raspberrypi.org/debian buster/main armhf Packages [400 kB]
Fetched 13.5 MB in 13s (1,045 kB/s)                                            
Reading package lists... Done
pi@raspberrypi:~ $ sudo apt-get install git
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  git-man libcurl3-gnutls liberror-perl
Suggested packages:
  git-daemon-run | git-daemon-sysvinit git-doc git-el git-email git-gui gitk
  gitweb git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  git git-man libcurl3-gnutls liberror-perl
0 upgraded, 4 newly installed, 0 to remove and 0 not upgraded.
Need to get 6,134 kB of archives.
After this operation, 33.0 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://mirror.umd.edu/raspbian/raspbian buster/main armhf libcurl3-gnutls armhf 7.64.0-4+deb10u7 [293 kB]
Get:2 http://mirror.umd.edu/raspbian/raspbian buster/main armhf liberror-perl all 0.17027-2 [30.9 kB]
Get:3 http://mirror.umd.edu/raspbian/raspbian buster/main armhf git-man all 1:2.20.1-2+deb10u8 [1,623 kB]
Get:4 http://mirror.umd.edu/raspbian/raspbian buster/main armhf git armhf 1:2.20.1-2+deb10u8 [4,187 kB]
Fetched 6,134 kB in 8s (746 kB/s)                                              
Selecting previously unselected package libcurl3-gnutls:armhf.
(Reading database ... 43450 files and directories currently installed.)
Preparing to unpack .../libcurl3-gnutls_7.64.0-4+deb10u7_armhf.deb ...
Unpacking libcurl3-gnutls:armhf (7.64.0-4+deb10u7) ...
Selecting previously unselected package liberror-perl.
Preparing to unpack .../liberror-perl_0.17027-2_all.deb ...
Unpacking liberror-perl (0.17027-2) ...
Selecting previously unselected package git-man.
Preparing to unpack .../git-man_1%3a2.20.1-2+deb10u8_all.deb ...
Unpacking git-man (1:2.20.1-2+deb10u8) ...
Selecting previously unselected package git.
Preparing to unpack .../git_1%3a2.20.1-2+deb10u8_armhf.deb ...
Unpacking git (1:2.20.1-2+deb10u8) ...
Setting up libcurl3-gnutls:armhf (7.64.0-4+deb10u7) ...
Setting up liberror-perl (0.17027-2) ...
Setting up git-man (1:2.20.1-2+deb10u8) ...
Setting up git (1:2.20.1-2+deb10u8) ...
Processing triggers for man-db (2.8.5-2) ...
Processing triggers for libc-bin (2.28-10+rpt2+rpi1+deb10u2) ...
pi@raspberrypi:~ $ git --version
git version 2.20.1
pi@raspberrypi:~ $ git clone https://github.com/DylanDeSchryver/moverpi.git
Cloning into 'moverpi'...
warning: You appear to have cloned an empty repository.
pi@raspberrypi:~ $ cd moverpi
pi@raspberrypi:~/moverpi $ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/DylanDeSchryver/moverpi
 * [new branch]      main       -> origin/main
Your configuration specifies to merge with the ref 'refs/heads/master'
from the remote, but no such ref was fetched.
pi@raspberrypi:~/moverpi $ ls -a
.  ..  .git
pi@raspberrypi:~/moverpi $ cd
pi@raspberrypi:~ $ rmdir moverpi
rmdir: failed to remove 'moverpi': Directory not empty
pi@raspberrypi:~ $ sudo rmdir moverpi
rmdir: failed to remove 'moverpi': Directory not empty
pi@raspberrypi:~ $ rm -ir moverpi
rm: descend into directory 'moverpi'? y
rm: descend into directory 'moverpi/.git'? y
rm: remove regular file 'moverpi/.git/description'? y
rm: remove directory 'moverpi/.git/branches'? y
rm: descend into directory 'moverpi/.git/refs'? y
rm: remove directory 'moverpi/.git/refs/heads'? y
rm: descend into directory 'moverpi/.git/refs/remotes'? y
rm: descend into directory 'moverpi/.git/refs/remotes/origin'? y
rm: remove regular file 'moverpi/.git/refs/remotes/origin/main'? y
rm: remove directory 'moverpi/.git/refs/remotes/origin'? y
rm: remove directory 'moverpi/.git/refs/remotes'? y
rm: remove directory 'moverpi/.git/refs/tags'? y
rm: remove directory 'moverpi/.git/refs'? y
rm: remove regular file 'moverpi/.git/config'? y
rm: descend into directory 'moverpi/.git/hooks'? y
rm: remove regular file 'moverpi/.git/hooks/update.sample'? 
rm: remove regular file 'moverpi/.git/hooks/post-update.sample'? 
rm: remove regular file 'moverpi/.git/hooks/applypatch-msg.sample'? 
rm: remove regular file 'moverpi/.git/hooks/pre-applypatch.sample'? 
rm: remove regular file 'moverpi/.git/hooks/pre-commit.sample'? 
rm: remove regular file 'moverpi/.git/hooks/prepare-commit-msg.sample'? 
rm: remove regular file 'moverpi/.git/hooks/pre-receive.sample'? 
rm: remove regular file 'moverpi/.git/hooks/fsmonitor-watchman.sample'? 
rm: remove regular file 'moverpi/.git/hooks/pre-push.sample'? 
rm: remove regular file 'moverpi/.git/hooks/pre-rebase.sample'? 
rm: remove regular file 'moverpi/.git/hooks/commit-msg.sample'? 
rm: remove directory 'moverpi/.git/hooks'? 
rm: remove regular file 'moverpi/.git/HEAD'? 
rm: descend into directory 'moverpi/.git/logs'? 
rm: descend into directory 'moverpi/.git/objects'? 
rm: descend into directory 'moverpi/.git/info'? 
rm: remove regular file 'moverpi/.git/FETCH_HEAD'? 
pi@raspberrypi:~ $ 
pi@raspberrypi:~ $ ls -a
.              bcm2835-1.70           Motor_Driver_HAT_Code.7z
..             bcm2835-1.70.tar.gz    moverpi
.bash_history  .gnupg                 .profile
.bash_logout   .local                 wiringpi-latest.deb
.bashrc        Motor_Driver_HAT_Code
pi@raspberrypi:~ $ rmdir moverpi
rmdir: failed to remove 'moverpi': Directory not empty
pi@raspberrypi:~ $ cd moverpi
pi@raspberrypi:~/moverpi $ ls -a
.  ..  .git
pi@raspberrypi:~/moverpi $ rm .git
rm: cannot remove '.git': Is a directory
pi@raspberrypi:~/moverpi $ cd .git
pi@raspberrypi:~/moverpi/.git $ ls -a
.  ..  FETCH_HEAD  HEAD  hooks  info  logs  objects
pi@raspberrypi:~/moverpi/.git $ cd
pi@raspberrypi:~ $ cd
pi@raspberrypi:~ $ rm -rf lampp
pi@raspberrypi:~ $ rm -rf moverpi
pi@raspberrypi:~ $ ls -a
.              bcm2835-1.70           Motor_Driver_HAT_Code.7z
..             bcm2835-1.70.tar.gz    .profile
.bash_history  .gnupg                 wiringpi-latest.deb
.bash_logout   .local
.bashrc        Motor_Driver_HAT_Code
pi@raspberrypi:~ $ git clone https://github.com/DylanDeSchryver/moverpi.git
Cloning into 'moverpi'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
pi@raspberrypi:~ $ cd moverpi
pi@raspberrypi:~/moverpi $ git pull
Already up to date.
pi@raspberrypi:~/moverpi $ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/DylanDeSchryver/moverpi
   682379e..865a56c  main       -> origin/main
Updating 682379e..865a56c
Fast-forward
 main.py | 1 +
 1 file changed, 1 insertion(+)
pi@raspberrypi:~/moverpi $ ls -a
.  ..  .git  main.py
pi@raspberrypi:~/moverpi $ sudo pip3 install adafruit-circuitpython-motorkit
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Requirement already satisfied: adafruit-circuitpython-motorkit in /usr/local/lib/python3.7/dist-packages (1.6.13)
Requirement already satisfied: adafruit-circuitpython-pca9685 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (3.4.11)
Requirement already satisfied: adafruit-circuitpython-motor in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (3.4.12)
Requirement already satisfied: Adafruit-Blinka in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (8.23.0)
Requirement already satisfied: adafruit-circuitpython-busdevice in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (5.2.6)
Requirement already satisfied: adafruit-circuitpython-register in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (1.9.17)
Requirement already satisfied: adafruit-circuitpython-typing>=1.5.0 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motor->adafruit-circuitpython-motorkit) (1.9.5)
Requirement already satisfied: Adafruit-PlatformDetect>=3.52.0 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (3.53.0)
Requirement already satisfied: Adafruit-PureIO>=1.1.7 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (1.1.11)
Requirement already satisfied: pyftdi>=0.40.0 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (0.54.0)
Requirement already satisfied: typing-extensions~=4.0 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-register->adafruit-circuitpython-motorkit) (4.7.1)
Requirement already satisfied: adafruit-circuitpython-requests in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-typing>=1.5.0->adafruit-circuitpython-motor->adafruit-circuitpython-motorkit) (2.0.2)
Requirement already satisfied: pyusb!=1.2.0,>=1.0.0 in /usr/local/lib/python3.7/dist-packages (from pyftdi>=0.40.0->Adafruit-Blinka->adafruit-circuitpython-motorkit) (1.2.1)
Requirement already satisfied: pyserial>=3.0 in /usr/lib/python3/dist-packages (from pyftdi>=0.40.0->Adafruit-Blinka->adafruit-circuitpython-motorkit) (3.4)
pi@raspberrypi:~/moverpi $ ls -a
.  ..  .git  main.py
pi@raspberrypi:~/moverpi $ cd
pi@raspberrypi:~ $ ls -a
.              bcm2835-1.70           Motor_Driver_HAT_Code.7z
..             bcm2835-1.70.tar.gz    moverpi
.bash_history  .gnupg                 .profile
.bash_logout   .local                 wiringpi-latest.deb
.bashrc        Motor_Driver_HAT_Code
pi@raspberrypi:~ $ cd
pi@raspberrypi:~ $ sudo pip3 install adafruit-circuitpython-motorkit
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Requirement already satisfied: adafruit-circuitpython-motorkit in /usr/local/lib/python3.7/dist-packages (1.6.13)
Requirement already satisfied: adafruit-circuitpython-register in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (1.9.17)
Requirement already satisfied: adafruit-circuitpython-pca9685 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (3.4.11)
Requirement already satisfied: adafruit-circuitpython-busdevice in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (5.2.6)
Requirement already satisfied: Adafruit-Blinka in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (8.23.0)
Requirement already satisfied: adafruit-circuitpython-motor in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-motorkit) (3.4.12)
Requirement already satisfied: adafruit-circuitpython-typing==1.*,>=1.3.1 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-register->adafruit-circuitpython-motorkit) (1.9.5)
Requirement already satisfied: typing-extensions~=4.0 in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-register->adafruit-circuitpython-motorkit) (4.7.1)
Requirement already satisfied: Adafruit-PureIO>=1.1.7 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (1.1.11)
Requirement already satisfied: pyftdi>=0.40.0 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (0.54.0)
Requirement already satisfied: Adafruit-PlatformDetect>=3.52.0 in /usr/local/lib/python3.7/dist-packages (from Adafruit-Blinka->adafruit-circuitpython-motorkit) (3.53.0)
Requirement already satisfied: adafruit-circuitpython-requests in /usr/local/lib/python3.7/dist-packages (from adafruit-circuitpython-typing==1.*,>=1.3.1->adafruit-circuitpython-register->adafruit-circuitpython-motorkit) (2.0.2)
Requirement already satisfied: pyserial>=3.0 in /usr/lib/python3/dist-packages (from pyftdi>=0.40.0->Adafruit-Blinka->adafruit-circuitpython-motorkit) (3.4)
Requirement already satisfied: pyusb!=1.2.0,>=1.0.0 in /usr/local/lib/python3.7/dist-packages (from pyftdi>=0.40.0->Adafruit-Blinka->adafruit-circuitpython-motorkit) (1.2.1)
pi@raspberrypi:~ $ sudo nano /usr/local/lib
pi@raspberrypi:~ $ sudo cd /usr/local/lib
sudo: cd: command not found
pi@raspberrypi:~ $ cd /usr/local/lib
pi@raspberrypi:/usr/local/lib $ ls -a
.  ..  libbcm2835.a  python2.7  python3.7
pi@raspberrypi:/usr/local/lib $ cd python3.7/dist-packages
pi@raspberrypi:/usr/local/lib/python3.7/dist-packages $ ls -a
.
..
adafruit_blinka
Adafruit_Blinka-8.23.0.dist-info
adafruit_bus_device
adafruit_circuitpython_busdevice-5.2.6.dist-info
adafruit_circuitpython_motor-3.4.12.dist-info
adafruit_circuitpython_motorkit-1.6.13.dist-info
adafruit_circuitpython_pca9685-3.4.11.dist-info
adafruit_circuitpython_register-1.9.17.dist-info
adafruit_circuitpython_requests-2.0.2.dist-info
adafruit_circuitpython_typing-1.9.5.dist-info
adafruit_motor
adafruit_motorkit.py
adafruit_pca9685.py
adafruit_platformdetect
Adafruit_PlatformDetect-3.53.0.dist-info
Adafruit_PureIO
Adafruit_PureIO-1.1.11.dist-info
adafruit_register
adafruit_requests.py
analogio.py
bitbangio.py
board.py
busio.py
circuitpython_typing
digitalio.py
keypad.py
microcontroller
micropython.py
micropython-stubs
neopixel_write.py
onewireio.py
pulseio.py
pwmio.py
__pycache__
pyftdi
pyftdi-0.54.0.dist-info
pyusb-1.2.1.dist-info
rainbowio.py
typing_extensions-4.7.1.dist-info
typing_extensions.py
usb
usb_hid.py
pi@raspberrypi:/usr/local/lib/python3.7/dist-packages $ sudo nano adafruit_motorkit.py
pi@raspberrypi:/usr/local/lib/python3.7/dist-packages $ cd
pi@raspberrypi:~ $ nano pibottest
pi@raspberrypi:~ $ ls -a
.              bcm2835-1.70           Motor_Driver_HAT_Code.7z
..             bcm2835-1.70.tar.gz    moverpi
.bash_history  .gnupg                 .profile
.bash_logout   .local                 wiringpi-latest.deb
.bashrc        Motor_Driver_HAT_Code
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
^[[Api@raspberrypi:~ $ 
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ exit
logout
Connection to 192.168.1.26 closed.
pl259351@7118L06 ~ % ssh pi@192.168.1.26
^C
pl259351@7118L06 ~ % ssh pi@192.168.1.26
^C
pl259351@7118L06 ~ % ssh pi@192.168.1.26
pi@192.168.1.26's password: 
Linux raspberrypi 5.10.103-v7+ #1529 SMP Tue Mar 8 12:21:37 GMT 2022 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Thu Oct 26 12:31:32 2023 from 192.168.1.16
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
^[[Api@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
^[[Api@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
^[[Api@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py
pi@raspberrypi:~ $ python3 pibottest.py
pi@raspberrypi:~ $ nano pibottest.py

  GNU nano 3.2                                                                                                               pibottest.py                                                                                                                          

# Before this code can run, the library named: adafruit-circuitpython-motorkit
# must be installed on your Raspberry Pi. Install it with this command:
# sudo pip3 install adafruit-circuitpython-motorkit

# You'll need the three lines below each time you
# write code to power the bot
from adafruit_motorkit import MotorKit
#kit = MotorKit()
# NOTE: If using the Waveshare Motor Driver Hat, change the above line to:
kit = MotorKit(0x40)
# Also, only if using the Waveshare Motor Driver Hat, be sure you've installed
# and modified CircuitPython files, in particular the file at:
# /usr/local/lib/python3.5/dist-packages/adafruit_motorkit.py
# as described in the tutorial at:
# https://gallaugher.com/makersnack-install-and-test-the-waveshare-raspberry-pi/
import time

# Forward at full throttle
kit.motor1.throttle = 0.85
kit.motor2.throttle = 0.85
# A 1.0 second sleep pauses the code while
# motors are running. After 1.0 sec., the
# lines after sleep will set throttle to zero,
# effectively turning the motor off.
time.sleep(2.5)
# Stop & sleep for 1 sec.
kit.motor1.throttle = 0.0
kit.motor2.throttle = 0.0
time.sleep(1.0)

# Left at half speed
kit.motor1.throttle = 0.75
kit.motor2.throttle = -0.75 
# let motors run for 2.0 seconds.
time.sleep(0.93)
# Stop. Sleep for 3 sec.
kit.motor1.throttle = 0.0
kit.motor2.throttle = 0.0
time.sleep(1.0)

#Forward full throttle
kit.motor1.throttle = 0.85
kit.motor2.throttle = 0.85

# Backward at 3/4 speed
#kit.motor1.throttle = -0.75
#kit.motor2.throttle = -0.75
# let motors run for 2.5 seconds
#time.sleep(2.5)
# Stop. Sleep for 1 sec.
kit.motor1.throttle = 0.0
kit.motor2.throttle = 0.0
time.sleep(1.0)

# Forward rt at full speed, backward left at 1/4 speed
#kit.motor1.throttle = 1.0
#kit.motor2.throttle = -0.25
                                                                                                                         [ Read 62 lines ]
^G Get Help       ^O Write Out      ^W Where Is       ^K Cut Text       ^J Justify        ^C Cur Pos        M-U Undo          M-A Mark Text     M-] To Bracket    M-Q Previous      ^B Back           ^◀ Prev Word      ^A Home           ^P Prev Line
^X Exit           ^R Read File      ^\ Replace        ^U Uncut Text     ^T To Spell       ^_ Go To Line     M-E Redo          M-6 Copy Text     ^Q Where Was      M-W Next          ^F Forward        ^▶ Next Word      ^E End            ^N Next Line
