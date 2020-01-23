![alt tag](https://cdn-images-1.medium.com/max/1200/1*zHmD0vnFF9phLu2LIlJJpQ.png)

# Naughty Tar Bawl
This folder contains a collection of encrytpted zip files (though not technically a tar file) that contain both non-malicious and malicious binaries from kali Linux (and other projects). The purpose of this folder and its contents is for anti-virus risk acceptance testing. 

# Side notes: 
## Encryption:
If you are wondering why I password protected the zip file, it is to prevent the AV solution you are testing from reading the contents of the archive, and removing or modifying the zip file(s) the moment you connect the thumbdrive and/or copy the files to disk.

## NaughtyExec-H Directory:
First and foremost the H in the filename stands for "Heavy". This is because I had another compressed file (along side NaughtyExec-Lite.zip) but it was too large to upload in one chuck so I split it into 75MB chucks. That file has even more content in it, about 1GB (870MB to be exact). You could use either the lite version if you want something quick or the heavy if you want to be more thorough.

## NaughtyExec-L Directory:
The naughty exe and posh (ps1) zip files are stored here. Like the dash H above, the dash L here stands for lite.

## Manifesto Directory:
These files will disclose the contents of the zip files, so you are aware of what you're extracting. 

## EICAR Directory:
If the idea of loading live malicious binaries makes you squeamish, this directory is a good alternative. The files in that directory are harmless and were designed by the European Institute for Computer Antivirus Research (EICAR) and the Computer Antivirus Research Organization (CARO).

# HOWTO: Usage
All you have to do is:
```
1. Copy the file(s) to a flash drive 
2. Unplug the flash drive 
3. Connect the flashdrive to your test machine 
4. Copy the files to disk OR Unzip the files on the flashdrive 
5. See if the AV catches the malicious binaries
6. Repeat steps 2-5 to infinium
```
You can also make a non-encrypted version and see if the AV detects the malicious binaries inside the zip file.

P.S the password to the files is below!

# Zip File Password
The zip files all share the same super secure password! (see below):
```
P4ssw0rd!
```

# AV Evasion Checklist
Use the screenshot and links (the pdfs are in the pdf folder of this directory) below to help you with your assessment
![alt tag](https://www.nextron-systems.com/wp-content/uploads/2018/06/Screen-Shot-2018-05-12-at-11.55.11.png)
1. https://www.nextron-systems.com/2018/09/08/antivirus-event-analysis-cheat-sheet-v1-4/
2. https://www.nextron-systems.com/wp-content/uploads/2018/09/Antivirus_Event_Analysis_CheatSheet_1.4.pdf
3. https://www.nextron-systems.com/wp-content/uploads/2018/09/Antivirus_Event_Analysis_CheatSheet_1.5-2.pdf
4. https://eicar.org/?page_id=3950

# Got questions?
Submit an issue or email me at gilles(dot)infosec(at)gmail(dot)com & I will address your concerns asap

```
  _   _                   _     _           _______         _                    _     _ 
 | \ | |                 | |   | |         |__   __|       | |                  | |   | |
 |  \| | __ _ _   _  __ _| |__ | |_ _   _     | | __ _ _ __| |__   __ ___      _| |___| |
 | . ` |/ _` | | | |/ _` | '_ \| __| | | |    | |/ _` | '__| '_ \ / _` \ \ /\ / / / __| |
 | |\  | (_| | |_| | (_| | | | | |_| |_| |    | | (_| | |  | |_) | (_| |\ V  V /| \__ \_|
 |_| \_|\__,_|\__,_|\__, |_| |_|\__|\__, |    |_|\__,_|_|  |_.__/ \__,_| \_/\_/ |_|___(_)
                     __/ |           __/ |                                               
                    |___/           |___/                                                
```