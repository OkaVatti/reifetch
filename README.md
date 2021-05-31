# reifetch 
**"Something to do with cats"**
____
## ToC

[**About**](https://github.com/OkaVatti/reifetch/blob/main/README.md#about)

[**How to install**](https://github.com/OkaVatti/reifetch/blob/main/README.md#How-to-install)
- [_1. Clone to home_](https://github.com/OkaVatti/reifetch/blob/main/README.md#1-clone-the-repo-to-your-home-directory)
- [_2. Make executable_](https://github.com/OkaVatti/reifetch/blob/main/README.md#2-make-the-file-executable)
- [_3. Test the script_](https://github.com/OkaVatti/reifetch/blob/main/README.md#3-optional-test-the-script-to-make-sure-it-works)
- [_4. Rename the file_](https://github.com/OkaVatti/reifetch/blob/main/README.md#4-optional-renaming-the-file)
- [_5. Add to bin_](https://github.com/OkaVatti/reifetch/blob/main/README.md#5-adding-to-your-bin)

[****]

## About
**Reifetch** is a work in progress successor to neofetch, made exclusivly for Linux, BSD, and MacOS systems. It's mission is to be faster, lightweight, and way more user friendly. The goal of neofetch is to give it's users a better experience than neofetch. This goal is achieved by trashing all of the useless, obscure distro asciis, keeping some of the most popular options, and getting rid of all windows, ios/ipados, and old UNIX compatabilities. As well as cleaning up the config file and making some of the options a lot easier to access.

 
 ## How to install
 
Installation is relativly simple and straight forward.

**A terminal is required**

### **1.** clone the repo to your home directory.
Paste the following into your terminal
```
git clone https://github.com/OkaVatti/reifetch.git
```
this will clone the repo to your home directory

### **2.** Make the file executable
In your terminal, Navigate to the reifetch folder and make 
```
cd
cd reifetch
chmod +x reifetch.sh
```

### **3. _(optional)_** Test the script to make sure it works.
It is recommended that you test out the script to make sure it works with your system. you can use 
```
./reifetch.sh -hp
``` 
to check what distros are supported and what asciis are available for your curent version.

If a distro is missing you can message me. (contact info on profile)

### **4. _(optional)_** Renaming the file
if having the `.sh` at the end of the files bothers you so much then you can rename the file, simply delete the `.sh` from the file
```
mv reifetch.sh reifetch
```

### **5.** Adding to your bin
You're gonna wanna be able to execute the shell script from anywhere on your system, so you're gonna want to put the file in your `/bin` folder on your system. To do this, you can either use the `cp` command, or the `mv` command.
**Copy the file**
```
cp reifetch.sh /bin
```

**Move the file**
```
mv reifetch.sh /bin
```

_Obvious Note: if you followed step 4, don't type in the `.sh` at the end of your file_

