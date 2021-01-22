# _nodesExctractor_
**Hi there!**
You're probably so tired of unpacking one archive at a time ... Right?
Then you can try to install my script. 

Briefly about him:  
For the first time it is desirable to run the script without arguments (by the word arguments, I mean -cnn, -mnn, -n)
The script will check if there is a working directory in the folder /Downloads, if it is not detected, the script will create it.
During subsequent launches, the script will check for working directories. If they are not, he will try to create them and notify you.
So, this script works with two folders: 'sdcard/Downloads' and 'sdcard/Stick Nodes'.

sdcard/Downloads/Nodes:
/Result    | _If you using -cnd -mnd -d, results wi be in this dir._
-----------|-----------------------------------------------------
**ls.txt**| **_This is a working file in which the staple stores the names of the files I need to do something._**

sdcard/Stick Nodes:
/stickfigures | _From this folder, the program Stick nodes draws models._
--------------|---------------

## **_Installing_**
To install the seript and start using it, you need to install the Termux. I heard something has changed there and the author of the program wants everyone to switch to the version with F-Droid.
I recommend installing Termux from an F-Droid source.
F-Droid | [_Termux on F-Droid_ (_Click Here_)](https://f-droid.org/en/packages/com.termux/)
--------|-----------------------------------------------------------------
**Play Market**| [_**Termux on PlayMarket**_ _**(Click Here)**_](https://play.google.com/store/apps/details?id=com.termux)

1. Launch the app.  
2. Copy:
```bash
apt update $$ apt upgrade
```
Paste it to Termux and press enter.
3. Now we need to give Termux permission to work with the folders on the phone. To do this, write:
```bash
termux-setup-storage
```
A spit window in which you will click 'Allow'.  

4. Now you need to download the script using the command:
```bash
git clone https://github.com/VladyslavRehan/nodesExctractor
```
   4.1 Before downloading, make sure you have the git installed
   ```bash
   pkg install git
   ```

5. Now let's go to the folders with the script:
```bash
cd nodesExctractor
```

6. Let's make the installation script executable:
```bash
chmod +x installNodesExtarctor
```

