# LEARNING ABOUT LINUX



## Introduction:

Linux is a free open-source kernel. In this document, I will discuss about the origin and history of Linux; which involves all developments and contributions done by the founder. Also, various popular Linux distributions will be addressed, explaining why these distributions are important and the differences between these distributions.
Furthermore, basic Linux commands will be discussed and what has been learned about Linux and why having it is a valuable skill will be talked about.

## Section 1: Linux History:

Linux has been initiated in 1990's and is created by linus Torvalds a student in university of Helsinki. In 1991 he aimed to make an operating system which is free and open-source alternative to MINIX operating systems.the first version of linux consists of few thousand lines of code. Linux was heavily influenced by UNIX, an operating system developed in 1970 at bell labs. Onyx system begin to sell the microcomputers-based UNIX workstations. In 1983 the GNU project by Richard Stallman provided the many tools and utilities that make Linux kernel making an complete operating system.
In the era 1990’s and 2000’s Linux grow rapidly, as an opensource software it allowed any one to modify and distribute the software leading to create multiple distributions. After that major companies like IBM also started to support and develop it.
Now a days it is used in android phones and supercomputers, servers and desktop systems because of its flexibility, security and open-source nature.

## Section 2: Linux Distributions:

### Importantce of Linux Distribution

1. *Customization:* They allow their users to customize their Operating Systems to fit their Specific needs.
2. *Cost-Effective:*  Most Distibutions are for usage.
3. *Security:* Linux is also know for it's sting security featuers.
4. *Community Support:* Beign Opensource allows many devlopers and users to create updates and support.

### Examples of Linux Popular Distribution

1. *Ubuntu:-* Debian Based OS used widley in Servers and Desktops
2. *Redhat:-* Used for enterprise Usage.
3. *Fedora:-* Open source but used as RedHats upstream
4. *Kali Linux:-* Used for SecOps

### Main Differnce in Distros

1. *Pack Package Management*
2. *Release Model*
3. *Target Audience*
4. *Desktop Enviorment*

## Section 3: Basic Linux Commands:
1. 
    
    touch - ex > xyz.py - Creating file
2.

    apt install / yum install > eg - apt install httpd > installing tools and software

3.

    mkdir > eg - mkdir newfolder > create new directories 

4. 

    mv > eg - mv newfolder /home/user2/ move files this can also be utilzied to rename files 

5. 


    rm > eg - rm test.py > delete folder 

6. 
    
    grep > eg - grep 'xyz' test.log > search inside files 

7. 
    
    tail -f > eg - tail -f test.log > tailing log files while they are being written 

8. | > merge 2 commands together 

        Eg - tail -f test.log | grep "error" -- This command checks the lines which as string error in it while it's being written 

9. 

    sudo > eg - sudo apt update > use root user privileges 

10. 

    nmtui - open network manager 

11. 
    
    cat > eg - cat test.config > view entire txt file 

12. 

    systemctl > eg - sudo systemctl start nginx - we can use systemctl to start stop and enable services

13. 

    ps -a > view all currently running processes 

14. 

    kill > eg - kill -9 1776 > we can use kill commands to terminate currently running processes 

15. 

    ls -lah > view all files and directories inside directory 

16. 

    df -h > view disk utilization
17. 

    free -h > view memory utilization (ram)
18. 


    top - view advanced utilization status (each CPU utilization alongside individual process utilization )
19. 


    chmod > eg - chmod 777 test.py > changing the permissions of files and folders (read write execute)
20. 

    chown > eg - chown nipuna:nipuna test.py > changing ownership of files to different users
## Conclusion:

We Learned About History of Linux,Uasge of each Distors in many difference Casees and Basic Commands.We feel the reason of linux bing a valuble skill as most used it and it give the user more flexiblity for usage