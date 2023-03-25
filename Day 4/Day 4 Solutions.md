# Tasks of Day 4

•	Explain in your own words and examples, what is Shell Scripting for DevOps.

•	What is #!/bin/bash? can we write #!/bin/sh as well?

•	Write a Shell Script which prints I will complete #90DaysOofDevOps challenge

•	Write a Shell Script to take user input, input from arguments and print the variables.

•	Write an Example of If else in Shell Scripting by comparing 2 numbers

Was it difficult?Post about it on LinkedIn and Let me know :) 

## Explain in your own words and examples, what is Shell Scripting for DevOps.
```
Shell scripting plays a very crucial role in DevOps Domain by providing a few ways to automate tasks and manage the deployment and configuration of applications and infrastructure. 

When we say Schell Scripting for DevOps, it can be used to automate tasks such as:

Deployment of applications and infrastructure
Configuration of servers and applications
Monitoring of system metrics and logs
Provisioning of resources in cloud environments
Testing and validation of software

For example, a DevOps engineer might write a shell script to automate the deployment of a web application to a server. 
The script would contain commands to install dependencies, configure the web server, and copy the application files to the server. 
The script could then be executed with a single command, saving time and reducing the potential for human error.

Overall, shell scripting is an important tool for DevOps teams to automate tasks and manage infrastructure, enabling faster deployment and more efficient collaboration between development and operations teams.
```
## What is #!/bin/bash? can we write #!/bin/sh as well?
```
#!/bin/bash is called a "shebang" or "hashbang" and is the first line in most shell scripts. 
It specifies the interpreter to be used to execute the script. In this case, it specifies that the Bash shell should be used.

The shebang line is important because it tells the operating system which interpreter to use to execute the script. 
Without the shebang line, the script would not know which interpreter to use, and attempting to execute the script could result in errors.

and

Yes, you can use #!/bin/sh as the shebang line in your shell script.

In Linux and Unix-based systems, sh refers to the Bourne shell.
The Bash shell is a more recent shell that is compatible with the Bourne shell and provides additional features and improvements.

While Bash is generally the default shell on most Linux distributions, the sh shell is still commonly used in many shell scripts because it is more lightweight and may be more suitable for certain tasks.

However,if you are using Bash-specific features in your script, it is best to use #!/bin/bash as the shebang line to ensure compatibility.

In general, the choice of #!/bin/bash or #!/bin/sh will depend on the specific requirements of your script and the systems on which it will be executed.
```
## Write a Shell Script which prints I will complete #90DaysOofDevOps challenge
```
#!/bin/bash

echo "I will complete #90DaysOfDevOps challenge"
```
## 	Write a Shell Script to take user input, input from arguments and print the variables.
```
#!/bin/bash

# Take user input
echo "Enter your name: "
read name

# Use command-line arguments
age=$1
gender=$2

# Print variables
echo "Name: $name"
echo "Age: $age"
echo "Gender: $gender"
```
Output:
```
Enter your name:
John
Name: John
Age: 25
Gender: Male
```
## 	Write an Example of If else in Shell Scripting by comparing 2 numbers
```
#!/bin/bash

num1=10
num2=20

if [ $num1 -gt $num2 ]
then
    echo "$num1 is greater than $num2"
else
    echo "$num1 is less than or equal to $num2"
fi
```
