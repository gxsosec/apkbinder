# apkbinder
Automatic backdooring apk with meterpreter (PoC)

# Dependencies
```
kali 2.0:
	python 2.7.x libraries: os re shutil zipfile tempfile argparse socket struct fcntl
	metasploit
	apktool 2.0
	dex2jar
```
	
# Components
```
apkbinder.py - APK automatic backdooring script
install.py - Install dependecies
permisos.xml - Permission of meterpreter
```

# Command line

```
usage: apkbinder.py [-h] -l LHOST [-p LPORT]

Backdooring APK with meterpreter

optional arguments:
  -h, --help            show this help message and exit
  -l LHOST, --lhost LHOST
                        LHOST select local host
  -p LPORT, --lport LPORT
                        LPORT select local port
```

# Authors

vay3t & 4c1d0_b1n4r10
