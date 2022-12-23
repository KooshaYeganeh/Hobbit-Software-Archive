# Hobbit-software-Archive





## Info

This software is a simple software for storing information in the database and saving the file in a specified path, which also has a graphical interface. The purpose of this software is to show the power of Linux to produce interesting software for new users. Pay attention to the size of the software)




## Install

*First You Should Install Zenity*

**Alpine**
```
sudo apk add zenity
```

**Arch**
```
sudo pacman -S zenity
```
**Fedora, RHEL, CentOS, Alma Linux and Rocky**
```
sudo dnf install zenity
```
**Debian, Ubuntu, Linux Mint, Pop OS**
```
sudo apt install zenity
```
**openSUSE**
```
sudo zypper install zenity
```

**MariaDB config**
*I added the user and password to the MariaDB settings file and you can add these settings according to your Linux distribution.*


```
mysql --execute="CREATE DATABASE test_data;use test_data;\
CREATE TABLE userinfo ( First_Name VARCHAR (100) , Last_Name VARCHAR(100) , Department VARCHAR (200) , UserID VARCHAR(200));"

```



**Install App**

```
cd /tmp
```

```
https://github.com/KooshaYeganeh/Hobbit-Software-Archive/archive/refs/heads/main.zip
```

```
unzip main.zip
```
```
Hobbit-Software-Archive-main
```

```
sudo mv Hobbit_Archive /usr/bin
```

## Run

```
Hobbit_Archive
```


## Remove

```
sudo rm /usr/bin/Hobbit_Archive
```

