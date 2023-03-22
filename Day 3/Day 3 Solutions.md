## Day 3 of 90daysofdevops

👣 Topics for #day3
```
What is File management and Directory management?
Linux commands for File management and Directory management
```

What is File management and Directory management?
```
File Management:

File management refers to the process of creating, organizing, storing, manipulating, and deleting files on a computer or other electronic devices. It involves managing files in a way that makes them easily accessible, searchable, and secure.

File management involves several tasks, including creating new files, organizing them into directories or folders, renaming, copying, moving or deleting files, and setting permissions to control who can access or modify the files. Additionally, file management involves backing up and archiving files to prevent data loss in case of disasters, such as hardware failures, viruses, or accidental deletion.

Good file management practices can help users find files more quickly and easily, avoid data loss or corruption, and protect sensitive information from unauthorized access.

Examples of file management tools include the File Explorer in Windows, Finder in macOS, and command-line tools in Linux and other Unix-like operating systems.

Directory Management:

Directory management, also known as folder management, is the process of creating, organizing, manipulating, and deleting directories or folders on a computer or other electronic devices. A directory or folder is a container for files and other directories, allowing users to organize their data in a hierarchical manner.

Directory management involves several tasks, including creating new directories or folders, organizing them into a logical structure, renaming, moving or deleting directories, and setting permissions to control who can access or modify the directories.

Overall, File and Directory management is an essential component of using a computer, and mastering this skill can help users better manage their data, improve productivity, and keep their files secure.
```
**Linux commands for File & Directory management**
```
To view what is written in a file --> cat filename

To change the access permissions of files --> chmod

To check which commands, you have run till now --> history

To remove a directory/ Folder --> rmdir directoryname

To create a fruits.txt file and to view the content --> touch fruit.txt 
      cat fruit.txt 
            or
      cat > fruit.txt
      cat fruit.txt
      
To Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava --> vim devops.txt

To Show only top three fruits from the file --> head -3 devops.txt

To Show only bottom three fruits from the file --> tail -3 devops.txt

To create another file Colors.txt and to view the content --> cat > Colors.txt and cat > Colors.txt

To Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey cat --> vim Colors.txt

To find the difference between fruits.txt and Colors.txt file --> diff <file1name> <file2name>
```
