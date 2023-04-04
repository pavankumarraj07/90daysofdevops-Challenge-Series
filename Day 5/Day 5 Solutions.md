# Tasks of Day 5

## Task 1: 
When the script is executed as

``./createDirectories.sh day 1 90``

then it creates 90 directories as day1 day2 day3 .... day90

### Solution:
```
#!/bin/bash
echo 'Creating Directories....'
mkdir TasksFolder
cd TasksFolder
for ((i=$2 ; i<$3 ; i++))
do
  mkdir "$1_$i"
done
```

## Task 2:
Create a Script to backup all your work done till now

### Solution
```
#!/bin/bash
back_up_file="backup$(date +%y-%m-%d-%H-%M-%S).tar.gz"
dir="/home/pavan07"
tar -czf $back_up_file $dir
echo "Backup completed : $back_up_file"
```

## Task 3:

Create 2 users and just display their Usernames
```
 sudo useradd Harsha -m
 sudo useradd Manu -m
```
![image](https://user-images.githubusercontent.com/126374902/229856622-dbebf3ad-2d62-46e4-b748-5f3767935a20.png)
