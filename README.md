## pocsuite3-pocs
Simple Some POCs for Pocsuite3

pip3 install -r requirements.txt

for RDP Scanner:
move "rdpscan_linux  rdpscan_mac  rdpscan_win.exe" on pocsuite3 folder

```
pocssuite3 ~# for x in `ls pocs/ | grep rdpscan_*`;do cp pocs/$x $(pwd);done
```
```
pocsuite3 ~# ls -l
-rwxrwxr-x  1 user  user     2156 Dis   27 18:46 cli.py
-rwxrwxr-x  1 user  user      667 Dis   27 18:46 console.py
-rwxrwxrwx  1 user  user   463024 Jan   7 12:25 rdpscan_linux
-rwxrwxrwx  1 user  user  3080608 Jan   7 12:25 rdpscan_mac
-rwxrwxrwx  1 user  user  2020352 Jan   7 12:25 rdpscan_win.exe
......
```


<br> Download Pocsuite3 here:
### <a href="https://github.com/knownsec/pocsuite3">https://github.com/knownsec/pocsuite3</a>
