分支原因Windows7不吃這種新語法，原作者寫法支援Windows8以上
修正僅支援Windows7，不支援WinXP

原作者
https://github.com/techbliss/Yara_Mailware_Quick_menu_scanner

This is for adding the awsome Yara pattern scanner to windows right click menus.

What it Does

Right click a folder
Scan folders and subfolder files recursive for

```Antidebug
Crypto patterns
Hacking Team Mailware
Packers
Malicious documents
```

Right Click a File

Scan files for

```Antidebug
Crypto patterns
Hacking Team Mailware
Packers
Malicious documents
```

Install

Since its really just alot of registry based commands, you have to have the files at,

```
C:\yara\yara32.exe
C:\yara\icons\
C:\yara\mailware\
```

I have added all rules to date, but if you wanna do it yourself, grap new yara rules from.
https://github.com/Yara-Rules/rules

And if you want new binary prebuild(Use x86 one)I have 3.4.0 in this repo.
https://github.com/plusvic/yara/releases/tag/v3.4.0

after you have extracted everything accoring to the folder i explained.

run
```
Add_Yara_Pattern_scanner_rmenu_To_right_click_file.reg
```

then
```
Add_Yara_Pattern_scanner_rmenu_To_right_click_folder.reg
```


Folder scan
![v7ssh](https://cloud.githubusercontent.com/assets/3592375/9501061/35b4d4b2-4c29-11e5-8288-292853d9ec54.jpg)

File scan
![ouezs](https://cloud.githubusercontent.com/assets/3592375/9501143/b18e5874-4c29-11e5-868d-7f3a7ddcaa1f.jpg)

Result
![allqk](https://cloud.githubusercontent.com/assets/3592375/9501146/b4af6692-4c29-11e5-97c1-04b4f554ab69.jpg)



regards













